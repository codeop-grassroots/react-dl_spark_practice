# Apache Spark

## Introduction
A primer approach to Apache Spark with PySpark


## Getting started

### Requirements
- Docker
- Docker compose

##### With Docker Compose: the easy way

`````
docker-compose up
`````

#### With Docker

To run the project first we need to pull the docker image:
````
docker pull jupyter/pyspark-notebook
````

Once we have the image downloaded, we can run it:
````
docker run -v ~/nbs:/home/jovyan/work -d -p 8888:8888 jupyter/pyspark-notebook
````

To preserve your work:
`````
sudo chown 1000 ~/nbs
`````


### The project

`warm_up.ipynb` => In this notebook you will find the questions you need to find an answer. Question 1 and 5 have already been solved to get you familiarized with the Spark SQL syntax<br>
Hint: Think how would you do this with plain SQL and then find the way to translate the plain SQL syntax to Sqpar SQL.
