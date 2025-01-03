# Initilize Node.js App

This repository contain all the basic requirements to start developing an express.js app.

1. Build dockerfile
   ```bash
   docker build -t node_app_img:latest .
2. Run docker container
   ```bash
   docker run --name init_node_app -p 127.0.0.1:3000:3000 -d node_app_img:latest