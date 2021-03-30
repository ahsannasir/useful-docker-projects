# useful-docker-projects

A random small repository containing useful docker projects that I've build along the way so you don't have to.

### Kafka
A docker-compose file that starts kafka with 3 brokers, 3 zookeepers instances and a kafka cluster manager that you can access at localhost:9000. The docker-compose file also takes care of persistent volumes for data storage in kafka brokers.


You can use the docker-compose like:

```
 MY_IP="127.0.0.1" docker-compose up
```

**Don't forget to pass MY_IP environment variable like**

More projects to be added soon...

Happy Clouding! <3
