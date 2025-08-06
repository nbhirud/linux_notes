

# IP Address

## On new systems, get IP address of the system using the `ip` command: 
```
ip addr
ip -6 addr # for IPv6
```

## On older systems, use `ifconfig` command:
To use it on new systems where it might not be pre-installed, install `net-tools`
```
# sudo dnf install -y net-tools
ipconfig
```

## General notes:
* Look for `inet` in the output of most of these commands for IPv4 address
* `inet6` for IPv6 address (might not give anything if you have disabled IPv6 on your system)
* `ifconfig` may not work if ou have `tor` enabled.
