FROM alpine:latest
RUN apk --no-cache add dhcp-helper
EXPOSE 67 67/udp
ENTRYPOINT ["dhcp-helper", "-n"]
#ENTRYPOINT ["tail", "-f", "/dev/null"]
