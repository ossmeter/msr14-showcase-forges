msr14-showcase-forges
=====================

A MongoDB dump of the data can be downloaded here: https://www.dropbox.com/s/hp2nl3xw3jzz3wk/msr14-forges-dump.zip

To load the data you'll need MongoDB installed (http://docs.mongodb.org/manual/installation/), then you need to unzip the file and run `mongorestore` in the directory containing the `dump` folder (see http://docs.mongodb.org/manual/reference/program/mongorestore/):

```mongorestore --dbpath=/your/database```
