FROM alpine:3.18.3

COPY ./go-admin /
EXPOSE 8000

CMD ["/go-admin","server","-c", "/config/settings.yml"]
