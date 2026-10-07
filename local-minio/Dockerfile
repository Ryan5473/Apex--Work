FROM alpine:latest
RUN apk add --no-cache minio
ENTRYPOINT ["minio"]
CMD ["server", "/data", "--console-address", ":9001"]
