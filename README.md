# Ziti Package Feed
Ziti package feed for OpenWRT

## Usage
To use these packages, add the following line to the `feeds.conf` in the OpenWrt buildroot:

```
src-git zt https://github.com/hanzozt/zt-openwrt.git
```

To install all its package definitions, run:

```
./scripts/feeds update zt
./scripts/feeds install -a -p zt
```
The Ziti packages should now appear in menuconfig.

## Provided Packages
_TODO_
