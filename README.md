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
![1](https://github.com/Aakash0407/ARP-Attack-and-Network-Sniffing/assets/118799103/100e445d-dcde-43d9-882c-66aa3f117336)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/Aakash0407/ARP-Attack-and-Network-Sniffing/assets/118799103/8f92f656-51a7-487e-b67c-74b434542f7c)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/Aakash0407/ARP-Attack-and-Network-Sniffing/assets/118799103/16be6860-380c-46c6-b56e-173cee946f1e)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![4](https://github.com/Aakash0407/ARP-Attack-and-Network-Sniffing/assets/118799103/791f34a9-7389-4eab-9bc0-576b9930a265)


Invoke the wireshark and examine the various menus  and controls of the tool:
![5](https://github.com/Aakash0407/ARP-Attack-and-Network-Sniffing/assets/118799103/dde6ff86-717e-42ea-a1cf-44c170104b90)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
