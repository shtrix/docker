# docker-debian-lamp

**Pull image**

```
docker pull kahatie/debian-lamp
```

**Run container**

```
docker run -d  --name=<container name> -v <path for files>:/home -v /etc/localtime:/etc/localtime:ro -p 8080:80 -p 8443:443 kahatie/debian-lamp
```

Please replace all user variables in the above command defined by <> with the correct values.


```
docker logs <container name>
```
