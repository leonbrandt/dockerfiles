FROM docker:dind

RUN apk update \
	&& apk add --no-cache \
		nodejs \
		npm \
	&& rm -rf /var/cache/apk/*

CMD [ "sh" ]
