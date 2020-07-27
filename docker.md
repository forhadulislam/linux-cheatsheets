## Docker commands


  `docker ps`
  
  
### Docker Volume

  `docker run --rm -v ${PWD}:/myvol ubuntu /bin/bash -c "ls -la > /myvol/file.txt"`
  
  
### Logs

  If you have a docker container and id of the container is b69147df3fe5efb. Then you can see the logs of the container by using -
  
    `docker logs b69147df3fe5efb` 
