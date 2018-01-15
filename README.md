![alt text](https://github.com/Hackdwerg/reconfirm/blob/master/rsz_1rsz_reconfirm.png)
# reconfirm
Reconfirm - a small tool that helps you during your recon process

## Usage:
```bash
./reconfirm -t <IP>
./reconfirm -g (some tips and tricks) 
./reconfirm -h (Help menu)
./reconfirm -v (version of software)
```

## example
```bash
./reconfirm -t 10.11.1.1
``` 

## To-Do:
1. Add stages of nmap intensity
1. Add read from file (nmap)
1. Only output positive results to file
1. Cleanup after ctrl+c 
1. Add more ports with tools and tricks
1. Add update function
1. Making sure that IP is valid upon entering (see variable regex for starters, this is still a not used variable.. im lazy)


## Ports to add (for now): 
* 69 (tftp)
* 88 (kerberos)
* 135 (MSRPC)
* 161-162 (SNMP)
* 143/993 (IMAP)
* 389/636 (LDAP)
* 1025/2049 (NFS/IIS)
* 1521 (ORACLE DATABASE)
* 2100 (ORACLE XML DB)
* 5900 (VNC)
* 8080 (TOMCAT?*) 

## Stages to add:
* Light scan
* Intense scan
