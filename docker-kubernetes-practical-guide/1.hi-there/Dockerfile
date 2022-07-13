# use Node.js as a base image
FROM node:14

# directory in the container file system
# where we are going to work
WORKDIR /app

# copy the file into our working directory
COPY package.json .

# install all dependencies
RUN npm install

# copy the rest of the code here
COPY . .

# expose port 3000 to the outside world
EXPOSE 3000

# execute app.mjs with the node command
CMD [ "node", "app.mjs" ]