`docker pull redis`
`docker run --restart=always --log-opt max-size=100m --log-opt max-file=2 -p 6379:6379 --name redistest -v //E/database/redisdata:/data -d redis`
