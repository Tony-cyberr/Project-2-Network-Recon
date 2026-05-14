# Wireshark Observations

## Capture Details
- Capture interface: bridge100
- Capture file: pcaps/nmap-scan-capture.pcapng
- Target IP address: 192.168.64.2
- Tool used to generate traffic: Nmap

## Traffic Observed
During the capture, Wireshark showed network traffic between the MacBook Pro and the Ubuntu-SOC-Lab VM.

Observed traffic included:
- ARP traffic used to identify devices on the local network
- TCP traffic related to the Nmap scan
- SSH-related traffic because port 22 was open on the target VM
- Background local network traffic such as mDNS and IPv6 messages

## Explanation
Wireshark captured packets while Nmap scanned the Ubuntu VM. This helped confirm that the scan created real network traffic and that the target VM responded to the scan.

## Key Takeaway
The packet capture supports the Nmap findings by showing network communication between the analyst machine and the target VM during the scan.
