# Ancora-Education-Ucertify-Lab63
# Using Probing Tools

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=16]

## Objective of the Lab 
In this lab, you will learn to use probing tools. Nmap is a free and open-source utility for network discovery and security auditing. lsof is 'LiSt Open Files', and used to find out what type of files are open by which process. 
## Instructions 
### STEP 1 
From the desktop, open the Terminal window. 
### STEP 2
Execute the following command to probe for open TCP on the local system:
```bash
nmap localhost
```
### STEP 3
Execute the following command to probe for open UDP on the local system:
```bash
nmap -sU localhost
```
### STEP 4 
Execute the following command to probe for ports 5000 and 10000 on the local system:
```bash
nmap -p 5000-10000 localhost
```
### STEP 5 
Execute the following command to display a summary of network packet information by protocol:
```bash
netstat -s
```
### STEP 6
Execute the following command to display the routing table:
```bash
netstat -l
```
### STEP 7
Execute the following command to open network sockets:
```bash
lsof -i
```
### STEP 8 
Execute the following command to open network sockets without resolving hostnames or port names:
```bash
lsof -inP
```

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
