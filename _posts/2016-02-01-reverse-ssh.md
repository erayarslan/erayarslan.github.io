---
layout: post
title: reverse ssh
---

## requirements
1. Server. (EXAMPLE IP: xxx.xxx.xxx.xxx)
2. SSH Server installable device. (Mobile Phone, Raspberry Pi, PC ...) (IP: localhost)

## steps

### device
1. Start SSH Server. (EXAMPLE PORT: 22)
2. Open Terminal and follow this command.

```sh
# Choose Random Free PORT (EXAMPLE PORT: 3000)
$ ssh -N -R xxx.xxx.xxx.xxx:3000:localhost:22 xxx.xxx.xxx.xxx
```

### outside world
1. Connect with SSH.

```sh
# like this
$ ssh -p 3000 xxx.xxx.xxx.xxx
```

## the end
broke the 3g chains!
