# start by pulling in the node image
FROM node

# setting the working directory of the container
WORKDIR /app

# copy all the code in the current directory (first .) to the /app folder in the container
COPY . /app

# install npm and dependencies in the image
RUN npm install

# expose port 8080 to the host (optional)
EXPOSE 80

# execute this command after a container is started from the image
CMD ["node", "server.js"]