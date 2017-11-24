# python-example
Sample dockerized Python application

### Build

```bash
docker build -t your-repo/name-of-image:tag .
```

### Deploy
```bash
docker run --name python-example -p 8081:8888 <image_name>
```
