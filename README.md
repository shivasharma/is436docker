# is436docker

#
docker build -t is436-docker .
docker ps -a
docker image ls
docker container run --name  is436container -d -p 1234:80 is436-docker

