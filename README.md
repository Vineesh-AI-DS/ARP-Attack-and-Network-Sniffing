# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![1 (1)](https://github.com/Vineesh-AI-DS/ARP-Attack-and-Network-Sniffing/assets/93427254/fdc6e89f-29a5-4768-988f-8f53d0f4346f)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![2 (1)](https://github.com/Vineesh-AI-DS/ARP-Attack-and-Network-Sniffing/assets/93427254/121924b2-b775-4d0f-bb73-50163068c352)



 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![3](https://github.com/Vineesh-AI-DS/ARP-Attack-and-Network-Sniffing/assets/93427254/61a51891-0b23-4780-94ca-3685a43bd989)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Uploading 4.png…]()



Invoke the wireshark and examine the various menus  and controls of the tool:

![5](https://github.com/Vineesh-AI-DS/ARP-Attack-and-Network-Sniffing/assets/93427254/ef34c638-0e7d-4939-8e57-789f6d1e8251)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
