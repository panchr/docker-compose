### To RUN:
```bash
You will have to
$ cd docker-container/docker
$ make
$ docker run -p 25:25 -p 80:80 -p 465:465 -p 587:587 -p 110:110 -p 143:143 -p
993:993 -p 995:995 -p 443:443 -p 8080:8080 -p 8443:8443 -p 7071:7071 -p
9071:9071 -h zimbra-tony.lixu.com --dns 127.0.0.1 --dns 8.8.8.8 -i -t -e
PASSWORD=zimbra zimbra_docker
or
$ docker-compose up -d
```

### Zimbra DB
https://www.zimbra.com/docs/os/5.0.19/administration_guide/3_Zimbra%20Servers.4.1.html
https://wiki.zimbra.com/wiki/MySQL_Backup_and_Restore
