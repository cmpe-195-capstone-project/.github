## CMPE 195 Capstone Project  


EmberAlert is a wildfire incident monitoring platform.
It collects wildfire data from Cal Fire, processes it, and makes it available to client applications through a REST API and WebSocket updates.

---

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


> Note: The backend services (API server + scheduler + database) are designed to be run using the Docker Compose configuration found in the `infrastructure` repo.
