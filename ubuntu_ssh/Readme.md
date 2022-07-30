# Ubuntu with ssh

`docker build -t ssh_docker .`

`docker run -d -p 54322:22 --privileged ssh_docker /usr/sbin/init`
