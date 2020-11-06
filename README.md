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

- [x] `$ docker-compose up -d`

### Visits

- Grafana: `<host-ip>:3002`
- Prometheus: `<host-ip>:9090`
- AlertManager: `<host-ip>:9093`