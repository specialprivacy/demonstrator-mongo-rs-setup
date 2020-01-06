# demonstrator mongo rs setup
This docker container runs a one off script that will configure the docker container that runs the mongo db database. It will change the mongo configuration to also produce change events.

# configuration
This service expect the mongo db container to be running and to be named mongo-db. It also expects it to run on the default port 27017. The username and password for the database is configuratble with environment variables:
MONGO_DB_USER and MONGO_DB_PWD.