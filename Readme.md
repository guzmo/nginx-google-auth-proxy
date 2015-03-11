# Docker container with Nginx and google auth proxy. #

Start by download a zip file from https://github.com/bitly/google_auth_proxy/releases. 

It should be *google auth proxy-1.0.linux-amd64.go1.3.tar.gz*

Put this tar.gz file in the same folder as the Dockerfile (Root folder of this repo)

**Build:**

    docker build .

**Run:**

    docker run -p 4180:4180 "IdOnContainer"
