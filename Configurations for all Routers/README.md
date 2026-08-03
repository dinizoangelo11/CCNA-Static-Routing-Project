## Router 1 Configuration

**Naming the Router**
- enable
- config t (configure terminal)
- hostname Router1

**Adding IP Address for each Interface**
- config t
- int f0/0
- ip address 10.0.1.2 255.255.255.0
- duplex auto
- speed auto
- no shut

---------------------------------------

- int f0/1
- ip address 10.0.0.1 255.255.255.0
- duplex auto
- speed auto
- no shut

----------------------------------------
**Setting IPs for Router1 Screenshot**

<img width="601" height="337" alt="Project1 - Setting IPs Router1" src="https://github.com/user-attachments/assets/ed9328d6-f2a5-4bee-8c0e-906cbdc599c2" />

---------------------------------------
**Checking information for ports on the router**
- do show ip interface brief
- (Since its in global configuration mode, I type "do" in front of the command / in regular config mode you do not need to type "do")

**Add in the routes after configuring IPs for all routers/PCs**
- config t
- ip route 10.1.0.0 255.255.255.0 10.0.0.2
- ip route 10.1.1.0 255.255.255.0 10.0.0.2

---------------------------------------
**Static Routes for Router1 Screenshot**

<img width="576" height="285" alt="Project 1- Static Routes Router1" src="https://github.com/user-attachments/assets/1df22159-55a5-4733-b3b2-f6e33ea4a81f" />

---------------------------------------
**Copying running configuration to your startup configuration**
- copy run start

  
## Router 2 Configuration

**Naming the Router**
- enable
- config t (configure terminal)
- hostname Router2

**Adding IP Address for each Interface**
- int f0/0
- ip address 10.1.0.2 255.255.255.0
- duplex auto
- speed auto
- no shut

---------------------------------------

- int f0/1
- ip address 10.0.0.2 255.255.255.0
- duplex auto
- speed auto
- no shut

---------------------------------------
**Setting IPs for Router2 Screenshot**

<img width="593" height="250" alt="Project 1 - Setting IPs Router2" src="https://github.com/user-attachments/assets/136b3a19-bfda-493e-9fde-2163026297af" />

---------------------------------------
**Checking information for ports on the router**
- do show ip interface brief
- (Since its in global configuration mode, I type "do" in front of the command / in regular config mode you do not need to type "do")
  
**Add in the routes after configuring IPs for all routers/PCs**
- config t
- ip route 10.1.1.0 255.255.255.0 10.1.0.1
- ip route 10.0.1.0 255.255.255.0 10.0.0.1

---------------------------------------
**Static Routes for Router2 Screenshot**

<img width="572" height="293" alt="Project 1 - Static Routes Router2" src="https://github.com/user-attachments/assets/d58c6591-453a-4123-9f65-140e098acf87" />

---------------------------------------
**Copying running configuration to your startup configuration**
- copy run start

## Router 3 Configuration

**Naming the Router**
- enable
- config t (configure terminal)
- hostname Router3

**Adding IP Address for each Interface**
- int f0/0
- ip address 10.1.0.1 255.255.255.0
- duplex auto
- speed auto
- no shut

---------------------------------------

- int f0/1
- ip address 10.1.1.2 255.255.255.0
- duplex auto
- speed auto
- no shut

---------------------------------------
**Setting IPs for Router3 Screenshot**

<img width="585" height="174" alt="Project 1 - Setting IPs Router3" src="https://github.com/user-attachments/assets/49474909-2d4f-40e0-b08d-73b286a262af" />

---------------------------------------
**Checking information for ports on the router**
- do show ip interface brief
- (Since its in global configuration mode, I type "do" in front of the command / in regular config mode you do not need to type "do")
  
**Add in the routes after configuring IPs for all routers/PCs**
- config t
- ip route 10.0.0.0 255.255.255.0 10.1.0.2
- ip route 10.0.1.0 255.255.255.0 10.1.0.2

---------------------------------------
**Static Routes for Router3 Screenshot**

<img width="574" height="301" alt="Project 1 - Static Routes Router3" src="https://github.com/user-attachments/assets/c7e9ec5e-bf7d-4975-ad92-a379c11ca2d9" />

---------------------------------------
*Copying running configuration to your startup configuration*
- copy run start
