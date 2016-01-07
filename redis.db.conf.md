### 一定要设置最大内存maxmemory参数, 否则物理内存用爆了就会大量使用Swap, 而且线上机器要关闭Swap
### 一般使用内存上限为45%是比较安全的阈值，所以例如16G内存的机器，碎片率为0.2，那么maxmemory设置为16*0.45/1.2=6G比较合适

## Limits

* maxclients 10000 #default is 10000

* maxmemory 6442450944 #6G

* maxmemory-policy noeviction

* maxmemory-samples 5 #default is 3
