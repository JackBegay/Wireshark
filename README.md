# Wireshark

## Objective
In the given scenario I was tasked as a security analyst to investigate traffic to a website. I analyzed a network packet capture file containing traffic data about users connecting to an interal site.  I had to filter through data to identify the source and destination IP addresses involed in the web browser session, examine which protocols were being used in making a connection to the site, and analyze data packets to identify what types of information were sent and received by the systems that were connected when the packets were captured. 

### Skills Learned

- Advanced understanding of using Wireshark to inspect activity on a network
- Proficiency in analyzing different data packets and their source and destination IP addresses
- Ability to filter through packets based on their IP address, MAC address, communication protocol, or port number 
- Enhanced knowledge of hig-level packet data like the DNS that was queried, time to live, and frame length

### Tools Used

- Utilized virtualization software VMware 
- Kali linux installed on Vmware
- Wireshark installed on kali linux

## Steps
1. First I had to load the file sample.pcap on wireshark

2. Once loaded I had to search for any traffic coming from the source IP address, 142.250.1.139, with the command   ip.src == 142.250.1.139  . This pulled up a list of results for traffic with the associated source IP address.
![Screenshot 2025-04-15 152605](https://github.com/user-attachments/assets/9ad01d9f-4b67-4e75-9f45-aeb2941318d5)

3.Next I had to search for any traffic with the same IP address, but this time for it being the destination. Accomplished this through the command   ip.dst == 142.250.1.139  to find any results for that being the destination IP address.
![Screenshot 2025-04-15 152656](https://github.com/user-attachments/assets/0ca47c77-5a63-470e-878f-2058ed301e03)

4.

