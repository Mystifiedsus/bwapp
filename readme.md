# bWAPP (Buggy Web Application)

bWAPP is a deliberately insecure web application designed for practicing and learning about web application security. It contains numerous security vulnerabilities and is intended for educational and training purposes.

## Setup using Docker

### 1. Pull the bWAPP Docker Image

Open a terminal and run the following command to pull the bWAPP Docker image:

```bash
docker pull raesene/bwapp
```

### This command starts the bWAPP container in detached mode (-d), maps port 80 on your host to port 80 on the container (-p 80:80), and maps port 3306 on your host to port 3306 on the container (-p 3306:3306).

3. Access bWAPP
Open your web browser and navigate to http://localhost/bWAPP to access the bWAPP web interface.

4. Login
The default login credentials for bWAPP are:

Username: bee
Password: bug
Use these credentials to log in and start exploring the vulnerabilities and challenges provided by bWAPP.

Important Note
bWAPP is intentionally insecure, and it is recommended to run it in a controlled environment, such as a local development machine or a virtual machine. Do not expose bWAPP to the public internet without proper security precautions.

Remember that bWAPP is a learning tool, and it is crucial to use it responsibly for educational purposes only. Always be aware of the security risks associated with intentionally vulnerable applications.
