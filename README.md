# python-web-fastapi-api-dolt-simple

## Description
Simple web app that serves api
for a fastapi project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - fastapi
  - uvicorn
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- dolthub/dolt-sql-serverdb

## Docker stack
- python:latest
- dolthub/dolt-sql-serverdb:latest

## To run
`sudo ./install.sh -u`
- [Availble at](http://localhost/dogs)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Fastapi sqlalchemy setup](https://fastapi.tiangolo.com/tutorial/sql-databases/)
