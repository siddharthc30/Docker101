# Use an existing docker image as base 
FROM alpine

# Download and Install Dependencies
RUN apk add --update redis

# Tell the image what to do when it starts to run as a container
CMD ["redis-server"]