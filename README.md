# CCNA Static Routing Lab

## Overview

This Cisco Packet Tracer lab demonstrates how to configure a small routed network using **static routing**.

The objective is to configure all devices with the correct IP addresses, configure router interfaces, create static routes between routers, and verify end-to-end connectivity using ping.

---

## Objectives

- Configure PCs with IPv4 addresses
- Configure default gateways
- Configure router interfaces
- Enable interfaces using `no shutdown`
- Configure static routes
- Verify connectivity between networks
- Save router configurations

---

# Network Topology


<img width="1233" height="511" alt="image" src="https://github.com/user-attachments/assets/7b459edc-428b-4ad3-91e0-b4143be038ff" />

---

## Network Addressing

| Device | Interface | IP Address | Subnet Mask |
|---------|-----------|------------|-------------|
| PC1 | NIC | 192.168.1.1 | 255.255.255.0 |
| R1 | G0/1 | 192.168.1.254 | 255.255.255.0 |
| R1 | G0/0 | 192.168.12.1 | 255.255.255.0 |
| R2 | G0/0 | 192.168.12.2 | 255.255.255.0 |
| R2 | G0/1 | 192.168.13.2 | 255.255.255.0 |
| R3 | G0/0 | 192.168.13.3 | 255.255.255.0 |
| R3 | G0/1 | 192.168.3.254 | 255.255.255.0 |
| PC2 | NIC | 192.168.3.1 | 255.255.255.0 |

---

# Configuration Steps

## Step 1

Configured the IP address of PC1.

<img width="1919" height="1011" alt="configuring-PC-1-IP-Address" src="https://github.com/user-attachments/assets/8d17c77d-e489-4497-9913-e6554ac6207e" />


---

## Step 2

Configured the IP address of PC2.

<img width="1883" height="1005" alt="configuring-pc-2 ipv4-address" src="https://github.com/user-attachments/assets/2b5f078c-a1cb-4d90-aeef-dfa182019a83" />


---

## Step 3

Configured router interfaces with the correct IPv4 addresses and enabled them using `no shutdown`.
<img width="1907" height="1009" alt="Configuring-R1-interfaces" src="https://github.com/user-attachments/assets/9c2fb686-7539-4ecd-a847-375dad6b5c7e" />

<img width="1912" height="1007" alt="configuring-R2-interfaces" src="https://github.com/user-attachments/assets/057636eb-8ba9-4ae3-a80a-ad9b9d170682" />

<img width="1919" height="1006" alt="configuring-R3-interfaces" src="https://github.com/user-attachments/assets/75bb97d7-3368-4a27-9da9-8d77b4d77a52" />


---

## Step 4

Configured static routes on each router and verifying interface status.

<img width="1919" height="1007" alt="configuring-R1-routes" src="https://github.com/user-attachments/assets/b9583b20-0eb1-492a-be2c-567a743fb7a2" />
<img width="1919" height="1010" alt="configuring-R2-ROUTES" src="https://github.com/user-attachments/assets/76c2d2d6-0034-4a25-8e44-39bed17ddb45" />
<img width="1900" height="1003" alt="configuring-R3-routes" src="https://github.com/user-attachments/assets/c35890c6-04ee-4394-8336-ee6261461328" />



## Step 6

Tested connectivity using ping.

Successful communication between the networks confirmed that the static routes were configured correctly.

<img width="1904" height="1009" alt="Confirming PC-1-can-commuinicate-to-PC-2" src="https://github.com/user-attachments/assets/18dd928d-9716-4225-8309-85d35a02b3bf" />


---

# Skills Demonstrated

- Cisco IOS CLI
- Router Configuration
- Static Routing
- IPv4 Addressing
- Interface Configuration
- Network Verification
- Connectivity Testing
- Troubleshooting

---

# Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- Static Routing
- IPv4
- Ethernet Networking

---

# Learning Outcomes

After completing this lab I was able to:

- Configure router interfaces
- Configure end devices
- Assign default gateways
- Configure static routes
- Verify network connectivity
- Troubleshoot routing issues
- Save router configurations

---

## Author

**Susan Wangari**

Bachelor of Science in Mathematics and Computer Science

Cisco Networking Enthusiast
