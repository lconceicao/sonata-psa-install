FROM        ubuntu:xenial

RUN         apt update \
            && apt install -y openssh-server openvpn

COPY        entrypoint.sh /sbin/entrypoint.sh
RUN         chmod 755 /sbin/entrypoint.sh

ENTRYPOINT  ["/sbin/entrypoint.sh"]
