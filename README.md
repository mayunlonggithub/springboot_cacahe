## springboot_ehcache
#### springboot整合ehcache实现缓存
---
## springboot_redis
#### springboot整合redis
---
## springboot_rediscache
#### springboot整合redis实现缓存
---
## springboot_rediscluster
#### springboot整合redis集群
##### 执行如下命令创建redis集群：./redis-trib.rb create --replicas 1 192 .168 .248 .144 :8001 192 . 168.248 .144 :8002 192.168.248.144: 8003 192.168.248.144:8004 192.168.248.144:8005 192.168.248.144:8006
##### 将主节点添加到集群命令：./redis-trib.rb add-node 192.168.248.144:8007 192.168.248.144:8001
##### 对slot槽重新分配命令：./redis-trib.rb reshard 192.168.248.144:8001
##### 添加从节点命令：./redis-trib.rb add-node --slave --master-id e0f275lb46c9ed3cal30e9fc825540386feaafb2 192.168.248.144:8008 192.168.248.144:8001
##### 删除从节点命令：./redis-trib.rb del-node 192.168.248.144:8001 122b2098df746afc3a77beddaad85630bf75ab9a
---
## springboot_redisclustercache
#### springboot整合redis集群实现缓存




