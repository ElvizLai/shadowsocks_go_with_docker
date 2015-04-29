# ShadowShocksServer 
# 
# VERSION 0.0.1 
FROM centos:centos7
ADD ./ss/server /
ADD ./ss/status.html /
ADD ./ss/static /static
EXPOSE 9000 9001/tcp 9001/udp 9002/tcp 9002/udp 9003/tcp 9003/udp 9004/tcp 9004/udp
RUN cp /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime