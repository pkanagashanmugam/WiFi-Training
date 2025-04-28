# Module 5 - Advanced Features and Standard Extensions

### Q1. What are the key features of Wi-Fi 6, 6E and 7 and how do they differ from previous standards like Wi-Fi 5 (802.11ac)?
| **Wi-Fi 5** |**Wi-Fi 6** |	**Wi-Fi 6E**	| **Wi-Fi 7** |
|  :---:  |  :---:  |  :---:    |  :---:  |
| Uses 5 GHz frequency spectrum | Uses 2.4 and 5 GHz frequency spectrum | Uses 2.4 and 6 GHz frequency spectrum | Uses 2.4, 5 and 6 GHz frequency spectrum |
| Supports maximum of 3.5 Gbps data rate | Supports maximum of 9.6 Gbps data rate | Supports maximum of 9.6 Gbps data rate | Supports maximum of 46 Gbps data rate |
| The maximum channel width is 80 MHz and has an option of 160 MHz | The maximum channel width is 160 MHz | The maximum channel width is 160 MHz | The maximum channel width is 320 MHz |
| Supports 256-QAM Modulation |	Supports 1024-QAM Modulation | Supports 1024-QAM Modulation | Supports 4096-QAM Modulation |

### Q2. Explain the role of OFDMA in Wi-Fi 6 and how it improves network efficiency.
OFDMA (Orthogonal Frequency Division Multiple Access) is one of the key technologies introduced in Wi-Fi 6 (802.11ax) to improve efficiency, especially in environments with many connected devices. OFDMA being a upgraded version of OFDM which allows a single user to transmit data in different sub-carriers, allows multiple users to transmit and receive data in the sub-carriers.

By splitting the channel into multiple sub carriers and grouping them as Resource Units(RU), OFDMA allocates different devices,different RUs to allow them to transmit and receive data at the same time. By allowing multiple devices to transmit and receive data simultaneously over the same channel, Wi-Di 6 improves network efficiency.

### Q3. Discuss the benefits of Target Wake Time (TWT) in Wi-Fi 6 for IoT devices.
Target Wake Time is a key feature to improve power efficiency for IoT devices. Target Wake Time allows devices to negotiate time intervals for communication and allows the battery powered IoT devices to sleep otherwise. By doing so, it not only allows Power Management in IoT devices, it also reduces unnecessary network congestion. Station sends a Target Wake Time request to the AP proposing wake intervals. Once AP confirms the schedule, the Station sleeps and wakes up only at agreed times for communication.

### Q4. Explain the significance of the 6 GHz frequency band in Wi-Fi 6E.
Network congestion in 2.4 GHz and 5 GHz lead to the expansion of 6 GHz frequency spectrum. Wi-Fi 6E adds almost 1200 MHz of spectrum from 5.9 GHz to 7.1 GHz. Allows 14 80MHz channels or 7 160 MHz channels. While the 2.4 GHz and 5 GHz are crowded with Wi-Fi, Bluetooth and other devices, 6 GHz frequency spectrum is dedicated to devices using Wi-Fi 6E standard. 

### Q5. Compare and contrast Wi-Fi 6 and Wi-Fi 6E in terms of range, bandwidth, and interference.
| **Wi-Fi 6** | **Wi-Fi 6E** |
|    :---:    |     :---:    |
| Uses 2.4 GHz and 5 GHz frequency spectrum | Uses 2.4 GHz and 6 GHz frequency spectrum |
| They have a good range but can be prone to interference by other devices | Since their frequency range is dedicated to devices using Wi-Fi 6E standard, they have much less inteference |
| Supports bandwidths up to 160 MHz on the 5 GHz band, which is well-suited for many applications | The 6 GHz band offers significantly more bandwidth, with up to 1,200 MHz available offering wider channels for bandwidth-intensive tasks | 

### Q6. What are the major innovations introduced in Wi-Fi 7 (802.11be)?
Wi-Fi 7 also known as Extremely High Throughput brings various new additions to the existing standards by concentrating more on data rates, reliability and decreasing latency. By almost doubling the channel width from Wi-Fi 6/6E 's 160 MHz to 320 MHz allowing higher data rates. By modifying the modulation rates to accomodate more bit, it switches from existing 1024-QAM to 4096-QAM.

It allows use of multiple frequency band for the first time in Wi-Fi technology, allowing access to 2.4 GHz, 5 GHz and 6 GHz bands at the same time. It increases number of spatial streams to accomodate 16x16 MIMO.

### Q7. Explain the concept of Multi-Link Operation (MLO) and its impact on throughput and latency.
Earlier, even though the Wi-Fi standards use multiple frequency bands, the Wi-Fi device is allowed to connect only to one of the available frequency bands. With Multi Link Operation, Wi-Fi connected devices can now aggregate multiple links to transmit and receive data in parallel. Aggregation allows the throughput to increase and dynamic selection of these links will ensure that devices face much lower latency

### Q8. What is the purpose of 802.11k and v, and how does it aid in roaming?


### Q9. Explain the concept of Fast BSS Transition (802.11r) and its benefit in mobile environments.


### Q10. How do 802.11k/v/r work together to provide seamless roaming in enterprise networks?
