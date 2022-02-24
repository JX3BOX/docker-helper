# Jbdock

> PHP docker开发环境

## 快速开始

> init

```shell
./jbdock.sh init
```

> docker-compose up -d

```shell
./jbdock.sh d u 
```

> 代码仓库 初始化

```shell
./jbdock.sh get <.git> <newDirName> 
```

会执行以下操作

克隆仓库`git clone <git>`，

执行`composer install`

生成nginx模版

重启nginx

# docker 安装

> linux

> macos

> windows

## next

1. 启动脚本完善
2. 生成模版文件
3. 支持多环境
