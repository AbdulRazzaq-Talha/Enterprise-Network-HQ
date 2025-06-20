**VLAN Plan for Enterprise Multi-Site Network (HQ Site)**

| VLAN ID | Department     | Subnet             | Default Gateway | Description                          |
|---------|----------------|--------------------|------------------|--------------------------------------|
| 10      | HR             | 10.0.10.0/24       | 10.0.10.1        | Human Resources department VLAN      |
| 20      | IT             | 10.0.20.0/24       | 10.0.20.1        | IT department VLAN                   |
| 30      | Finance        | 10.0.30.0/24       | 10.0.30.1        | Finance department VLAN              |
| 40      | Guest          | 10.0.40.0/24       | 10.0.40.1        | Guest wireless VLAN with restrictions|
| 50      | Admin          | 10.0.50.0/24       | 10.0.50.1        | Administration VLAN                  |
| 99      | Management     | 10.0.99.0/24       | 10.0.99.1        | Management VLAN & network control    |

**Device IP Assignment (HQ Site)**

- **Router 1**:
  - Inside: `10.0.0.1/24`
  - Outside (Cloud/ISP): `203.0.113.1/30`

- **Router 2**:
  - Inside: `10.0.1.1/24`
  - Outside (Cloud/ISP): `203.0.114.1/30`

- **Core Switch**:
  - Uplinks to Router 1 (Gi0/1) and Router 2 (Gi0/2)

- **Access Switch**:
  - VLAN interfaces for DHCP, DNS, Syslog servers and PCs

- **Servers (DHCP/DNS/Syslog)**:
  - DHCP: `10.0.99.10`
  - DNS: `10.0.99.20`
  - Syslog: `10.0.99.30`

- **PCs**:
  - Auto-assigned via DHCP within their respective VLANs

**Coming Up**
- Branch A and Branch B VLAN plans
- VPN setup
- Redundancy
- ACLs and security
- Cloud simulation (public web, DNS)


