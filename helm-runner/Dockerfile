FROM alpine

RUN apk update \
	&& apk add --no-cache --repository=http://dl-cdn.alpinelinux.org/alpine/edge/testing/ \
		helm \
		git \
	&& rm -rf /var/cache/apk/*

RUN helm plugin install https://github.com/chartmuseum/helm-push

CMD ["sh"]
