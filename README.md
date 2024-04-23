# CTFD-Docker

ctfd-docker版本是flag动态靶场的快速搭建版，基于frp、ctf-whale搭建的，只需要允许一下命令即可搭建成功

```shell
docker-compose up -d
```

由于基于docker-compose、docker所以前提是要完成docker的安装工作

使用官方安装脚本
```shell
curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun
```
docker-compose安装

```shell
sudo curl -L "https://github.com/docker/compose/releases/download/v2.26.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```