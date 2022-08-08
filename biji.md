笔记



docker ps 显示所有容器

docker images 显示所有镜像

docker run imagesID 启动镜像

docker restart containerId 启动容器

docker rm 容器id

docker rmi 镜像id

docker cp /宿主机文件夹   容器id:/容器文件夹

(1)find / -name httpd.conf　　*#在根目录下查找文件httpd.conf，表示在整个硬盘查找*

ps -aux|grep redis   查看正在运行的redis

cp -r /home/packageA/* /home/cp/packageB/  将一个文件夹下的所有内容复制到另一个文件夹下

./redis-trib.rb create --replicas 1 127.0.0.1:7000 127.0.0.1:7001 \ > 127.0.0.1:7002 127.0.0.1:7003 127.0.0.1:7004 127.0.0.1:7005   redis启动集群