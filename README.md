## Blogchain Apps Docker Compose

### Build images 

#### Server

- [x] `$ docker build -t qwx1337/blogchain-server .`
- [x] `$ docker push qwx1337/blogchain-server`
- [x] see in `https://hub.docker.com/r/qwx1337/blogchain-server`

#### Client

- [x] `$ docker build -t qwx1337/blogchain-client .`
- [x] `$ docker push qwx1337/blogchain-client`
- [x] see in `https://hub.docker.com/r/qwx1337/blogchain-client`

### Up

- [x] Rename `.env.example` to `.env`
- [x] `$ docker-compose up -d`

**Output**

```shell script
msi blogchain-compose # docker ps -a
CONTAINER ID        IMAGE                      COMMAND                  CREATED             STATUS              PORTS                    NAMES
f4d897bffa66        qwx1337/blogchain-client   "docker-entrypoint.s…"   27 seconds ago      Up 25 seconds       0.0.0.0:3000->3000/tcp   blogchain-compose_client_1
39230f3d061d        qwx1337/blogchain-server   "/app/main --host 0.…"   27 seconds ago      Up 26 seconds       0.0.0.0:3001->3001/tcp   blogchain-compose_server_1
```