FROM alpine:3.18.4
# 替换成国内的阿里云源
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/' /etc/apk/repositories
# 更新一下源,并安装软件
RUN apk update && apk add curl vim openssh-client busybox-extras drill net-tools
CMD ["/bin/sh"]