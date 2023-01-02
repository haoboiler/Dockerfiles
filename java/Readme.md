# Dockerfile for java in centos platform

## In windows docker

`docker build -f .\DockerfileCentosJava18 -t centos/java:0.1 .`

`docker run -d -p 10122:22 --privileged centos/java:0.1 /usr/sbin/init`

In docker

`systemctl start sshd`
`passwd {passwd}`
