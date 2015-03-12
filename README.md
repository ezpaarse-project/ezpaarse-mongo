# ezpaarse-mongo

Directory structure sample for mongo use with ezpaarse (>= 2.2.0)
You will use this sample if you want to have ezpaarse dedicated mongo database in application environement

## Prerequisites ##

You must have an [ezpaarse installation](https://github.com/ezpaarse-project/ezpaarse) and [mongodb](https://github.com/ezpaarse-project/ezpaarse/blob/master/doc/quickstart.md#installation-de-mongodb) ready to run

## Installation quickstart ##


To install ezpaarse-mongo on a Unix-type system, open a terminal and type:
```shell
git clone https://github.com/pseudom/ezpaarse-mongo.git
cd ezpaarse-mongo
./init-config
```

This will generate all the stuff needed for your mongo instance for ezpaarse

To start your mongo for ezpaarse :
```shell
./etc/init.d/mongod start
```
To connect ezpaarse with your mongod instance, copy the generated config.local.json file in your ezpaarse installation (or update yours with the EZPAARSE_MONGO_URL value) and restart ezpaarse.

