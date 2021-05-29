# alpine docker image

![buildx](https://github.com/ryjer/docker-alpine/workflows/buildx-latest/badge.svg)
![buildx](https://github.com/ryjer/docker-alpine/workflows/buildx-3.13/badge.svg)
[![Docker Stars](https://img.shields.io/docker/stars/ryjer/alpine.svg)](https://hub.docker.com/r/ryjer/alpine/)
[![Docker Pulls](https://img.shields.io/docker/pulls/ryjer/alpine.svg)](https://hub.docker.com/r/ryjer/alpine/)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

配置了国内镜像源的 alpine 镜像，以便于在国内使用。
---
会每月进行更新，以追随最新的 alpine 镜像。
配置了以下镜像源地址，使得源配置文件中同时拥有 alpine官方源和以下三个源（共4个源）
- 阿里云镜像：
```bash
https://mirrors.aliyun.com/alpine/v3.6/main/
https://mirrors.aliyun.com/alpine/v3.6/community/
```
- 中科大镜像：
```bash
https://mirrors.ustc.edu.cn/alpine/v3.6/main/
https://mirrors.ustc.edu.cn/alpine/v3.6/community/
```
- 清华镜像：
```bash
https://mirrors.tuna.tsinghua.edu.cn/alpine/v3.6/main/
https://mirrors.tuna.tsinghua.edu.cn/alpine/v3.6/community/
```
