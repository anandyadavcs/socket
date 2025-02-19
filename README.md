
# Log Socket
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

Log Socket is a application to read most recent lines of a log file placed remotely on a server using websockets on web browser. At every refresh it will return top N lines of log for a configured log file. This is a multithreaded application, will support multiple users.



## Run Locally

Clone the project

```bash
  git clone https://github.com/anandyadavcl/socket.git
```

Go to the project directory

```bash
  cd socket
```

Install dependencies

```bash
  mvn install
```

Start the server

```bash
  mvn spring-boot:run
```


## Environment Variables

To run this project, you will need to configure the log file path in constants file.

- [Constants.java](https://github.com/anandyadavcl/socket/blob/1631cd5b5497c3bd9313d83eda691f34715faac1/src/main/java/com/anand/socket/constants/Constants.java#L4)



