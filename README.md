# docker-example
Example Docker project using NGINX &amp; Ubuntu

# Start here on OSX to install the docker linux vm-ish
https://docs.docker.com/v1.8/installation/mac/

# After installing use the "Docker Quickstart Terminal" this will open a terminal
 - make a dir (mkdir mydockerexample)
 - pull this repo into that directory (git clone git@github.com:Morsekode/docker-example.git . )
 
# Now do these things :) (from inside your directory)
- docker build -t docker-test-nginx . (note the period)
- docker run  -p 80:80 -i -t docker-test-nginx

If all works out navigating to http://192.168.99.100/ should work
