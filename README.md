# is436docker

#
docker build -t is436-docker .
docker ps -a
docker image ls
docker container run --name  is436container -d -p 1234:80 is436-docker
docker login
shivathebravo/is436-docker
docker image
# push docker image
docker tag is436-docker shivathebravo/is436-docker

#pull docker image

docker pull shivathebravo/is436-docker

docker run -p 8081:80 shivathebravo/is436-docker