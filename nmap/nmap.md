Common Commands | Description
--- | ---
`nmap -sC [HOST]` | Scan `[HOST]` using default scripts
`nmap -sV [HOST]` | Scan `[HOST]` using service version detection
`nmap -oA [OUTPUT_FILENAME_PREFIX] [HOST]` | Save `[HOST]` scan output in all formats
`nmap -sC -sV -oA [OUTPUT_FILENAME_PREFIX] [HOST]` | Preliminary scan format sometimes used by IppSec

Other Flags | Description
--- | ---
`-Pn` | No ping, helpful for Windows machines that don't respond to ICMP
`-sn` | No port scan, helpful for simple host discovery especially when scanning an entire subnet
`-iL [INPUT_FILENAME]` | Scan multiple hosts listed in `[INPUT_FILENAME]`
`-p [PORT/PORTS]` | Scan a specific port or ports (comma separated list and/or port ranges)
`-p-` | Scan all 65,535 TCP ports
`-sU` | Scan the most common UDP ports
`-O` | Enable OS detection
`-A` | Enable OS detection, service version detection, default scripts, and traceroute

