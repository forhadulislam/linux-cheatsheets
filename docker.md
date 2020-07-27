## Docker commands


  `docker ps`
  
  
### Docker Volume

  `docker run --rm -v ${PWD}:/myvol ubuntu /bin/bash -c "ls -la > /myvol/file.txt"`
