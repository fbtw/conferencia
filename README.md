### Starting the application

Start the application using Node:

```bash
# Install dependencies for server
npm install

# Run the server
node server
```

Start the application using Docker:

```bash
# Building the image
docker build --tag webrtcvideobroadcast .

# Run the image in a container
docker run -d -p 4000:4000 webrtcvideobroadcast
```

### Testing the application

The application should now be running on your localhost:4000 and you test it by connecting to localhost:4000/broadcast.html to add a new broadcaster.

After that, you just need to visit localhost:4000 to connect to the server as a client and you should get the video that is streamed from the broadcaster.
