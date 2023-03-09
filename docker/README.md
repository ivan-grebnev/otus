Build
-----
```
docker build --platform linux/amd64 -t 9grebnev/otus:docker-latest .
```
Run
---
```
docker run -p 8000:80 9grebnev/otus:docker-latest
```

Push registry
-------------
```
docker push 9grebnev/otus:docker-latest
```