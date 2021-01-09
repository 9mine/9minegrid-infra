---
User registry
---

Install:
```bash
$ helm repo add 9mine https://9mine.github.io/charts
$ helm repo update
# install global registry
$ helm upgrade --install registry 9mine/inferno --version 0.4.1 -f registry.yml
# install user registry
$ helm upgrade --install user-registry 9mine/inferno --version 0.4.1 -f user-registry.yml
# install gridfiles
$ helm upgrade --install gridfiles 9mine/inferno --version 0.4.2 -f ./gridfiles.yml
# install manuals
$ helm upgrade --install manuals 9mine/inferno --version 0.4.3 -f ./manuals.yml
# install minetest server with 9mine mod
$ helm upgrade --install minetest 9mine/minetest --version 0.2.1 -f ./minetest.yml
```
