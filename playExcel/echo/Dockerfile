FROM alpine

RUN apk add --update bash
RUN adduser -S echo

RUN ln -s /bin/bash /bin/rbash
RUN rm -rf /var/cache/apk/*
RUN rm -rf /bin/dd /bin/mount /bin/mountpoint /bin/pwd /bin/rm /bin/rmdir /bin/uname /bin/sleep /bin/ping

USER echo
