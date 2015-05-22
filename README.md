# lxc-bind

lxc-bind is the template script for [LXC](https://linuxcontainers.org/lxc/).

## Installation

Copy lxc-bind to templates directory. For example:

```
cp lxc-bind /usr/share/lxc/templates
```

## Usage

Specify as the value of '-t' option of lxc-create.

```
lxc-create -t bind -n test -- [-b directory] [command]
```

## Template options

* -b/--bind : the directory or file that you want to bind mount
* command : command that you want to run on a container
