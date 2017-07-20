FROM        centos:7

RUN         yum install -y epel-release openvpn

COPY        entrypoint.sh /sbin/entrypoint.sh
RUN         chmod 755 /sbin/entrypoint.sh

ENTRYPOINT  ["/sbin/entrypoint.sh"]
