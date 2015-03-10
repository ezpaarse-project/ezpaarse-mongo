# ezpaarse-mongo

Directory structure sample for mongo use with ezpaarse (>= 2.2.0)
You will use this sample if you want to have ezpaarse dedicated mongo database in application environement

## Prerequisites ##

You must have an ezpaarse installation ready to run

## Installation quickstart ##


To install ezpaarse-mongo on a Unix-type system, open a terminal and type:
```shell
git clone https://github.com/pseudom/ezpaarse-mongo.git

```

Fill {{ezpaarse-mongo-path}}, {{ezpaarse-mongo-user}}, {{ezpaarse-mongo-group}} with your needs in etc/mongod.conf and etc/init.d/mongod files.
Check that {{ezpaarse-mongo-port}} is in mongo URL from your ezpaarse config.local.conf (like "EZPAARSE_MONGO_URL": "mongodb://localhost:50000/ezpaarse")


