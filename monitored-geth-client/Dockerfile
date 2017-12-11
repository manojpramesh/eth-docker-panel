FROM ethereum/client-go:v1.6.5

RUN apk update &&\
    apk add git nodejs bash perl

ADD start.sh /root/start.sh
ADD app.json /root/eth-net-intelligence-api/app.json
RUN chmod +x /root/start.sh

ENTRYPOINT /root/start.sh
