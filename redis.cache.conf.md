
### 压力不大，cache没有开RDB和AOF，也没有Slave

#Limits

* maxclients 10000 #default is 10000

* maxmemory 4294967296 #4G

* maxmemory-policy volatile-lru

* maxmemory-samples 5 #default is 3
