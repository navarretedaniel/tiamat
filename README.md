# tiamat
Pymongo tutorial with NOAA metadata records

In this lab, we will use Pymongo to store [NOAA metadata](https://data.noaa.gov/data.json) records to a database.

![Tiamat](https://github.com/rebeccabilbro/tiamat/blob/master/images/tiamat.jpg)  

_By Internet Archive Book Images [No restrictions], via Wikimedia Commons_


## Install MongoDB
First, install [MongoDB](https://docs.mongodb.org/manual/administration/install-community/).

[__OSX__](https://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/)    
```bash
$ brew install mongodb
```

[__Linux__](https://docs.mongodb.org/manual/administration/install-on-linux/)    

[__Windows__](https://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/)    

## Install Pymongo
Next, make sure you have `pymongo` [installed](https://api.mongodb.org/python/current/installation.html). Type this into your terminal:

```bash
$ python -m pip install pymongo
```

## Clone this repo  

```bash
$ git clone https://github.com/rebeccabilbro/tiamat.git
$ cd tiamat
```

## Install Jupyter if you don't already have it

```bash
$ pip install jupyter
```

## Launch the Jupyter Notebook

```bash
$ jupyter notebook MongoDBTutorial.ipynb
```
