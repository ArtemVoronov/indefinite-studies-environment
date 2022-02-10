# Building and running the Docker images
1. Set environment vars in the config `.env` e.g.:
```
DATABASE_NAME=indefinite_studies_api_db
DATABASE_USER=indefinite_studies_api_user
DATABASE_PASSWORD=password
DATABASE_ROOT_PASSWORD=password
DATABASE_URL=jdbc:postgresql://postgres:5432/indefinite_studies_api_db
DATABASE_DRIVER_NAME=org.postgresql.Driver
```