# scala-web-bloop-sbt-spring-thyme-ssl-postgres-simple

## Description
A POC for springboot web app with thymeleaf support
connecting to a self-signed ssl enabled postgres database.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - springboot
  - thymeleaf
  - postgres connector
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine
- postgres
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://spring.io/guides/gs/accessing-data-mysql/
- https://medium.com/@gustavo.ponce.ch/spring-boot-jquery-datatables-a2e816e2b5e9
