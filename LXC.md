# LXC

## multiple operations

### all container

* lxc list -c n --format=csv | while read line; do lxc stop $line; done
