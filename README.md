```
for i in {0..9}; do docker run --name oooo$i --log-driver=syslog --log-opt syslog-address=tcp://<hostname>.amazonaws.com:5514 -P -d redis; done
```
