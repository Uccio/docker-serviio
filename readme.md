## RUN ##
 docker run -d --net host --privileged  -p 23423:23423/tcp -p 23424:23424/tcp -p 8895:8895/tcp -p 1900:1900/udp -v /media:/medialib -v /var/serviio/library:/opt/serviio/library -v /var/log/serviio:/opt/serviio/log serviio
