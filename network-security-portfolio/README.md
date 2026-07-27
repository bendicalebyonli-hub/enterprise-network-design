# Network & Security Portfolio

Hands-on projects in enterprise network design and security operations,
built in Cisco Packet Tracer and a self-hosted security lab.

## Projects

### 1. Enterprise Network Design
`/network-design`

A multi-floor campus network simulation featuring:
- Dual-ISP internet edge with redundant perimeter firewalls (OSPF-based failover)
- Redundant core switching with HSRP gateway redundancy
- VLAN-segmented access layer across 3 floors / 5 departments
- DMZ / server farm with ACL-based traffic filtering
- Dynamic NAT/PAT across both firewalls
- LACP EtherChannel link aggregation between core switches
- Cisco CME-based VoIP (IP telephony) deployment
- WLC-managed enterprise wireless

📄 Full write-up: [`Enterprise_Network_Design_Portfolio.docx`](./network-design/Enterprise_Network_Design_Portfolio.docx)

### 2. Security Operations Home Lab
`/security-operations`

A self-hosted blue-team lab covering the reconnaissance/detection/analysis
lifecycle. Currently documents a full internal vulnerability assessment:
- Nmap-based scanning (SYN scan, full port scan, service/OS detection, NSE vuln scripts)
- CVE-mapped findings (outdated web server, Slowloris DoS, SMB/RDP exposure, IoT risk)
- Management-facing risk dashboard
- Prioritized remediation roadmap (immediate / short-term / long-term)

Additional modules (pfSense, Snort, Wireshark, Splunk, GoPhish) are in progress
and will be added as each is documented.

📄 Full write-up: [`Security_Operations_Home_Lab_Portfolio.docx`](./security-operations/Security_Operations_Home_Lab_Portfolio.docx)

## Contact: +226 71 78 28 92

Bendi Caleb Yonli
