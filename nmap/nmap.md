| Command | Description |
--- | ---
`nmap -p- [HOST]` | Scan all TCP ports on `[HOST]`
`nmap -iL [INPUT_FILENAME]` | Scan multiple hosts from `[INPUT_FILENAME]`
`nmap -oA [OUTPUT_FILENAME_PREFIX] [HOST]` | Save `[HOST]` scan output in all formats
`nmap -sV [HOST]` | Scan `[HOST]` using service version detection
`nmap -sC [HOST]` | Scan `[HOST]` using default scripts
`nmap -sC -sV -oA [OUTPUT_FILENAME_PREFIX] [HOST]` | Preliminary scan format sometimes used by IppSec

