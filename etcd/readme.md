# [etcd](https://github.com/etcd-io/etcd) 集群快速搭建

quay.io/coreos/etcd 次镜像来源于 红帽维护的 etcd docker 镜像仓库

使用 红帽仓库 的 etcd 镜像 原因 :

hub.docker.com 中的 etcd 官方镜像(elcolio/etcd
)太旧了 Updated 4 years ago [4 年前更过目前还是 2.0 版本的 etcd]

## 启动

第一次启动请使用 : `start.sh`

```bash
 ./start.sh          # 运行脚本 启动集群
 ./start.sh gen     # 生产固定配置信息的docker-compose.yml 文件到build 目录中
 ./start.sh info    # 查看集群运行状态
 ./start.sh stop    # 停止集群
 ./start.sh reload  # 集群热重重启
 ./start.sh restart # 集群重启
```
