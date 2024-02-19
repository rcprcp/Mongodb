# MongoDB Test Program

First try working with MongoDB in Java. I have been testing this with Mongo Atlas. Work in progress, please read this code before trying to run it.  :) 

You'll need to configure the environment variables to fit your setup - you'll need the cluster ID, username and password.
```shell
export MONGODB_CLUSTER_ID=cluster0.blahblah
export MONGODB_PASSWORD=mypassword
export MONGODB_USERNAME=myusername
```
the usual Maven incantation should be enough to build the runnable jar. 

```shell
git clone https://github.com/rcprcp/MongoDB
cd MongoDB
mvn package
java -jar target/MongoDB-1.0-SNAPSHOT-jar-with-dependencies.jar
```

TODO: 

- Need to finish setting up the logger; remove the System.out.println's
