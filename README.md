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
![273780018-2fe52578-42cb-4242-97b5-1777d143033a](https://github.com/Bakkiyalakshmi29/ARP-Attack-and-Network-Sniffing/assets/119406233/0a3e4b12-f22e-4abc-a68a-84e5b009f836)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![273780164-ecc9cfec-4038-4fac-b946-63bf348d1195](https://github.com/Bakkiyalakshmi29/ARP-Attack-and-Network-Sniffing/assets/119406233/1b325a88-a3e8-4cd7-94fb-496e1651108a)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![273780288-b3f418ba-fdaf-49e2-a50d-b7b8ef688efb](https://github.com/Bakkiyalakshmi29/ARP-Attack-and-Network-Sniffing/assets/119406233/66b302d3-cf8a-49d8-b5f4-5c01c32f4ad4)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![273780348-d28920c0-c2dd-477a-b882-4cafd6577eba](https://github.com/Bakkiyalakshmi29/ARP-Attack-and-Network-Sniffing/assets/119406233/f1a69670-29bb-41aa-98f0-aed294612a1a)




Invoke the wireshark and examine the various menus  and controls of the tool:
![273780446-d5011e8e-d087-4d6b-a580-2170535b49fd](https://github.com/Bakkiyalakshmi29/ARP-Attack-and-Network-Sniffing/assets/119406233/067fcd5c-bc76-498a-813c-8fab8ec52c71)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
