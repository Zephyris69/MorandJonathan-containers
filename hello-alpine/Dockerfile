FROM alpine:3.15.0
LABEL distro="3.15.0" maintainer="Jonathan Morand" os="alpine"
ENV CONTAINER_USER="Morand"
RUN adduser $CONTAINER_USER --disabled-password && mkdir "/home/morand/receipts"
CMD echo "hello-alpine, I’m Jonathan Morand and this is a container from my first image"
