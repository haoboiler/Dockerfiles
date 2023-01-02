# Dockerfile for cpp in Linux platform

## In windows docker
`docker pull centos/systemd`

`docker build -f .\DockerfileCentosC++ -t centos/cpp:0.1 .`

`docker run -d -p 10022:22 --privileged centos/cpp:0.1 /usr/sbin/init`

In docker

`systemctl start sshd`
`passwd {passwd}`