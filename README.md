# kubernetes-demo

kubernetes-demo

# start master

docker-compose up master

# start slave

docker-compose scale slave=4

# start full tests

docker-compose scale master=1 slave=4

# status

docker-compose ps

#logs
docker-compose logs --follow

docker container prune -f
