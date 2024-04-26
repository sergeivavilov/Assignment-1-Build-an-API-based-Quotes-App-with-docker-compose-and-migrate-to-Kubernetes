FROM alpine
RUN apk upgrade
RUN apk add mysql-client
COPY . /opt
WORKDIR /opt
RUN chmod +x import.sh
ENTRYPOINT ["./import.sh"]


