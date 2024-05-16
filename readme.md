### docker commands
```bash
docker system prune
WARNING! This will remove:
  - all stopped containers
  - all networks not used by at least one container
  - all dangling images
  - all dangling build cache

Are you sure you want to continue? [y/N] N
```
```bash
docker ps -a
```
```bash
docker run -d -p 5000:80 nginx
```

```bash
docker exec -it pedantic_mendel bash
```
### docker file build from Dockerfile
```bash
docker build -t youtube-nodejs .
```
### docker image run commands
```bash
docker run -it -p 8000:8000 youtube-nodejs
```
### docker image of ubuntu
- for example
```bash
docker run -it ubuntu
```
### docker images
```bash
docker pull nginx
```
```bash
docker ps
```
```bash
docker run -d -p2000:80 nginx
```
```bash
docker stop 089
```

```bash
docker pull ubuntu
```
```bash
docker pull owncloud
```
