# Build a Docker Image for NodeJS App
## How to run
- `docker build .`  
- `docker run -p 3000:80 <image_id>`   
- Visit `localhost:3000` to see the application
- To stop: `docker stop <container_name>`

## Quick side note
For all docker commands where an ID can be used, you don't always have to copy / write out the full id. You can also just use the first (few) character(s) - just enough to have a unique identifier.

So instead of
`docker run abcdefg`, you could also run `docker run abc` or, if there's no other image ID starting with "a", you could even run just: `docker run a`.
This applies to ALL Docker commands where IDs are needed.