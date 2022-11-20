# Damn Vulnerable Web App

This docker-compose setup will install everything you need to run [Damn Vulnerable Web App (DVWA)](https://github.com/digininja/DVWA)

# Requirements

- [Docker Engine](https://www.docker.com)
- [Docker Compose](https://docs.docker.com/compose/install/)

# Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dockfiles/Damn-Vulnerable-Web-App.git dvwa
```

cd into the new directory

```bash
cd dvwa
```

### 2. Ready to start!

- To start DVWA use this command:

```bash
docker compose up -d
```

- Go to `localhost:80` on your web browser and you should see the login page.

### 3. Login Credentials

The default login credentials for DVWA are:
username: admin
password: password
