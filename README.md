# docker-example
Example Docker project using NGINX &amp; Ubuntu

# Start here 
- To use a GUI, install the [docker linux vm-ish](https://docs.docker.com/v1.8/installation/mac/)
- To run Docker without a GUI, follow [these instructions](https://hackinggate.com/helloworld-docker-on-osx-without-boot2docker/) which use [Homebrew](http://brew.sh/)

# After installing use the "Docker Quickstart Terminal" this will open a terminal
 - make a dir (mkdir mydockerexample)
 - pull this repo into that directory (git clone git@github.com:Morsekode/docker-example.git . )
 
# Now do these things :) (from inside your directory)
- docker build -t docker-test-nginx . (note the period)
- docker run  -p 80:80 -i -t docker-test-nginx

If all works out navigating to http://192.168.99.100/ should work
