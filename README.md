<p align="center">
  <img title="portainer" src='https://github.com/bigbugcc/portainer/blob/main/app/assets/images/portainer-github-banner.png?raw=true' />
</p>

## Portainer-ce 中文汉化

汉化版本基于[官方](https://github.com/portainer/portainer)`v2.13.1`持续更新中 🎈，官方版本迭代较快顾选择一个稳定的版本进行汉化跟进，后续版本将会在上游大版本更新完稳定下来后进行同步。若有汉化不标准还请提交`issue`告知，或直接提交`PR`。

## Docker

🐬[dockerhub 中查看](https://hub.docker.com/r/bigbugcc/portainer-ce)

🍕[官方文档](https://docs.portainer.io/)

```shell
docker run -itd -p 9000:9000 --name portainer \
  --restart=always \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /root/portainer/:/data \
  bigbugcc/portainer-ce
```

## PR 说明

提交 PR 需在分支`v2.13.1`进行，主分支不接受直接提交。

## 预览

<p align="center">
  <img title="portainer" src='https://github.com/bigbugcc/portainer/blob/main/app/assets/images/portainer-zh-1.png?raw=true' />
</p>

## Demo

自行容器测试。
