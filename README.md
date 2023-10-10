# java-cli-maven-ssl-postgresql-data-type-uuid

## Description
Creates a small table `dog` that uses
a uuid data type.

A java maven build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- maven
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
