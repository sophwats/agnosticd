# bind9 dns
FROM registry.access.redhat.com/ubi8/ubi-init:8.3 AS bind9

RUN yum install -y bind 

RUN systemctl enable named

EXPOSE 53/udp 53/tcp

CMD [ "/sbin/init" ]
