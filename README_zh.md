# peer2profit-一键式命令安装

## 介绍

peer2profit 是一个允许用户通过分享流量来赚钱的平台。(被动收入)

您共享的 1G 流量将获得 0.30 美元，并且此脚本支持数据中心网络或家庭带宽(两倍收益)。

它具有以下特点：

1.根据系统自动安装docker，如果已经安装了docker，则不再安装。

2.根据架构自动选择和构建拉取的docker镜像，无需您手动修改官方案例安装。
    
3.使用Watchtower进行镜像自动更新，无需手动更新和重新输入参数。

(Watchtower 是一款实现自动化更新 Docker 镜像与容器的实用工具.它监控着所有正在运行的容器以及相关镜像,当检测本地镜像与镜像仓库中的镜像有差异时,会自动拉取最新镜像并使用最初部署时的参数重新启动相应的容器.)

### 信息

- 本项目已经在 AMD64 和 ARM 上验证上测试通过
- 感兴趣可以尝试一下，[注册链接点我](https://t.me/peer2profit_app_bot?start=164225539661e2d42426a2f), 走我链接注册你不会损失什么，但我更有动力维护脚本。

## 安装

### 交互式安装

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/peer2profit-one-click-command-installation/main/p.sh -o p.sh && chmod +x p.sh && bash p.sh
```

注册链接注册后，记住你的注册邮箱，运行此命令，粘贴注册邮箱，回车，即可开始安装。

### 一键安装

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/peer2profit-one-click-command-installation/main/p.sh -o p.sh && chmod +x p.sh && bash p.sh -m 你的邮箱
```

在此命令最后修改为你的邮箱再一键运行即可

## 卸载

```shell
bash p.sh -u
```

卸载服务

### 经验

主要看IP是属于何种类型，如果是家庭带宽将收益最高，如果是数据中心将收益最低。

收益比较低，一个IP一个月大概就0.1~0.0.25刀，个人实验38天0.21刀

国外服务器可挂，国内服务器挂了收益较低，但挂住宅网(家庭带宽)收益还是可观的，我上面实验的是服务器的收益。

### 免责声明

本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。

使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.
