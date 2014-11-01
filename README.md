Usage
=====

```shell
docker run --rm -p 8000:80 -v /var/www:/html softinnov/mininginx:latest
```

**8000** the port on the local host (binded to 80 which is nginx internal container port)

**/var/html** your local folder to your html pages (binded to /html which is nginx default internal container location)softinnov/mininginx:latest
