# groovy-cli-gradle-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

## Tech stack
- groovy
- gradle
  - log4j
  - postgres driver

## Docker stack
- postgresql:alpine
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
