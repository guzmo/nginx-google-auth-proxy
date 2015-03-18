# Docker container with Nginx and google auth proxy. #


**Build:**

    docker build .

**Run:**

    docker run -p 4180:4180 "IdOnContainer"
    
You need to ADD an google_auth_proxy.cfg file in /etc in the Docker container somehow.
