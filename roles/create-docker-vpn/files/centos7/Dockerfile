FROM        centos:7

RUN         yum install -y epel-release openssh-server openvpn

COPY        entrypoint.sh /sbin/entrypoint.sh
RUN         chmod 755 /sbin/entrypoint.sh

ENTRYPOINT  ["/sbin/entrypoint.sh"]
