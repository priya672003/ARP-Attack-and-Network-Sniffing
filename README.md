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



![image](https://github.com/priya672003/ARP-Attack-and-Network-Sniffing/assets/81132849/35388d8a-0f7c-4093-ac6b-4accd4bc713e)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


## OUTPUT:



![image](https://github.com/priya672003/ARP-Attack-and-Network-Sniffing/assets/81132849/19caced6-b80d-4f16-8b00-8195c31385a3)


 dsniff:   In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org



## OUTPUT:



![image](https://github.com/priya672003/ARP-Attack-and-Network-Sniffing/assets/81132849/a08fa384-0341-4c0b-b5db-31b96bfcc692)


In Kali issue the following commands:
sudo dsnifff



## OUTPUT:


![image](https://github.com/priya672003/ARP-Attack-and-Network-Sniffing/assets/81132849/c7e09b5f-3740-41fb-9ffc-65930e551a7c)


Invoke the wireshark and examine the various menus  and controls of the tool:


![image](https://github.com/priya672003/ARP-Attack-and-Network-Sniffing/assets/81132849/1cc0207a-0d88-407d-af4f-afd1a68d14cc)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
