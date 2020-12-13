---
User registry
---

Install:
```
$ helm repo add 9mine https://9mine.github.io/charts
$ helm repo update
# install global registry
$ helm upgrade --install registry 9mine/inferno --version 0.4.1 -f registry.yml
# install user registry
$ helm upgrade --install user-registry 9mine/inferno --version 0.4.1 -f user-registry.yml
# install gridfiles
$ helm upgrade --install gridfiles 9mine/inferno --version 0.4.2 -f ./gridfiles.yml
```
