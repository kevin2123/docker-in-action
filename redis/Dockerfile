#基于哪个镜像
FROM redis

#镜像创建者
MAINTAINER Frank "zhangfu@i2finance.net"

WORKDIR /data

#用来设置环境变量,KV结构


#安装软件用


#container内部服务开启的端口。主机上要用还得在启动container时，做host-container的端口映射：
EXPOSE 6379


#Container启动时执行的命令，但是一个Dockerfile中只能有一条CMD命令，多条则只执行最后一条CMD.
CMD ["redis-server", "/etc/redis/redis.conf"]