# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
```
Tested By: Shaik Sameer Basha
Reg. no: 212222240093
```
Find out the ip address of the attackers system
## OUTPUT:

![img0](https://github.com/user-attachments/assets/f71fd39f-1f7d-4761-8f7a-aacb11f0bbb2)


## Invoke msfconsole
## OUTPUT:

![img2](https://github.com/user-attachments/assets/fedff2d6-0124-491d-8622-a3d0209747f9)


Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

![img3](https://github.com/user-attachments/assets/5a83174d-2ee6-435f-95ee-ed111ad9f7dd)

## Port scanning:
## msf > nmap -sT 192.168.1810/24-p1-1000

![img4](https://github.com/user-attachments/assets/d2fad85c-c6ff-49fb-a3d5-6a651d68b66e)

## msf > db_nmap 192.168.181.0/24

![img5](https://github.com/user-attachments/assets/0048056c-049d-487b-906b-3b6c47259399)

## kali > ls-l

![img6](https://github.com/user-attachments/assets/4e0abcf9-9d05-439d-83f0-6c8fa852b687)

## search 

![img7](https://github.com/user-attachments/assets/6fb72d8c-4dbd-4c68-9a01-eaf57912a0ca)

## info

![img8](https://github.com/user-attachments/assets/2116c3a3-e8ee-4d43-9afa-fd6585527545)

## MYSQL ENUMERATION
## db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

![img9](https://github.com/user-attachments/assets/cc1409ed-5149-4000-be59-836ec6011e43)

## search

![img10](https://github.com/user-attachments/assets/e8bef46a-66f8-403c-9cc1-8408b98f753b)

##  use 11 Or: use auxiliary/scanner/mysql/mysql_version

![img11](https://github.com/user-attachments/assets/59814e7b-a8b3-49b8-a9f2-cda293476510)

## Use the set rhosts command to set the parameter and run the module, as follows:

![img12](https://github.com/user-attachments/assets/c4aced52-b8ec-415f-b5f2-b31c2b78590a)

## After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

![img13](https://github.com/user-attachments/assets/89c0ad50-28d8-4ebd-a0e0-3d21b29e1c8e)

## /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 

![img14](https://github.com/user-attachments/assets/7d2e5c98-9825-4051-a07b-61871320f5c1)

![img15](https://github.com/user-attachments/assets/8ab06d01-2434-4acb-b739-d863579f49e8)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
