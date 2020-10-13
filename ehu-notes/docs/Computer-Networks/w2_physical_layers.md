# Physical Layer Part 1
* Carries ‘BITS’ stream over a physical medium.
* Foundation on which other layers build
* Properties of wires, fiber, wireless limit what the network can do
* Key responsibility is to send (digital) bits using signals

1. Application
2. Transport
3. Network
4. (Data) Link
5. Physical

![Physical Layer](https://elele.team/upload/5BiJvF.png "Physical Layer")


## Transmission Medium
Links used  by the devices to transmit and receive data. 

![Transmission Medium](https://elele.team/upload/0xWp8Q.png)

## Copper Cable (Ethernet)
* Unshielded Twisted Pair (UTP)
* Shielded Twisted Pair (STP)

![Copper Cable](https://elele.team/upload/NySkrD.png)

## Copper Cable (Coaxial)
* Better shielding and more bandwidth for longer distances and higher rates than twisted pair.

![Coaxial](https://elele.team/upload/YQose8.png)

## Optical Fiber Media
* Light Waves
* High Speed Transmission

![OFM](https://elele.team/upload/6mpx8l.png)

## Copper Cable vs Optical Fiber



| Implementation Points         | Copper Cable      | Fiber Optics       |
| ----------------------------- | ----------------- | ------------------ |
| Bandwidth                     | 10 Mbps - 10 Gbps | 10 Mbps - 100 Gbps |
| Range                         | 10 Mbps - 10 Gbps | 10 Mbps - 100 Gbps |
| Immunity to EMI and RFI       | Relatively Short  | Relatively High    |
| Immunity to Electrical Hazards| Low               | High               |
| Media and Connector Cost      | Low               | High               |
| Installation skills required  | Lowest            | Highest            |
| Safety                        | Lowest            | Highest            |

## Wireless Medium (Electromagnet Spectrum)
* All practical links rely on electromagnetic radiation propagating through a medium 
* Different bands have different uses e.g. Radio: wide-area broadcast; Microwave: LANs and 3G/4G; 

![Wireless Medium](https://elele.team/upload/ENFxKv.png)

* Wireless Miedum has the following areas of concern:
    * Coverage
    * Interference
    * Security


![Wireless Medium](https://elele.team/upload/2V5MIH.png)

---

# Physical Layer Part 2

## Bit Representation
![](https://elele.team/upload/pcxhu1.png)

## Bit Synchronization

* Asynchronous
    * Uses start bit and stop bit to indicate when transmission occurs from sender to receiver.

* Synchronous
    * Uses a reference clock to coordinate transmissions by both sender and receiver.

## Data Flow

* Simplex
    * Communication is always unindirectional
    * One device can transmit and other deivce will receive
        * For Example: Keyboard, Traditionl Monitors, etc.

* Half Duplex
    * Communication is in both directions but not at the same time or frequency
    * If one device is sending, the other can only receive
        * For Example: Walkie-Talkies, even current celluar system, etc.

* Full Duplex
    * Communication is in both directions simultaneously.
    * Both devices can send and receive at the same time and at same frequency.
        * For Example: Telephone lines, etc


## Transmissions Type
![](https://elele.team/upload/WB07iN.png)

* Baseband is related to digital signal transmission where the entire bandwidth or channel is used by single user. 
* Carriers one data signal at a time.
* Baseband is related to digital signals
* Ethernet is an example of baseband system

![](https://elele.team/upload/L6grXe.png)

* Broadband refers to any kind of signal transmission technique that carrier two or more different type of data in separate channels.
* Broadband signals can share same medium.
* Broadband is related to analog signals
* Cellular communication is an example of broadband System

## Modulation
Modulation is a process of imposing data signal wave onto a carrier wave

![](https://elele.team/upload/zUcBPG.png)


## Multiplexing
Multiplexing in networking means multiple signals are combined and thus travel simultaneously over the transmission medium.

![](https://elele.team/upload/7Y3PRC.png)

* Time Division Multiplexing (TDM)
* Statistical Time Division Multiplexing (STDM)
* Frequency Division Multiplexing (FDM)
* Orthogonal Frequency Division Multiplexing (OFDM) 
* Code Division Multiplexing (CDM)
* Frequency Hopping 

---

### Time Division Multiplexing (TDM)
Time Division Multiplexing (TDM) shares a channel over time by placing users on different time slots.

* Users can take turns on a fixed schedule.
* Widely used in telephone/cellular systems.


![](https://elele.team/upload/aVqoj5.png)
Main feature of TDM is equality. Equality is not sufficient in many situations 
(Some users may have more data or higher priority)


### Statistical Time Division Multiplexing (STDM)
Statistical Time Division Multiplexing (STDM) analysis statistics such as workload, need or priority and determines over the fly how much time each user should get.

![](https://elele.team/upload/ea1qbM.png)

* More Efficient
* More Control

### Frequency Division Multiplexing (FDM)
Frequency Division Multiplexing (FDM) allows different users by dividing the available bandwidth or frequency band into different non-overlapping sub channels or bands.

![](https://elele.team/upload/lDzVFr.png)

### Orthogonal Frequency Division Multiplexing (OFDM) 
Orthogonal Frequency Division Multiplexing (FDM) allows different users by dividing the available bandwidth or frequency band into different orthogonal overlapping sub channels or bands.

Used in many modern wireless communication system such as 4G, 5G, Wi-Fi, and Satellite. 

* OFDM is a variant of FDM

![](https://elele.team/upload/qFTex6.png)

* OFDM achieve interference mitigation by Orthogonality
* OFDM combines the signals so that they are orthogonal to each other.
* OFDM is a variant of FDM

![](https://elele.team/upload/yv7gRb.png)

OFDM would better utilize the available bandwidth, thus offering higher data transmission than FDM

### Code Division Multiplexing (CDM)
Code Division Multiplexing (CDM) shares a channel by assigning users with different orthogonal codes.

* Users’ signals are transmitted together over both time and frequency. 
* Widely used in 2G & 3G systems.

![](https://elele.team/upload/UrYXIf.png)

### Frequency Hopping
* In communication three major challenges exist: Interference, Jamming and interception

* Used for secure military communications

![](https://elele.team/upload/mUbnkK.png)









