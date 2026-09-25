# Objective 2.4 — Network Configuration Concepts

**Official objective:** Explain common network configuration concepts.

## Resources

- Professor Messer
- Official CompTIA A+ 220-1201 objectives
- ExamCompass
- ChatGPT clarification and practice

## DNS records

- **A:** hostname → IPv4 address
- **AAAA:** hostname → IPv6 address
- **CNAME:** alias hostname → another hostname
- **MX:** identifies mail servers for a domain
- **TXT:** stores text data used for verification and other purposes

Email-related DNS concepts:

- **SPF:** identifies authorized sending servers/IPs.
- **DKIM:** uses a digital signature so recipients can verify message authenticity/integrity.
- **DMARC:** defines policy/reporting around SPF and DKIM results.

A useful distinction:

- **A:** hostname → IPv4
- **PTR:** IP address → hostname

## DHCP

DHCP automatically provides network configuration to clients.

The basic exchange is:

**Discover → Offer → Request → Acknowledge**

I remember this as **DORA**.

Important concepts:

- **Scope:** pool/range of addresses DHCP can assign.
- **Lease:** temporary right to use an assigned address.
- **Reservation:** DHCP gives a particular client a specific address.
- **Exclusion:** addresses inside the scope that DHCP should not automatically hand out.

### Static IP vs. DHCP reservation

Both can result in a device keeping the same address, but they work differently.

- **Static IP:** configured directly on the endpoint.
- **DHCP reservation:** configured on the DHCP server; the client still depends on DHCP.

## VLAN

A **VLAN** logically separates devices into different broadcast domains even when they share physical switching infrastructure.

## VPN

- **Site-to-site:** network ↔ network
- **Client-to-site:** individual user/device ↔ organization network

## Validation

- ExamCompass: **93.33%**

## Key takeaway

This objective connects several services that control how devices are identified, addressed, segmented, and connected across a network.
