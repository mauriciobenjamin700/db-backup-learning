FROM postgres:12

RUN apt-get update && apt-get install -y make

COPY Makefile /scripts/Makefile

ENV POSTGRES_DB=YOUR_POSTGRES_DB
ENV POSTGRES_USER=YOUR_POSTGRES_USER
ENV POSTGRES_PASSWORD=YOUR_POSTGRES_PASSWORD

WORKDIR /scripts

EXPOSE 5432
