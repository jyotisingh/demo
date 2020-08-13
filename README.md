# demo

## Build: 

```
$ docker build . --tag basic-image-with-nginx:latest
```

## Run: 
```
docker run -p 9000:80 -d basic-image-with-nginx:latest
```

Access `http://localhost:9000` from browser.