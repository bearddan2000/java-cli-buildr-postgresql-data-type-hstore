# java-cli-buildr-postgresql-data-type-hstore

## Description
Creates a small table `dog` that uses
a key value pair data type.

## Tech stack
- java
- buildr
  - log4j
  - postgresql driver

## Docker stack
- postgresql:alpine
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[HStore data type info](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-hstore/)
