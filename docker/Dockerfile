FROM alpine:3.18.3

COPY restic /usr/bin

RUN apk add --update --no-cache ca-certificates fuse openssh-client tzdata

ENTRYPOINT ["/usr/bin/restic"]
