# use an existing dokcer image as base
FROM alpine




# download and install a dependency 
RUN apk add --update redis


# Tell the image what to do when it starts as a container  
CMD [ "redis-server" ]