#use NGINX as base image
FROM nginx

# goes to the app directory (like a cd terminal command)
WORKDIR /the/workdir/path

# copy packages
COPY source dest

# install app dependencies
RUN command

# copy the rest of the app into the container
COPY . .

# set port environment variable
ENV PORT=80
# expose the port so out computer can access it
EXPOSE 9000

CMD [ "executable" ]

# build an image: docker build -t name . (path to the Dockerfile)
# running the container: docker run -p (port forwarding) 80:80 name