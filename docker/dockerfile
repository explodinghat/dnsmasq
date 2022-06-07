FROM alpine:latest
LABEL maintainer="richjjoh@gmail.com"
RUN apk update
RUN apk --no-cache add dnsmasq
COPY dnsmasq.conf /etc/dnsmasq.conf
EXPOSE 53/udp
CMD ["dnsmasq","-d"]
