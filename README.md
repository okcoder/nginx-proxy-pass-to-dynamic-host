```
docker run -v `pwd`/conf/default.conf:/etc/nginx/conf.d/default.conf -p 1080:80 nginx
```

```
curl "localhost:1080/proxy/https/1234567a88888bcd/httpbin.org/anything?q1=abcd&q2=aaaaa"
curl "localhost:1080/proxy/http/1234567a88888bcd/httpbin.org/anything?q1=abcd&q2=aaaaa"
```
