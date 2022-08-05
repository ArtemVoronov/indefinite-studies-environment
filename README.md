# How to build and run
1. Set environment vars in the config `.env` e.g.:
```
DATABASE_NAME=indefinite_studies_api_db
DATABASE_USER=indefinite_studies_api_user
DATABASE_PASSWORD=password
```
2. Check `docker-compose.yml` is appropriate to config that you are going to use (e.g.`docker-compose config`)
3. Build images: `docker-compose build`
4. Run it: `docker-compose up`
5. Stop it: `docker-compose down`