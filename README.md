MSR14 Data Showcase: OSS Forge Meta-Data
=====================

This project hosts the datasets for the following paper accepted at MSR 2014's Data Showcase track (http://2014.msrconf.org/data.php):

James R. Williams, Davide Di Ruscio, Nicholas Matragkas, Juri Di Rocco, Dimitris S. Kolovos, _Models of OSS Project Meta-Information: A Dataset of Three Forges_

A MongoDB dump of the data can be downloaded here: http://ifolder.di.univaq.it/msr14-forges-dump.tar.gz

To load the data you'll need MongoDB installed (http://docs.mongodb.org/manual/installation/), then you need to unzip the file and run `mongorestore` in the directory containing the `dump` folder (see http://docs.mongodb.org/manual/reference/program/mongorestore/):

```mongorestore --dbpath=/your/database```
