# start by pulling the node image
FROM node

# setting the working directory of the container
WORKDIR /app

# copy the dependencies required by the app to the /app folder in the container
COPY package.json /app

# install npm and dependencies in the image. 
# put this before COPY . /app to avoid reinstalling npm in an image every time a file is changed
RUN npm install

# copy all the code in the current directory (first .) to the /app folder in the container
COPY . /app

# expose port 8080 to the host (optional)
EXPOSE 80

# execute this command after a container is started from the image
CMD ["node", "server.js"]