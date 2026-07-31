## Configuring Network Information for PC1 and PC3

**Create IP that is located in the same subnet as your router (gateway)**
- Since Router1 is 10.0.1.2 and my subnet mask is 255.255.255.0, the PC needs to be in the range of 10.0.1.1 - 10.0.1.254
- You need to leave 10.0.1.0 as network address and 10.0.1.255 as broadcast address
- I chose 10.0.1.3 as my IP Address for PC1
-------------------------------------------
- Since Router3 is 10.1.1.2 and my subnet mask is 255.255.255.0, the PC needs to be in the range of 10.1.1.1 - 10.1.1.254
- You need to leave 10.1.1.0 as network address and 10.1.1.255 as broadcast address
- I chose 10.1.1.3 as my IP Address for PC3

## Steps for Configuring the PC1s Network Information
- In the IP Configuration box, make sure static is selected
- Write the IP Address chosen in the first box (10.0.1.3)
- Write the subnet mask in the second box (255.255.255.0)
- Write the Router1 IP or default gateway in the third box (10.0.1.2)

-------------------------------------------
**PC1 Network Information Screenshot**

<img width="1903" height="565" alt="Project 1 - PC1 Network Information" src="https://github.com/user-attachments/assets/bd04e431-872e-42fa-b32c-d4feb706994c" />

-------------------------------------------


## Steps for Configuring the PC3s Network Information
- In the IP Configuration box, make sure static is selected
- Write the IP Address chosen in the first box (10.1.1.3)
- Write the subnet mask in the second box (255.255.255.0)
- Write the Router1 IP or default gateway in the third box (10.1.1.2)

-------------------------------------------
**PC3 Network Information Screenshot**

<img width="1903" height="579" alt="Project 1 - PC3 Network Information" src="https://github.com/user-attachments/assets/6d8ab368-c961-4c79-b965-a3c8f278de6d" />

-------------------------------------------


PC1 and PC3 have now have static IP Addresses set up and are able to communicate with other hosts on the network since the static routes are in place
