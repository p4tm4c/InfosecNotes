# nmap

## Commands

### Preliminary scans inspired by IppSec tutorials

For a single host:
```
nmap -sV -sC -oA [OUTPUT_FILENAME_PREFIX] [HOST]
```

For multiple hosts contained in a list file:
```
nmap -sV -sC -oA [OUTPUT_FILENAME_PREFIX] -iL [INPUT_FILENAME]
```

## Flags

Flag | Description
--- | ---
`-Pn` | No ping, use for hosts that don't respond to ICMP
`-sn` | No port scan, helpful for simple host discovery especially when scanning an entire subnet
`-iL [INPUT_FILENAME]` | Scan multiple hosts listed in a file
`-sV` | Enable service version detection
`-sC` | Enable default scripts
`-O` | Enable OS detection
`-A` | Enable service version detection, default scripts, OS detection, and traceroute
`-p [PORT/PORTS]` | Scan a specific port or ports (comma separated list and/or port ranges)
`-p-` | Scan all 65,535 TCP ports
`-sU` | Scan the most common UDP ports
`-oA [OUTPUT_FILENAME_PREFIX]` | Save scan output in all formats
