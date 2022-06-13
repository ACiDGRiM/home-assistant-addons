FROM zabbix/zabbix-agent2:latest

ARG BUILD_ARCH
ARG BUILD_VERSION

LABEL maintainer "ACiDGRiM"

ENV LANG C.UTF-8

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
