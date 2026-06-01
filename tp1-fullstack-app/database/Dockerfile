# base image
FROM postgres:17.2-alpine

# Environnement variable
ENV POSTGRES_DB=db

# Copy initialization scripts
COPY ./sql/ /docker-entrypoint-initdb.d/