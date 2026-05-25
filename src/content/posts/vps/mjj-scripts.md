---
title: 'MJJ相关脚本'
published: 2026-05-10
category: VPS
tags: ["vps", "mjj", "脚本"]
---

## NodeQuality

```shell
bash <(curl -sL https://run.NodeQuality.com)
```

## 融合怪

```shell
curl -L https://gitlab.com/spiritysdx/za/-/raw/main/ecs.sh -o ecs.sh && chmod +x ecs.sh && bash ecs.sh
```

## 融合怪 GO 版本

```shell
export noninteractive=true && curl -L https://bash.spiritlhl.net/goecs -o goecs.sh && chmod +x goecs.sh && bash goecs.sh install && goecs -l=en
```

## 线路测试

```shell
wget -qO- besttrace.sh | bash
```

## speed test

```shell
## If migrating from prior bintray install instructions please first...
# sudo rm /etc/apt/sources.list.d/speedtest.list
# sudo apt-get update
# sudo apt-get remove speedtest
## Other non-official binaries will conflict with Speedtest CLI
# Example how to remove using apt-get
# sudo apt-get remove speedtest-cli
sudo apt-get install curl
curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash
sudo apt-get install speedtest
```
