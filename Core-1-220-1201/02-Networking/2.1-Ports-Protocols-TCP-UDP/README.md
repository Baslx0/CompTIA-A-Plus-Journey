# Objective 2.1 — Ports, Protocols, TCP and UDP

**Official objective:** Compare and contrast Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) ports, protocols, and their purposes.

## Resources

- Professor Messer
- Official CompTIA A+ 220-1201 objectives
- ExamCompass
- ChatGPT recall and troubleshooting practice

## TCP vs. UDP

**TCP** is connection-oriented and focuses on reliable delivery. It uses mechanisms such as acknowledgements, sequencing, and retransmission.

**UDP** is connectionless and has lower overhead, but it does not guarantee delivery.

## Common ports

| Protocol | Port |
| --- | ---: |
| FTP | 20/21 |
| SSH | 22 |
| Telnet | 23 |
| SMTP | 25 |
| DNS | 53 |
| DHCP | 67/68 |
| TFTP | 69 |
| HTTP | 80 |
| POP3 | 110 |
| NTP | 123 |
| NetBIOS | 137–139 |
| IMAP | 143 |
| SNMP | 161/162 |
| LDAP | 389 |
| HTTPS | 443 |
| SMB/CIFS | 445 |
| RDP | 3389 |

Useful transport reminders from my review:

- DHCP — UDP
- TFTP — UDP
- NTP — UDP
- SNMP — UDP
- DNS — can use TCP or UDP

## Validation

- ExamCompass: **100%**

## Key takeaway

Memorizing the port number is only part of the objective. It is more useful to connect the port to the service and understand whether the protocol needs TCP's reliability or UDP's lower overhead.
