![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/1035291e-e07e-4b19-bdd0-63ff2e6b4a1e)


# Azure-Networking-and-Wireshark-Lab-2

# 1. Task 1. Create a new Rescource Group within Azure 


# 2. Task 2. Create a Virtual Network, Subnet, and VM1 running Windows 10 

# 3. Task 3. Create VM2 running Linux Ubuntu 

# 4. Task 4. Use RDP (Remote Desktop) to connect to VM1 its Public IP 

# 5. Task 5. Download Wireshark on VM1 

# 6. Task 6. Use Wireshark to view traffic packets 

# 7. Task 7. Filter traffic by ICMP. We will use this when we use Ping command to communicate between VM1 and VM2 

# 8. Task 8. Find the Private IP of VM2 

# 9. Task 9. Use the Private Ip of VM2 to Ping it From the Powershell in VM1 and view the Filtered traffic on Wireshark 

# 10. Task 10. Using "Ping (VM2 Private Ip Address) -t) set a Perpetual Ping from VM1 to VM2 and view the change of traffic on Wireshark 

# 11. Task 11. I will block IMCP traffic on VM2 Firewall and view the change in traffic on Wireshark 

# 12. Task 12. Find VM2 Firewall Settings inside Azure by searching for "Security Groups" and Selecting VM2 

# 13. Task 13. Add a new rule to VM2 security group to block ICMP traffic and view the change in traffic on Wireshark

# 14. Task 14. Remove the new rule in VM2 security group to enable ICMP traffic and view the change in traffic on Wireshark

# 15. Task 15. Filter traffic in Wireshark by SSH

# 16. Task 16. Connect from VM1 to VM2 using SSH and VM2 private IP Address and login credentials 

# 17. Task 17. See the green text as confirmation connection is complete and lets try some Linux commands 

# 18. Task 18. Exit the SSH connection using "$ exit" command 

# 19. Task 19. Filter traffic in Wireshark by DCHP

# 20. Task 20. Run "Ipconfig/renew" command in powerhshell in VM1 

# 21. Task 21. Filter traffic in Wireshark by DNS and use "nslookup" for www.google.com and see some of the the public IP addresses for www.google.com

# 22. Task 22. Filter traffic in Wireshark by RDP "Tcp.port == 3389" and see the traffic related to the RDP I am using to connect to VM1 

