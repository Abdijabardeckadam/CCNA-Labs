# Basic Network Setup Lab

## Lab Description

This lab demonstrates the design and configuration of a basic Cisco network topology using Cisco Packet Tracer.

The goal of this lab is to build a small LAN environment, connect network devices, configure IP addressing, and verify communication between devices.

This practice helps develop fundamental CCNA 200-301 networking skills, including device configuration, IPv4 addressing, and troubleshooting basic connectivity issues.

---

## Lab Objectives

By completing this lab, you will learn how to:

- Create a basic network topology
- Connect Cisco networking devices
- Configure router and switch settings
- Assign IPv4 addresses to end devices
- Configure device interfaces
- Enable network interfaces
- Test connectivity between devices
- Verify successful communication using network commands

---

## Network Devices Used

- Cisco Router
- Cisco Switch
- PCs (End Devices)
- Copper Ethernet Cables

---

## Configuration Tasks

The following configurations were performed:

### Router Configuration

- Set device hostname
- Configure router interfaces
- Assign IPv4 addresses
- Enable interfaces using `no shutdown`
- Verify interface status

### Switch Configuration

- Set switch hostname
- Configure basic switch settings
- Assign management IP address
- Verify switch connectivity

### PC Configuration

- Configure IPv4 address
- Configure subnet mask
- Configure default gateway
- Test communication with other devices

---

## IP Addressing

Example addressing scheme:

| Device | Interface | IP Address |
|---|---|---|
| Router | G0/0 | 192.168.1.1 |
| PC-1 | Ethernet | 192.168.1.10 |
| PC-2 | Ethernet | 192.168.1.20 |

Subnet Mask:
255.255.255.0


---

## Verification Commands

Commands used to verify the configuration:

### Check Interface Status
show ip interface brief


### Check Running Configuration
show running-config


### Test Connectivity
ping <destination-ip>


---

## Skills Practiced

- Cisco IOS command-line interface (CLI)
- Basic router configuration
- Basic switch configuration
- IPv4 addressing
- Network troubleshooting
- Connectivity testing

---

## Lab Files
Basic-Network-Setup.pkt

Cisco Packet Tracer project file containing the complete lab topology and configurations.
Network topology diagram showing device connections.

Documentation and explanation of the lab.

---

## Conclusion

This lab provides a foundation for understanding Cisco networking concepts. It introduces basic device configuration, IP addressing, and connectivity testing, which are essential skills for progressing through the CCNA learning path.
