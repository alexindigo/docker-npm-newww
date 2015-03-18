# docker-npm-newww
Containerized npmjs.org for local deployment

Containerized [npmjs.org](https://github.com/alexindigo/newww) for local deployment,
using redis, elasticsearch, node `0.10.37` and private_npm `2.4.3`.

Requires:
- [alexindigo/private-npm](https://registry.hub.docker.com/u/alexindigo/private-npm/) as linked container.
- [elasticsearch](https://registry.hub.docker.com/_/elasticsearch/) as linked container.
- [redis](https://registry.hub.docker.com/_/redis/) as linked container.

## Run

```
$ ./autostart
```
