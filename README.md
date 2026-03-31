Docker Compose Multi-Container Project

## Description
This project demonstrates how to run multiple containers using Docker Compose.

---

## Architecture
- Nginx (Web Server)
- MySQL (Database)

---

## Features
- Multi-container setup
- Service-to-service communication
- Simplified deployment using docker-compose

---

## Steps to Run

```bash
docker-compose up -d
docker ps

## Network Testing
```
docker exec -it <container id> bash
yum update
yum install iputils-ping -y
ping db

---
## Screenshots
<img width="926" height="437" alt="Screenshot 2026-03-31 164208" src="https://github.com/user-attachments/assets/a40b0d3e-59f0-49b8-9bc5-750144975ce0" />
<img width="1919" height="386" alt="Screenshot 2026-03-31 164615" src="https://github.com/user-attachments/assets/9ac8189a-29ac-482b-b756-bdf13847d4db" />
<img width="1632" height="494" alt="Screenshot 2026-03-31 165821" src="https://github.com/user-attachments/assets/16fa1332-ab8a-4140-b67c-9c3192c49ec5" />
<img width="1919" height="965" alt="Screenshot 2026-03-31 165146" src="https://github.com/user-attachments/assets/61328469-baee-43ae-b9ec-b4a5297cba00" />

Author
Dhinakar M
