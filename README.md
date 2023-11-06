# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/NAVEENKUMAR4325/ARP-Attack-and-Network-Sniffing/assets/119479566/06ce9fa0-f4f9-47e1-a10c-90a3b2da0c01)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/NAVEENKUMAR4325/ARP-Attack-and-Network-Sniffing/assets/119479566/1ce58962-3fb5-4228-87ca-c7a21f110bae)


dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/NAVEENKUMAR4325/ARP-Attack-and-Network-Sniffing/assets/119479566/0706942a-3227-4b0b-a885-63cb24a3b927)




In Kali issue the following commands:sudo dsnifff
## OUTPUT:

![image](https://github.com/NAVEENKUMAR4325/ARP-Attack-and-Network-Sniffing/assets/119479566/c2559f1a-68c5-48a7-aa8d-ca1dba375e6a)



Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/NAVEENKUMAR4325/ARP-Attack-and-Network-Sniffing/assets/119479566/6959c32b-aee6-41c2-8084-75b5eea80fdc)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
