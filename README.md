# jfinal
使用jfinal shiro mhcache jetty 构建的 maven 项目
是一个后台管理项目；
登录 /admin 用户名和密码分别是：admin 123123；
ztree使用simpledata实现树形结构；
遇到的bug是：mhcache容易把缓存留在本地磁盘，难以清除；
mhcache 容易宕机，有明显的bug，但是广泛应用；
memcache 做缓存还是比较好；
redis 做急速存取的数据库比较好；
mongodb适合做分布式存储；
由于开发的时候考虑到时间成本暂时用mhcache，这里推荐使用redis
