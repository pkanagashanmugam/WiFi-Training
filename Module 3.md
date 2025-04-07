# Module 3 - WLAN PHY Layer

### Q1. What are the different 802.11 PHY layer standards? Compare their characteristics.
There are various PHY layer standards that 802.11 covers.

| **`STANDARD`** | **`MODULATION`** | **`FREQUENCY BAND`** | **`DATA RATE`** |
|    :---:     |     :---:      |       :---:        |     :---:     |
|   802.11     |    DSSS,FHSS   | 2.4 GHz | 2 Mbps |
|   802.11a    |    OFDM (BPSK,QPSK,16-QAM,64-QAM)   | 5 GHz | 54 Mbps |
|   802.11b    |    DSSS    | 2.4 GHz | 11 Mbps |
|   802.11g    |    OFDM (BPSK,QPSK,16-QAM,64-QAM) and DSSS   | 2.4 GHz | 54.2 Mbps |
|   802.11n    |    OFDM (BPSK,QPSK,16-QAM,64-QAM)   | 2.4 GHz and 5 GHz | 600 Mbps (MIMO upto 4 spatial streams |
|   802.11ac    |    OFDM (BPSK,QPSK,16-QAM,64-QAM)   | 5 GHz | 6.93 Gbps (MIMO,MU-MIMO upto 8 spatial streams |

- **DSSS - Direct Sequence Spread Spectrum** : A technique where data is transmitted over a wide frequency band by spreading it across multiple frequencies. 
- **FSSS - Frequency Hopping Spread Spectrum** : A method where the transmitter and receiver hop between different frequencies in a predetermined pattern
- **MIMO - Multiple Input Multiple Output** : Uses multiple antennas to send and receive data simultaneously, allowing for higher throughput.
- **MU-MIMO - Multi User Multiple Input Multiple Output** : Modification of MIMO which allows multiple devices are allowed to communicate with the AP at the same time instead of a single device.
- **OFDM - Orthogonal Frequency Division Multiplexing** : A technique which splits the signal into multiple subcarriers to improve the speed of the transmission, especially in noisy environments.
- **BPSK - Binary Phase Shift Keying** : Modulation technique by which data is transmitted by changing the phase of a carrier wave between two distinct states, representing binary 0 and 1.
- **QPSK - Quadrature Phase Shift Keying** : Modulation technique by which 2 bits of data is transmitted by changing the phase of a carrier wave.
- **QAM - Quadrature Amplitude Modulation** : A modulation technique which combines Amplitude Modulation and Phase Shift Keying to transmit data.
  
### Q2. What are DSSS and FHSS? How do they work?
DSSS and FHSS are spread spectrum modulation techniques which deals with how signals are spread over a frequency domain. 

- **DSSS :** Direct Sequence Spread Spectrum is a technique where data signal is spread over a wide frequency band. The original data signal is multiplied by a pseudorandom noise sequence, which is a series of binary digits. The resultant spread signal is transmitted over air.

- **FHSS :** Frequency Hopping Spread Spectrum is another Spread Spectrum technique which works by rapidly changing the transmission frequency between hops according to a predefined hopping pattern. The transmitter and receiver are synchronized on the hopping pattern to ensure that the communication is not lost.

### Q3. How do modulation schemes work in the PHY layer? Compare different modulation schemes and their performance across various Wi-Fi standards.
Modulation is the process of varying one or more properties of a carrier wave in order to carry information. There are two types of modulation namely Digital and Analog modulation.

| **`MODULATION TECHNINQUE`** | **`WIFI STANDARD`** | **`PERFORMANCE`** |
|      :---:                  | :---:               | :---:             |
| **BPSK** | 802.11b | Provides a maximum speed upto 11 Mbps best suitable for long range communication |
| **QPSK** | 802.11a , 802.11g | Capable of providing higher data rates than BPSK with a maximum speed of 54 Mbps.|
| **16-QAM** | 802.11a, 802.11g, 802.11n | Provides higher data rate by encoding 4 bits per symbol which allows to provide a maximum speed of 54 Mbps for 802.11a/g and 600 Mbps for 802.11n standards.|
| **ASK** | Not generally used in Wi-Fi standards | Data is encoded by varying the amplitude of a waveform. A wave with high amplitude is understood for data carrying 1 as its information and wave with low amplitude is understood as 0.|

Different modulation schemes are used depending on the data rate, range, and interference conditions, with each scheme offering a tradeoff between speed and reliability.

### Q4. What is the significance of OFDM in WLAN? How does it improve performance?


### Q5. How are frequency bands divided for Wi-Fi? Explain different bands and their channels.


### Q6. What is the role of Guard Intervals in WLAN transmission? How does a short Guard Interval improve efficiency?


### Q7. Describe the structure of an 802.11 PHY layer frame. What are its key components?


### Q8. What is the difference between OFDM and OFDMA?


### Q9. What is the difference between MIMO and MU-MIMO?


### Q10. What are PPDU, PLCP, and PMD in the PHY layer?


### Q11. What are the types of PPDU? Explain the PPDU frame format across different Wi-Fi generations.


### Q12. How is the data rate calculated?
