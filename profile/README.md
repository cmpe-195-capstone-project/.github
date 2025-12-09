## CMPE 195 Capstone Project  


EmberAlert is a wildfire incident monitoring platform.
It collects wildfire data from Cal Fire, processes it, and makes it available to client applications through a REST API and WebSocket updates.

---
[Video of Demo](https://youtu.be/nEmRQxMZpZU)

Team Members
- Nhat Tran
- Mariam Matar
- Alicia Zhao
- Carlos Quiroz-Vasquez

### Project Repositories
- `frontend`: the EmberAlert mobile client that lets users view wildfire incident data and notifications.
- `backend`: provides REST endpoints and WebSocket notifications for wildfire data.
- `scheduler`: background service that polls the Cal Fire API, cleans data, and stores it in PostgreSQL.
- `infrastructure`: Docker Compose deployment for the API server, scheduler, and PostgreSQL database and testing for backend.

### Setup
Our **backend** is currently deployed on an AWS EC2 instance, but it can also be run locally using Docker.  
The **mobile client** can be run by going to the `frontend` directory, where installation and startup instructions are provided in the corresponding README file.
- Setup and execution instructions for the backend are provided in the README file located inside the `backend` directory. All backend services (API server, scheduler, and PostgreSQL database) can be started together using Docker Compose.

  
