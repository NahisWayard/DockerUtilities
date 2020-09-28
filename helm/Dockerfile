FROM alpine

RUN apk add --update coreutils

RUN apk update && apk add --no-cache curl openssl

RUN curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | sh

RUN mkdir –m700 -p $HOME/.kube