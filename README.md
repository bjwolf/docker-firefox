docker-firefox
==============

Firefox over Docker via VNC

docker build --rm -t bjwolf/docker-firefox:v1 .


docker run -it -p 5900 -e HOME=/ bjowlf/docker-firefox x11vnc -forever -usepw -create


