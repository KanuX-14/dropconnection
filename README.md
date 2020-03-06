# dropconnection
Shell script to identify and block DoS/DDoS attacks.

Need to have permission to run! For it use:
```shell
$: chmod +x dropconnection
```

Usage:

-i: get information from the connection of your computer.
-b: ban the IP.
-u: unban the IP.
-s show: show the banned IPs.
-v show: show version of the script and the developer.

Example:

```shell
$: ./dropconnection (option) [ARG]
```
or
```shell
$: mv /path/to/dropconnection /usr/local/bin/dropconnection
$: dropconnection (option) [ARG]
```
or
```shell
#: mv /path/to/dropconnection /bin/dropconnection
#: dropconnection (option) [ARG]
```

ATENTION: Some distributions don't need be logged as ROOT to run the commands, but most recently ones does!
It's recommended to you run this script as ROOT if your distribution don't recognize [ifconfig](https://packages.debian.org/search?keywords=net-tools) or/and [iptables](https://packages.debian.org/search?keywords=iptables)!
