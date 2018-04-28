# nyw_data
Data infrastructure for [nywater.info](http://nywater.info)

This repository provisions a [MongoDB](https://www.mongodb.com/) server, a [Mongo-Express](https://github.com/mongo-express/mongo-express) admin interface, and a [Jupyter](http://jupyter.org/) notebook server.

## Getting Started

### Prerequisites
- Docker + Docker-Compose (version?)

### Run the services
```
docker-compose up
```

### Getting the data
The CSV datafiles are available from the following locations:
- [Lead Testing in School Drinking Water: Buildings with Lead-Free Plumbing Beginning 2016](https://health.data.ny.gov/Health/Lead-Testing-in-School-Drinking-Water-Buildings-wi/5hbp-c6bb)
- [Lead Testing in School Drinking Water Sampling and Results: Most Recently Reported Beginning 2016](https://health.data.ny.gov/Health/Lead-Testing-in-School-Drinking-Water-Sampling-and/rkyy-fsv9)

### License
[MIT License](http://opensource.org/licenses/MIT).

### Technologies used

- [Jupyter Datascience Notebook](https://hub.docker.com/r/jupyter/datascience-notebook/)

- [Pandas](https://pandas.pydata.org/)

- [PyMongo](https://api.mongodb.com/python/current/)
