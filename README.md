# ocs

https://github.com/sigscale/ocs-k8s

install OCS:
```bash
helm upgrade -i ocs .
```

k8s.shubhamtatvamasi.com:30080
k8s.shubhamtatvamasi.com:30068
k8s.shubhamtatvamasi.com:30012
k8s.shubhamtatvamasi.com:30013

---
### Docker

```bash
docker pull sigscale/ocs
docker run --rm -it --entrypoint bash -h host1 -v db:/home/otp/db sigscale/ocs bin/initialize
```

```bash
docker run -d -h host1 -v db:/home/otp/db -p 8080:8080/tcp -p 1812:1812/udp -p 1813:1813/udp -p 3868:3868/tcp sigscale/ocs
```

Source: https://raw.githubusercontent.com/sigscale/ocs/master/README.docker
