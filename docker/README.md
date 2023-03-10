Build
-----
```
docker build --platform linux/amd64 -t 9grebnev/otus-docker:1 .
```
Run
---
```
docker run -p 8000:8000 9grebnev/otus-docker:1
```

Push registry
-------------
```
docker push 9grebnev/otus-docker:1
```