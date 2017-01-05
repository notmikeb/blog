---
title: linux_syslog
date: 2017-01-05 23:04:46
tags:
---

### clean
Clean the syslog file content
```sh
sudo dd if=/dev/null of=/var/log/syslog
```
### test
Use logger to write syslog
```sh
logger -t XYZ this_is_message_xyz
```
### api
man syslog could find the usage of syslog api
