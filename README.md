# arp_detector
This Python script serves as a simple ARP (Address Resolution Protocol) detector, designed to identify potential ARP spoofing attacks on a local network. ARP spoofing is a technique where an attacker sends fake or "spoofed" ARP messages to associate their MAC address with the IP address of a legitimate device on the network, redirecting traffic through the attacker's system.
1. The script utilizes the powerful Scapy library to analyze ARP packets on the network.
2. It extracts and compares MAC addresses associated with IP addresses in ARP packets to identify potential discrepancies.
3. The detector operates in real-time, sniffing network traffic and raising an alert if a potential ARP spoofing attack is detected.
