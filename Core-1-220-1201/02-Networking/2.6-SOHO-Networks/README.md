# Objective 2.6 — SOHO Networks

**Official objective:** Given a scenario, configure basic wired/wireless small office/home office (SOHO) networks.

## Resources

- Professor Messer
- Official CompTIA A+ 220-1201 objectives
- ExamCompass
- ChatGPT troubleshooting practice

## IPv4 addressing

Private IPv4 ranges:

- `10.0.0.0/8`
- `172.16.0.0/12`
- `192.168.0.0/16`

Private addresses are used inside local networks and are not routed directly across the public Internet.

## APIPA

Windows can assign an address in the **169.254.0.0/16** range when it cannot obtain normal configuration from DHCP.

Seeing a `169.254.x.x` address is therefore a useful troubleshooting clue for a DHCP/connectivity problem.

## Static vs. dynamic

- **Static:** manually configured and intended to remain fixed.
- **Dynamic:** assigned automatically, usually by DHCP, and is not guaranteed to stay the same.

## Subnet mask and default gateway

The **subnet mask** helps a device determine whether a destination is on the local network.

If the destination is on another network, traffic is normally sent to the **default gateway**.

Two devices on the same local subnet can communicate directly without sending their traffic through the default gateway.

## Validation

- ExamCompass IP Addressing Quiz: **100%**

## Key takeaway

IP troubleshooting starts by checking whether the device has a valid address, mask, and gateway before moving farther up the troubleshooting path.
