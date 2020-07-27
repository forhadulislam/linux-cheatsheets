## Docker commands


    docker ps
    
    To remove a container
    
    docker rm b69147df3fe5efb
  
  
### Docker Volume

    docker run --rm -v ${PWD}:/myvol ubuntu /bin/bash -c "ls -la > /myvol/file.txt"
  
  
### Logs

  If you have a docker container and id of the container is b69147df3fe5efb. Then you can see the logs of the container by using -
  
    docker logs b69147df3fe5efb
  
  To follow the logs -
  
    docker logs b69147df3fe5efb -f
    
    
  To inspect -
  
    docker inspect b69147df3fe5efb
