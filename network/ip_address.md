

# IP Address

## On new systems, get IP address of the system using the `ip` command: 
```
ip addr
```

## On older systems, use `ifconfig` command:
To use it on new systems where it might not be pre-installed, install `net-tools`
```
# sudo dnf install -y net-tools
ipconfig
```