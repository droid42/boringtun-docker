# Wireguard / Boringtun in Docker

Wireguard but userspace and in containers and kubernetes-compatible.

## Building

```bash
git submodule init
git submodule update
```

update to latest boringtun
```bash
cd boringtun
git pull origin master
cd ..
```

build
```bash
docker build -t boringtun:latest .
```

## Getting Started

Check out the /k8s directory for kubernetes examples

Check out the /docker-compose directory for docker-compose example

## Contributing

Just submit PRs.

## Versioning

I tagged the docker container with the matching commit hash prefix from Boringtun hyphen revision... Keep that up

## Authors

* [FrankPetrilli](https://github.com/FrankPetrilli)

## License

* See [LICENSE.md](LICENSE.md)

## Acknowledgments

* Boringtun from Cloudflare

