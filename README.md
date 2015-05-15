# rockmongo-docker-image

Repository to build a rockmongo docker image.

## How to

Running the resulting image will bring up a rockmongo server, which can be
configured with the following environment variables:

* `MONGO_HOST`: the hostname of the mongo server, e.g. `mongo.example.com`
* `ROCKMONGO_USER`: the username of the rockmongo control user
* `ROCKMONGO_PASSWORD`: the password for the rockmongo control user
