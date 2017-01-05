---
title: start_stop_daemon
date: 2017-01-05 23:08:29
tags:
  - linux
---

init.d script usually use start-stop-daemon to control the service enable and disable
```sh
ls /etc/init.d
service --status-all
```

systemd is a high-level management and its tool name is systemctl
the package name is 'systemd'
```
ls /etc/systemd/system
```

[start-stop-daemon](http://stackoverflow.com/questions/8251933/how-can-i-log-the-stdout-of-a-process-started-by-start-stop-daemon)
normally start-stop-daemon is used to control a executable file and not control its descendant processes
there are some solution to control the standout and redirect it to syslog
,like /usr/bin/daemon or pipexec


