
### 一定要设置最大内存maxmemory参数，否则物理内存用爆了就会大量使用Swap

#Limits

* maxclients 10000 #default is 10000

* maxmemory 2147483648 #2G

* maxmemory-policy volatile-lru

* maxmemory-samples 5 #default is 3
