FROM redis:7.2-rc2-alpine3.18
#Adding risk acceptance
RUN apk update && apk upgrade
RUN apk add --no-cache \
  libcrypto3=3.1.1-r0 \
  libssl3=3.1.1-r0 
CMD [ "redis-server" ]
