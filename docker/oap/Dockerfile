FROM apache/skywalking-oap-server:6.4.0

RUN apk add tzdata
ENV TZ Asia/Taipei
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

WORKDIR /skywalking


EXPOSE 12800 11800 1234

ENTRYPOINT ["bash", "docker-entrypoint.sh"]
