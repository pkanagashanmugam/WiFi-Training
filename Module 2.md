# Module 2 - WLAN AP/Controller Architectures

### Q1. Brief about SplitMAC architecture and how it improves the AP's performance.
SplitMAC architecture is the architecture widely is used in WLAN setup where MAC layer functionalities are divided between _Access Points (AP)_ and _WLAN Controller (WLC)_ for better resource management and load reducal on Access Points. The **Access Points** handle real time tasks such as Client Association, Probe Response, Packet buffering, Data Encryption, Aggregation and **Controllers** handle non real time tasks such as QoS Management, Load balancing, Association / Di-association, Classifying, 802.1x/EAP authentication. 

By shifting the control functions to the Controller, Access Points becomes lightweight and improves response time and reliability. The Controller has entire view of the network and allows efficient allocation of resources. 

### Q2. Describe about CAPWAP, explain the flow between AP and Controller.
CAPWAP which stands for `Control and Provisioning of Wireless Access Points` is the protocol used to support communication between components of the SplitMAC architecture. Two Tunnels are established to support this communication namely : _Control Tunnel_ and _Data Tunnel_. The flow of communication between AP and WLC is as follows:

**1. DHCP :** The Access Point requests for an IP address to DHCP server using the DHCP Protocol

**2. Access Controller Discovery :** The Access Point finds out the WLAN Controller using a Discovery Request and receives Discovery Response from the WLC post which DTLS connection is established for secure communication.

**3. AP Access Control :** The Access Point securely connects to the WLC by sending Join Request and receives Join Response from WLC. Configuration data is sent as Images if necessary.

**4. Configuration Delivery :** Configuration details are requested by AP and WLC responds with Configuration Status Response. If there are any changes in the state, AP sends out Configuration Status Event Request to which WLC acknowledges with Configuration Status Event Response.

**5. Tunnel Maintenance :** AP and WLC maintain active connection by sending and receiving Keepalive messages and Echo Request and Replies.

**6. Configuration Update :** If there are any changes in the configuration, AP sends Configuration Update Request and WLC responds with Configuration Update Response.

### Q3. Where does CAPWAP fit in OSI model, What are the two tunnels in CAPWAP and its purpose?
CAPWAP ideally operates from Layer 4 to Layer 7 of the OSI Model.

- **Transport Layer(Layer 4) :** CAPWAP uses UDP protocol for transport between AP and the Controller.
- **Session Layer(Layer 5) :** CAPWAP establishes and maintains the session between AP and Controller by sending Keepalive messages and status updates.
- **Presentation Layer(Layer 6) :** CAPWAP uses Datagram Transport Layer Security encryption to ensure secure transmission of messages.
- **Application Layer(Layer 7) :** CAPWAP by itself is a control protocol which is an application-level protocol designed to manage and provision the APs. 

The two tunnels in CAPWAP are:

1. Control Tunnel : Used for control and management of APs.
2. Data Tunnel : Used as passage through which Data is transmitted between AP and the controller.


### Q4. What is the difference between Lightweight APs and Cloud-based APs?

| **Lightweight AP** | **Cloud Based AP**|
|       :---:        |        :---:      |
| Managed by a WLAN Controller (WLC) | Managed by a Cloud based Controller |
| Requires a local physical controller to manage and configure APs | No need of on premise hardware as management and configuration of APs are done over cloud |
| Scalability is dependent on capacity of WLC | Highly scalable since configuration of APs are completely remote |
| Since WLC is local, network admins have more control over security | Security policies are managed through the cloud interface and enforced on the APs |
| Costs are slightly higher than that of Cloud Based APs due to initial cost of WLC hardware | Lower initial costs but subscription-based recurring costs |

### Q5. How the CAPWAP tunnel is maintained between AP and controller?
CAPWAP tunnel is maintained between AP and Controller by periodic exchange of packets to check the status of the tunnel. _Keepalive_ packets verify data tunnel's connectivity and _Echo_ packets verify control tunnel's connectivity. CAPWAP tunnels can be re-established in case of failure or connection teardown.

### Q6.What is the difference between Sniffer and monitor mode? Explain with use case for each mode.


### Q7.If WLC deployed in WAN, which AP mode is best for local network and how?


### Q8. What are challenges if deploying autonomous APs (more than 50) in large network like university?


### Q9. What happens on wireless client connected to Lightweight AP in local mode if WLC goes down?
