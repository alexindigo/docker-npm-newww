# docker-npm-newww
Containerized npmjs.org for local deployment

Containerized [npmjs.org](https://github.com/npm/newww) for local deployment,
using redis, elasticsearch, node `0.10.37` and couchdb `1.6.0`.

Requires:
- [couchdb](https://registry.hub.docker.com/u/alexindigo/couchdb/) as linked container.
- [elasticsearch](https://registry.hub.docker.com/_/elasticsearch/) as linked container.
- [redis](https://registry.hub.docker.com/_/redis/) as linked container.

## Run

```
$ ./autostart
```
