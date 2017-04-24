# Useful Commands

## General Commands for mac dev machine
MAC find program running in specific port  
sudo lsof -i :80 # checks port 80



## Doker commands 
  * docker exec -i -t 665b4a1e17b6 /bin/bash or  
  * docker run -it --rm alpine /bin/sh

## Cassandra commands  
### Start Cassandra
cd /{Cassandra_Directory}/bin/cassandra
$ sudo kill pid

### Stop Cassandra
Stop cassandra ps auwx | grep cassandra  
$ sudo kill pid

