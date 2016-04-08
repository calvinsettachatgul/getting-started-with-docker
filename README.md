mfrom https://scotch.io/tutorials/getting-started-with-docker


### what is docker?

hardware and platform independent

in the past it was a vm (virtual machine)

containers are smaller and have far less overhead

vm not as portable docker container extremely portable

vm no versioning, logging/monitoring
docker images layers can be verison controlled
docker has logging functionality

what could go into a container?
isolate pieces of system into sep containers
nginx, MongoDB, Redis
easy to set up

much easier than vm even something like vagrant

### installation

$ wget http://download.redis.io/releases/redis-stable.tar.gz
$ tar xzf redis-stable.tar.gz
$ cd redis-stable
$ make
$ make install
$ ./utils/install_server.sh

$ service redis_6379 start
