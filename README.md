# java-web-gradle-spring-thyme-postgres-ssl-simple

## Description
A thyme springboot java gradle build,
that connects to self-signed ssl enabled postgres database.

## Tech stack
- springboot
  - web
- thymeleaf
- gradle
  - 6.8.2
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine
- postgres
- gradle:jdk11

## To run
`sudo ./install.sh -u`
Available http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Postgres SSL Config](https://dev.to/danvixent/how-to-setup-postgresql-with-ssl-inside-a-docker-container-5f3)
