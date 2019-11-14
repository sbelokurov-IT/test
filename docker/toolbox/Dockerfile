FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip3 && \
    pip3 install awscli
RUN apk --purge -v del py-pip3
CMD tail -f /dev/null
