# Deploying the first web app
## Steps
1. Run `docker build .` which will produce an image with an ID.
2. Then run `docker run -p 3000:3000 <image ID>`.  
`-p 3000:3000` flag performs an operation knows as port mapping. The container, as well as our local machine, has its own set of ports. In order to access the port 3000 within the container, we need to map it to a port on our local computer (in this case it is port 3000).
3. Open web browser and go to `localhost:3000` to see if the app is running (it will print `Hi there!`).