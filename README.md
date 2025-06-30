# Elevate-labs-Task-5
#  Wireshark Packet Capture

## 📄 Summary
Captured live network traffic using Wireshark while:
- Pinging a server (e.g., ping google.com)
- Visiting websites using curl or a browser

The capture includes common network protocols like ICMPv6, DNS, and TCP.

---

## 🔍 Protocols Identified

### 1. *ICMPv6 (Internet Control Message Protocol for IPv6)*
- *Purpose*: Used for diagnostics and error reporting in IPv6 networks.
- *Captured While*: Running ping commands to IPv6-enabled servers.
- *Example Packet*: Echo Request and Echo Reply for testing connectivity.

### 2. *DNS (Domain Name System)*
- *Purpose*: Resolves domain names like google.com to IP addresses.
- *Captured While*: Running ping and browsing websites.
- *Example Packet*: Query type A or AAAA for domain lookups.

### 3. *TCP (Transmission Control Protocol)*
- *Purpose*: Provides reliable, ordered delivery of data for applications.
- *Captured While*: Browsing or using curl https://example.com.
- *Example Packet*: SYN, SYN-ACK (part of 3-way handshake), and data transfer packets.

---

## 📁 Files Included
- capture.pcap – The Wireshark packet capture file.
- README.md – This report summarizing the captured traffic and analysis.

---

## 🎯 Outcome
- Gained hands-on experience in capturing real-time traffic with Wireshark.
- Learned to identify and filter key protocols.
- Practiced basic network troubleshooting and protocol analysis.

---

## 📎 References
- [Wireshark Protocol Guide](https://wiki.wireshark.org/ProtocolReference)
- [ICMPv6 Explained](https://www.cloudflare.com/learning/ddos/glossary/internet-control-message-protocol/)
- [What is DNS](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [How TCP Works](https://www.cloudflare.com/learning/ddos/glossary/transmission-control-protocol-tcp/)
