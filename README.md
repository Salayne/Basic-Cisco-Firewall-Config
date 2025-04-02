# Basic-Cisco-Firewall-Configuration


1. Add an ASA firewall , 2960 switch, 2 PC End devices.
2. Click on the Firewall CLI and use the command **en** to enable no password.
3. Use command **config t** to begin configuration.
4. To enable a password. Use command **enable password** and enter a password.
5. Configure the interface with command **int g1/1**  or whichever interface is in use.
6. Add IP address using the command **ip add** plus the ip address and subnet mask. 
7. Name the network using the command **nameif**
8. Set the security level with the command **security-level plus** the level.


![image alt](https://github.com/Salayne/Basic-Cisco-Firewall-Config/blob/4f0987e62f8df4e2c11c677a5269864169960583/Screenshot%202025-04-01%20224549.png)


9. Next set up a PC and perform a ping test 

![image alt](https://github.com/Salayne/Basic-Cisco-Firewall-Config/blob/2380557fc29c484b40f75aeab844ddcf45fd1b8a/Screenshot%202025-04-01%20224837.png)

**PING TEST**

![image alt](https://github.com/Salayne/Basic-Cisco-Firewall-Config/blob/0a0c7f594829f63f814eb61c0c25450f83e45f2a/Screenshot%202025-04-01%20224930.png)


10. Configure the DCHP(Dynamic Host Configuration Protocol)  this system will helps devices connect to a network by assigning them IP addresses and other network settings.
11. Use command **dhcpd address** - address plus the network name.
12. Next configure the DNS(Domain Name Server) with the command **dhcps dns** plus address.
13. Enable this with command **dhcpd enable** and the name of the network.


![image alt](https://github.com/Salayne/Basic-Cisco-Firewall-Config/blob/1432a8bedc5df40faccb2a0905f03afdaac6700f/Screenshot%202025-04-01%20225828.png)

14. Save this configuration with the command **wr mem** (write memory).

![image alt](https://github.com/Salayne/Basic-Cisco-Firewall-Config/blob/107bcf6d054364c931a6065c929c6354cf6536c8/Screenshot%202025-04-01%20230126.png)


16. Switch pc 1 Ip configuration to dhcp and switch pc 2 to dhcp

![image alt(https://github.com/Salayne/Basic-Cisco-Firewall-Config/blob/ef28aefb54f2431a06acfe6595564c35cea32931/Screenshot%202025-04-01%20230816.png)

