FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd ipython && \
    ipython install awscli
RUN apk --purge -v del ipython
CMD tail -f /dev/null
