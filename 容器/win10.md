## volumes 路径问题 

### docker-compose 启动容器和docker run -v 启动容器时
会出现启动不成功问题

#### 解决办法, 设置文件共享
  
    settings->resource->file sharing
    add f:\docker
    docker-compose.yml 文件
        volumes:
            - f://docker/elk/data/es:/usr/share/elasticsearch/data
