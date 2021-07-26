FROM alpine:3.14

# 重置 源文件
RUN echo https://dl-cdn.alpinelinux.org/alpine/v3.13/main > /etc/apk/repositories && \
    echo http://mirrors.aliyun.com/alpine/v3.7/main/ >> /etc/apk/repositories && \
    echo https://mirrors.ustc.edu.cn/alpine/v3.6/main/ >> /etc/apk/repositories && \
    echo https://mirrors.tuna.tsinghua.edu.cn/alpine/v3.6/main/ >> /etc/apk/repositories && \
    echo https://dl-cdn.alpinelinux.org/alpine/v3.13/community >> /etc/apk/repositories && \
    echo http://mirrors.aliyun.com/alpine/v3.7/community/ >> /etc/apk/repositories && \
    echo https://mirrors.ustc.edu.cn/alpine/v3.6/community/ >> /etc/apk/repositories && \
    echo https://mirrors.tuna.tsinghua.edu.cn/alpine/v3.6/community/ >> /etc/apk/repositories
