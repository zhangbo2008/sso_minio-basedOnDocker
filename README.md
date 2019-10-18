# sso_minio-basedOnDocker
一个minio实例,完全配置好了,直接能用



使用方法:
docker pull docker.io/zhangbo2008/minio_saving:v2
然后看/readme  里面的说明使用即可.
能配置的都配置了.







 -----------------------readme.txt---------------------------------

本dockker镜像是为了对象存储而做的,是单点村粗,不是分布式.
docker run -t -u root -i  -p 0.0.0.0:8080:8080    镜像名     /bin/bash
#运行这这个sh时候会报错,再运行一次即可,因为第一次要生成配置文件而已.
#无关大雅.
运行方法
#
进入899目录

然后运行sh kaishi.sh即可.

然后任意一个电脑上输入ip:8080/mybucket/文件名.xxx 即可浏览文件和下载文件

使用说明:


存文件:存到/data/mybucket 里面即可.
读和下载:任意一个电脑上输入ip:8080/mybucket/文件名.xxx 即可


