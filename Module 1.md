# Module 1 - Introduction and History of Wi-Fi

### Q1. In which OSI layer the Wi-Fi standard/protocol fits.

Wi-Fi which stands for Wireless Fidelity is a wireless networking technology used to connect devices. Hence it operates in Layers 1 (Physical Layer) and 2 (Data Link Layer). The standard **802.11** specifies how devices communicate without wired connection.

### Q2. Can you share the Wi-Fi devices that you are using day to day life, share that device's wireless capability/properties after connecting to network. Match your device to corresponding Wi-Fi Generations based on properties.

Almost every device we use nowadays use Wi-Fi. Primary devices like _Mobile Phones, Laptops and Television_ use Wi-Fi to access the internet.

| Device | Property | Wi-Fi Generation |
| :---:  | :---:    | :---:            |
| Mobile Phone | Mobile Phones support both 2.4 GHz and 5 GHz bandwidth with speed upto 1 Gbps  | Wi-Fi 5 (802.11ac) |
| Laptop | Laptops, similar to Phones support both bands but can speed upto 1.3 Gbps | Wi-Fi 5 (802.11ac) |
| Television | Smart TVs use 5 GHz mainly for streaming high quality content which otherwise uses 2.4 GHz band and can speed upto 500 Mbps | Wi-Fi 5 (802.11ac) |

The Wi-Fi properties in Laptop can be checked using `netsh wlan show drivers` command on the command prompt.

![image](https://github.com/user-attachments/assets/1c5b67b9-d68c-450d-bcdc-4704d6592419)

### Q3. What is BSS and ESS?

BSS stands for **Basic Service Set** which is the building block of the Wireless LAN. It is made up of group of Wireless devices which are connected to an Access Point for intra network communication. BSS is analogous to Switch or Hub in a wired network.

ESS which stands for **Extended Service Set**, is a group of BSSs which allows devices to move between Access Points in the same network.

### Q4. What are the basic functionalities of Wi-Fi Access Point?

Access Point is the networking device in a network which translates internet connectivity from a wired medium to a wireless medium to all wireless devices. The primary function of Wi-Fi Access Points are to provide wireless network connectivity from a wired LAN connection. It allows performs the function of routing by analyzing the incoming packet and routing it to the desired wireless device. Moreover, it alos provides security by adhering to the security standards. It can also act as the DHCP server, providing IP addresses to the wireless device when they connect to the network.

### Q5. Difference between Bridge mode and Repeater mode.

Bridge mode and Repeater mode are two of the various toplogies in Wi-Fi Networks.

| **Bridge Mode** | **Repeater Mode** |
|      :---:      |      :---:        |
| Used to connect separate networks, facilitating communication between devices on different LANs | Used to extend the range of a single network by amplifying and retransmitting the existing Wi-Fi signal |
| Bridges operate on Layer 2 of the OSI model | Repeaters operates on Layer 1 of the OSI model concentrating only on amplifying the signals it receives |
| Eg: It is used to connect networks on two different buildings | Eg: It is used in buildings with large space to extend connectivity of the Access Points to other rooms |

### Q6. What are the differences between 802.11a and 802.11b.

**802.11b :** 802.11b was created in 1999 which works on the frequence range of 2.4 GHz supporting speed of 11 Mbps. It was mainly designed for domestic purposes.

**802.11a :** This Wi-Fi standard was created in 1999 which works on the frequency range of 5 GHz with speed upto 54 Mbps. It is used for industrial and commercial purposes. It was invented after 802.11b standard  to avoid inteferences with devices communicating in 2.4 GHz range. Called as Wi-Fi 2

### Q7. Configure your modem/hotspot to operate only in 2.4Ghz and connect your laptop/Wi-Fi device, and capture the capability/properties in your Wi-Fi device. Repeat the same in 5Ghz and tabulate all the differences you observed during this.

### Q8. What is the difference between IEEE and WFA
### Q9. List down the type of Wi-Fi internet connectivity backhaul, share your home/college's wireless internet connectivity backhaul name and its properties
### Q10. List down the Wi-Fi topologies and use cases of each one.
