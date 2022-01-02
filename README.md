# Docker tftp container

Originally from drerik, https://github.com/drerik


## Run
To start a tftp container with the current dir as share like this:
 
```
docker run -it --rm -p 69:69 -v $(pwd):/var/lib/tftpboot --name tftpd tftpd
```
