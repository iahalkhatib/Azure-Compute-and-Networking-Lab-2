![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/1035291e-e07e-4b19-bdd0-63ff2e6b4a1e)


# Azure-Networking-and-Wireshark-Lab-2

# 1. Task 1. Create a new Rescource Group within Azure 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/90eb1b9e-cdc9-4e00-80cf-70021db1326e)

# 2. Task 2. Create a Virtual Network, Subnet, and VM1 running Windows 10 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/583d9b6f-1680-46d2-8e7d-6a219bd73f89)

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/8dd98cdf-6e10-420f-af9c-94bb3f7bb765)

# 3. Task 3. Create VM2 running Linux Ubuntu 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/baf710f5-4426-4566-81ed-0d7fdb1fa93a)


# 4. Task 4. Use RDP (Remote Desktop) to connect to VM1 its Public IP 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/451fe6a0-dd68-4b78-a9c3-eea2a630f83b)

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/a41c62df-7f89-4c65-b758-95a2b6b4f387)


# 5. Task 5. Download Wireshark on VM1 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/0e39d41a-bfbe-4aef-be3c-b17f4daebbdf)

# 6. Task 6. Use Wireshark to view traffic packets 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/99676ae0-a668-4b32-badb-aad4a376a87d)


# 7. Task 7. Filter traffic by ICMP. We will use this when we use Ping command to communicate between VM1 and VM2 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/8c5f3579-089e-42a9-8d63-d8b336a4ae31)


# 8. Task 8. Find the Private IP of VM2 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/c8d46f3f-d02b-49b4-a2eb-454ef7b81f64)


# 9. Task 9. Use the Private Ip of VM2 to Ping it From the Powershell in VM1 and view the Filtered traffic on Wireshark 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/86f2cc75-b879-458c-b4ff-01d70203cb89)

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/6a71b0a8-1eea-4383-8f73-10367112c72e)

# 10. Task 10. Using "Ping (VM2 Private Ip Address) -t) set a Perpetual Ping from VM1 to VM2 and view the change of traffic on Wireshark 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/1308095b-7089-41b4-932a-19868ef8bcfb)


# 11. Task 11. I will block IMCP traffic on VM2 Firewall and view the change in traffic on Wireshark 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/7a285447-9692-4cd6-a367-592835a45c0b)


# 12. Task 12. Find VM2 Firewall Settings inside Azure by searching for "Security Groups" and Selecting VM2 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/a19c46e5-129c-4152-8e61-f651526482cd)


# 13. Task 13. Add a new rule to VM2 security group to block ICMP traffic and view the change in traffic on Wireshark

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/a22e10c6-18fd-4265-a7ff-8130ef992229)
![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/a84d7e1e-96f3-4f83-aced-7a02b427b2e2)
![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/0424a4c0-975d-40bb-9530-e210b2c6e090)
![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/d694df58-9822-42a1-a957-a767b2b96367)


# 14. Task 14. Remove the new rule in VM2 security group to enable ICMP traffic and view the change in traffic on Wireshark

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/b7fa642d-a6de-41e2-a6bd-e216f1908596)


# 15. Task 15. Filter traffic in Wireshark by SSH

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/53df9718-0541-485d-8665-700a2b80ad6c)


# 16. Task 16. Connect from VM1 to VM2 using SSH and VM2 private IP Address and login credentials 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/d5238705-2d76-4250-9e3a-744349306631)
![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/c7111acd-6191-4397-9619-224e7315b3c7)
![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/e912fb78-972e-434a-adad-ee7d5c864ef4)


# 17. Task 17. See the green text as confirmation connection is complete and lets try some Linux commands 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/fe12ff3f-298f-4cec-9ba0-205512a4dd81)


# 18. Task 18. Exit the SSH connection using "$ exit" command 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/85a6ef85-e75d-4ffe-918e-0e4ece102e0c)

# 19. Task 19. Filter traffic in Wireshark by DCHP and Run "Ipconfig/renew" command in powerhshell in VM1 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/b559e47c-c534-45a7-b4c2-0c9716e6f3dc)


# 20. Task 20. Filter traffic in Wireshark by DNS and use "nslookup" for google and see some of the the public IP addresses for google

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/299c6e0e-1069-4da4-bd2e-26c0c65db1cf)


# 21. Task 21. Filter traffic in Wireshark by RDP "Tcp.port == 3389" and see the traffic related to the RDP I am using to connect to VM1 

![image](https://github.com/iahalkhatib/Azure-Networking-and-Wireshark-Lab-2/assets/170050432/18375bfe-aa55-44e5-b5af-80fe8b6564c4)

