
```
wget https://github.com/ginuerzh/gost/releases/download/v2.11.2/gost-linux-amd64-2.11.2.gz

gzip gost-linux-amd64-2.11.2.gz -d

mv gost-linux-amd64-2.11.2 gost && chmod +x gost

nohup ./gost -L=relay+tls://:9998 &

```
