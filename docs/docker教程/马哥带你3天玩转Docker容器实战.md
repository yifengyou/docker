<!-- MDTOC maxdepth:6 firsth1:1 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [马哥带你3天玩转Docker容器实战](#马哥带你3天玩转docker容器实战)   
   - [课程优势](#课程优势)   
   - [课程大纲](#课程大纲)   
   - [讲师介绍](#讲师介绍)   
   - [我的笔记](#我的笔记)   
      - [基本概念](#基本概念)   
      - [安装及使用](#安装及使用)   
   - [docker镜像和容器操作](#docker镜像和容器操作)   
   - [运行容器相关操作](#运行容器相关操作)   
      - [docker Registry分类](#docker-registry分类)   
   - [获取镜像](#获取镜像)   
   - [docker镜像制作](#docker镜像制作)   
      - [镜像导入导出](#镜像导入导出)   
   - [相关笔记](#相关笔记)   

<!-- /MDTOC -->
# 马哥带你3天玩转Docker容器实战

Docker 是一个开源的应用容器引擎，让开发者可以打包他们的应用以及依赖包到一个可移植的容器中，然后发布到任何流行的 Linux 机器上，也可以实现虚拟化。容器是完全使用沙箱机制，相互之间不会有任何接口。Docker自2013年以来非常火热，无论是从 github 上的代码活跃度，还是Redhat在RHEL6.5中集成对Docker的支持, 就连 Google 的 Compute Engine 也支持 docker 在其之上运行。

它启动很快。启动一个Docker容器只需50毫秒。没有看错，是真的这么快。这就是使用高层级抽象的好处，这样减少了你所需运行的组件的数量。这也意味着，在它执行的过程中几乎没有额外的开销。

一键（单命令）部署。它是真的简单到安装一个应用只需输入一行命令。想要安装MySQL？一行命令。想到一下子把WordPress, MySQL, Nginx and Memcache全部安装并且配置完成？统统一行命令。

扩展性。这也是Docker很亮眼的特性之一，特别是，如果你的项目是基于微服务的。Compose and Swarm用来部署可扩展的应用系统，加上Kubernetes、Mesos等第三方应用，这两方面使服务器的扩展性提高到了更高的层级。可承载多达数百万级数量的容器的管理能力。

资源隔离。在过去，如果你想运行所有的服务在同一台服务器上，这可能会耗尽服务器的所有资源。Docker允许你基于各自应用或服务，进行设置、监听、调整。

Docker容器几乎可运行于任意的Linux平台，包括物理机、虚拟机、公有云、私有云、个人PC、服务器等。用户可以很方便地将应用程序在各平台间迁移。国内腾讯、百度、阿里、京东、小米、新浪、美团点评、滴滴等公司不断的加入，也随着Kubernetes技术也不断成熟，2019年将会有更大的应用和发展。掌握Docker、Kubernetes，是运维、开发、测试必不可少的高薪技能。


##  课程优势

本课程为市面上不可多得的全面Docker体系课程，其他同类线下Docker培训大多售价在2000-4000RMB，内容为2天10个课时左右。而本课程有14个课时专业内容，限时特价198，为其他培训价格十分之一，含金量为其他同类Docker课程2-3倍，并由国内Linux教父-马哥亲授。

1、课程内容讲解Docker版本为目前官方最新版18.06，并全面介绍其新特性，领先于市面上教程。

2、本课程会以企业实际应用为主线，对整个Docker架构进行全方面讲解。

3、本课程以理论+实战结合方式教学，让你知其然并知其所以然。

4、本课程为福利课程，原本定价800RMB，但近期新闻有说谷歌要回归，为迎接谷歌回馈开源，特此福利价198。



## 课程大纲

内容含金量为同类docker课程2-3倍不止，并由国内Linux教父-马哥亲授。
```
一、Linux容器技术基础

1、容器技术发展史

2、Namespace和CGroups

3、LXC和容器技术

二、Docker容器技术基础

1、Docker技术构架

2、安装部署Docker

3、Docker的镜像及容器的基础应用

三、Docker镜像

1、Docker镜像工作原理

2、基于容器制作Docker镜像

3、推送Docker镜像至Registry

4、镜像的本地分发

四、Docker网络

1、Docker网络模型及工作原理

2、Docker网络模型验正

3、暴露容器应用至节点外部

4、桥接式网络管理

5、配置Docker进程的网络属性

五、存储卷

1、存储卷类型及功能

2、存储卷应用

3、存储卷共享

六、Dockerfile

1、Dockerfile文件格式

2、各指令详解

3、案例：自定义entrypoint脚本，接收变量进行容器化应用配置

七、私有Registry

1、Registry的组织格式

2、利用docker-registry构建简单的私有Registry

3、docker-compose简介

4、使用VMWare Harbor构建企业级私有Registry

八、容器资源限制

1、资源限制模型

2、CPU资源限制及三种形式及其应用

3、内存及Swap资源限制及其应用

4、案例：使用stress-ng镜像验正资源限制效果
```


## 讲师介绍

马哥（马永亮）：马哥教育创始人CEO，51CTO金牌讲师和专家博主

计算机安全专业硕士，Linux核心专家、Linux运维教父、51CTO专家博主。多年Linux及数据库实战和教学经验，擅长讲授Linux运维、企业级运维自动化、系统架构和优化、hadoop海量数据、大并发架构设计、IaaS云技术等实战。马哥Linux、Python系列培训视频一直被网友们称为业内最专业的IT培训视频，马哥擅长把复杂抽象的大问题化解成具体形象的案例，其授课方式生动形象，幽默风趣。马哥在Linux界跟JAVA界马士兵称之为IT培训界的”马氏双雄”。在业内一直有着”马哥出品必是精品”之说。其教学方法及治学态度深受网友喜欢。直接或间接受教的真实学员数十万人，门徒遍布业内一二线互联网公司，往期学员已在腾讯、大众点评、巨人、盛大、九城、淘宝、滴滴、小米、京东、网易、平安、电信、一号店等知名公司担当要职！


## 我的笔记

### 基本概念

![20191205_150921_95](image/20191205_150921_95.png)

![20191205_150947_76](image/20191205_150947_76.png)

![20191205_151004_92](image/20191205_151004_92.png)

* 镜像是静态的，不会运行。类似于程序
* 容器是动态的，有声明周期。类似于进程

![20191205_151142_28](image/20191205_151142_28.png)

* 镜像可以增删改查，容器可以增删改查

### 安装及使用

* CentOS 6 还是2.6内核，但是依然可以跑docker，是因为红帽打了补丁，不过有问题，不稳定

![20191205_151523_98](image/20191205_151523_98.png)

清华大学开源镜像网站： <https://mirrors.tuna.tsinghua.edu.cn>

![20191205_151849_28](image/20191205_151849_28.png)

docker-ce:配置文件：**/etc/docker/daemon.json**,此配置文件有时候需要手动创建

docker镜像加速：

1. docker cn    
2. 阿里云加速器   
3. 中国科技大学

```
{
  "registry-mirrors": ["https://registry.docker-cn.com"]
}
```


![20191205_152111_99](image/20191205_152111_99.png)

![20191205_152122_45](image/20191205_152122_45.png)

配置好加速器后使用info子命令查看docker环境参数

```
docker info ## 查看当前机器docker相关信息

docker image pull nginx:1.14-alpine

docker image ls  ##列出所有镜像

docker image rm ##删除某个镜像

docker image ls --no-trunc

docker container COMMAND --help

docker run  --name kvstor1 -d redis:4-alpine   ##运行一个redis，先在dockerhub上搜索是否有这个镜像

docker run --name b1 -it buusybox:latest

docker exec -it kvstor1 /bin/sh   ##交互式运行redis

docker search ##搜索镜像

docker pull ##下载到本地

docker image  ##镜像

docker ps -a  ##查看所有容器

docker start -i -a b1  ##启动名为b1的容器，模式为交互式

docker container ls 或 docker ps ##查看当前正在运行的容器
```

![20191205_152612_81](image/20191205_152612_81.png)

## docker镜像和容器操作

![20191205_152706_29](image/20191205_152706_29.png)

分清容器和镜像，容器是动态，镜像是静态，容器是运行的镜像，镜像就是死的文件

![20191205_154314_41](image/20191205_154314_41.png)

![20191205_154326_40](image/20191205_154326_40.png)

* 每个镜像都有默认自定义运行的程序（也可以指定，也可以改）


## 运行容器相关操作

```
root@vm:~# docker run --help

Usage:	docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

Run a command in a new container

Options:
      --add-host list                  Add a custom host-to-IP mapping (host:ip)
  -a, --attach list                    Attach to STDIN, STDOUT or STDERR
      --blkio-weight uint16            Block IO (relative weight), between 10 and 1000, or 0 to disable (default 0)
      --blkio-weight-device list       Block IO weight (relative device weight) (default [])
      --cap-add list                   Add Linux capabilities
      --cap-drop list                  Drop Linux capabilities
      --cgroup-parent string           Optional parent cgroup for the container
      --cidfile string                 Write the container ID to the file
      --cpu-period int                 Limit CPU CFS (Completely Fair Scheduler) period
      --cpu-quota int                  Limit CPU CFS (Completely Fair Scheduler) quota
      --cpu-rt-period int              Limit CPU real-time period in microseconds
      --cpu-rt-runtime int             Limit CPU real-time runtime in microseconds
  -c, --cpu-shares int                 CPU shares (relative weight)
      --cpus decimal                   Number of CPUs
      --cpuset-cpus string             CPUs in which to allow execution (0-3, 0,1)
      --cpuset-mems string             MEMs in which to allow execution (0-3, 0,1)
  -d, --detach                         Run container in background and print container ID
      --detach-keys string             Override the key sequence for detaching a container
      --device list                    Add a host device to the container
      --device-cgroup-rule list        Add a rule to the cgroup allowed devices list
      --device-read-bps list           Limit read rate (bytes per second) from a device (default [])
      --device-read-iops list          Limit read rate (IO per second) from a device (default [])
      --device-write-bps list          Limit write rate (bytes per second) to a device (default [])
      --device-write-iops list         Limit write rate (IO per second) to a device (default [])
      --disable-content-trust          Skip image verification (default true)
      --dns list                       Set custom DNS servers
      --dns-option list                Set DNS options
      --dns-search list                Set custom DNS search domains
      --domainname string              Container NIS domain name
      --entrypoint string              Overwrite the default ENTRYPOINT of the image
  -e, --env list                       Set environment variables
      --env-file list                  Read in a file of environment variables
      --expose list                    Expose a port or a range of ports
      --gpus gpu-request               GPU devices to add to the container ('all' to pass all GPUs)
      --group-add list                 Add additional groups to join
      --health-cmd string              Command to run to check health
      --health-interval duration       Time between running the check (ms|s|m|h) (default 0s)
      --health-retries int             Consecutive failures needed to report unhealthy
      --health-start-period duration   Start period for the container to initialize before starting health-retries countdown (ms|s|m|h) (default 0s)
      --health-timeout duration        Maximum time to allow one check to run (ms|s|m|h) (default 0s)
      --help                           Print usage
  -h, --hostname string                Container host name
      --init                           Run an init inside the container that forwards signals and reaps processes
  -i, --interactive                    Keep STDIN open even if not attached
      --ip string                      IPv4 address (e.g., 172.30.100.104)
      --ip6 string                     IPv6 address (e.g., 2001:db8::33)
      --ipc string                     IPC mode to use
      --isolation string               Container isolation technology
      --kernel-memory bytes            Kernel memory limit
  -l, --label list                     Set meta data on a container
      --label-file list                Read in a line delimited file of labels
      --link list                      Add link to another container
      --link-local-ip list             Container IPv4/IPv6 link-local addresses
      --log-driver string              Logging driver for the container
      --log-opt list                   Log driver options
      --mac-address string             Container MAC address (e.g., 92:d0:c6:0a:29:33)
  -m, --memory bytes                   Memory limit
      --memory-reservation bytes       Memory soft limit
      --memory-swap bytes              Swap limit equal to memory plus swap: '-1' to enable unlimited swap
      --memory-swappiness int          Tune container memory swappiness (0 to 100) (default -1)
      --mount mount                    Attach a filesystem mount to the container
      --name string                    Assign a name to the container
      --network network                Connect a container to a network
      --network-alias list             Add network-scoped alias for the container
      --no-healthcheck                 Disable any container-specified HEALTHCHECK
      --oom-kill-disable               Disable OOM Killer
      --oom-score-adj int              Tune host's OOM preferences (-1000 to 1000)
      --pid string                     PID namespace to use
      --pids-limit int                 Tune container pids limit (set -1 for unlimited)
      --privileged                     Give extended privileges to this container
  -p, --publish list                   Publish a container's port(s) to the host
  -P, --publish-all                    Publish all exposed ports to random ports
      --read-only                      Mount the container's root filesystem as read only
      --restart string                 Restart policy to apply when a container exits (default "no")
      --rm                             Automatically remove the container when it exits
      --runtime string                 Runtime to use for this container
      --security-opt list              Security Options
      --shm-size bytes                 Size of /dev/shm
      --sig-proxy                      Proxy received signals to the process (default true)
      --stop-signal string             Signal to stop a container (default "SIGTERM")
      --stop-timeout int               Timeout (in seconds) to stop a container
      --storage-opt list               Storage driver options for the container
      --sysctl map                     Sysctl options (default map[])
      --tmpfs list                     Mount a tmpfs directory
  -t, --tty                            Allocate a pseudo-TTY
      --ulimit ulimit                  Ulimit options (default [])
  -u, --user string                    Username or UID (format: <name|uid>[:<group|gid>])
      --userns string                  User namespace to use
      --uts string                     UTS namespace to use
  -v, --volume list                    Bind mount a volume
      --volume-driver string           Optional volume driver for the container
      --volumes-from list              Mount volumes from the specified container(s)
  -w, --workdir string                 Working directory inside the container

```

已经停止的容器激活

![20191205_155406_64](image/20191205_155406_64.png)

支撑容器的骨架进程不可在后台运行

![20191205_161058_27](image/20191205_161058_27.png)

![20191205_161415_67](image/20191205_161415_67.png)

* 只有在最上层可写，删除容器，容器最上层的可写层也会被删除

![20191205_161607_19](image/20191205_161607_19.png)

* 依赖于专用的文件系统，高级多层统一文件系统 最早被docker用于联合挂载的文件系统
* UnionFS、aufs据说代码很烂，被拒绝申请融入内核，因此不是内核所拥有支持的文件系统。若要使用，独立打补丁

![20191205_162012_57](image/20191205_162012_57.png)

* DM（devicemapper）性能较差

![20191205_162210_91](image/20191205_162210_91.png)

* 镜像存储位置。本地镜像不存在的时候去Registry网络获取镜像存储到本地。
* 默认就是docker hub的镜像

![20191205_162400_96](image/20191205_162400_96.png)

### docker Registry分类

![20191205_162513_89](image/20191205_162513_89.png)

* 互联网大部分镜像用不了，因为不满足需求，一般都是二次定制镜像

![20191205_162640_48](image/20191205_162640_48.png)

![20191205_162901_50](image/20191205_162901_50.png)

* 镜像开发人员制作后推送到开放的公共仓库，其他人员通过开放仓库下载到本地
* 云原生：面向云计算而诞生的应用，专门运行在容器中，适配容器。云原生的配置是通过环境变量注入，而nginx基于配置文件，所以算不上云原生

![20191205_163601_54](image/20191205_163601_54.png)

* docker就是一个非常庞大的存储仓库

![20191205_163646_78](image/20191205_163646_78.png)

* 联动构建docker镜像：在github上创建项目，存放dockerfile，该仓库与docker hub仓库关联并持续监听，一旦更新，自动创建镜像。就跟gitbook一模一样的套路
* webhooks是自动构建的一个特征，推送dockerfile到站点，触发webhooks，启动自动构建
* automated builds和webhooks是一回事，相互关联

## 获取镜像

```
docker pull <registry>[:<port>]/[<namespace>/]<name>:<tag>
```

![20191205_164249_24](image/20191205_164249_24.png)

* 常用站点：
  - <https://quay.io>


```
docker pull quay.io/coreos/flannel
docker pull quay.io/coreos/flannel:
```

* 不加标签默认就是latest，指定标签加冒号
* 默认端口都是443
* 除非是docker hub的镜像，否则都要加前缀域名
* namespace可以是组织，个人或者角色


## docker镜像制作

![20191205_164946_94](image/20191205_164946_94.png)

1. 使用dockerfile结合build命令制作
2. 二次开发，基于容器制作，相当于增加一层（把可写层叠加进镜像成为新镜像），可写层做成镜像

![20191205_165500_33](image/20191205_165500_33.png)

```
docker commit -a "MageEdu <mage@magedu.com>" -c 'CMD ["/bin/httpd","-f","-h","/data/html"]' -p b1 mageedu/httpd:v0.2
```

![20191205_170808_37](image/20191205_170808_37.png)

![20191205_170818_62](image/20191205_170818_62.png)

* 二次开发很方便，如何推送到docker hub？

![20191205_170925_67](image/20191205_170925_67.png)

![20191205_170929_33](image/20191205_170929_33.png)

```
docker login -p PASSWD -u USER    hub.docker.com
docker image push mageedu/httpd
```

![20191205_171056_36](image/20191205_171056_36.png)

![20191205_171108_87](image/20191205_171108_87.png)

* 同理，阿里云镜像仓库也可以推送。国内做的比较好的也就阿里云

![20191205_171320_55](image/20191205_171320_55.png)

![20191205_171505_95](image/20191205_171505_95.png)

### 镜像导入导出

![20191205_171938_59](image/20191205_171938_59.png)

导出：

![20191205_172105_90](image/20191205_172105_90.png)

导出：

![20191205_172318_34](image/20191205_172318_34.png)















## 相关笔记

* <https://blog.csdn.net/weixin_30549175/article/details/99901855>
