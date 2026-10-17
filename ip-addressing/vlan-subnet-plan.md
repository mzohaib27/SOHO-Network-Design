# VLAN and IPv4 Subnet Plan

Base network: 192.168.1.0

Subnet mask: 255.255.255.192 (/26)

| Department                 | VLAN | Network          | Gateway       | Broadcast     |
| -------------------------- | ---: | ---------------- | ------------- | ------------- |
| Admin/IT                   |   10 | 192.168.1.0/26   | 192.168.1.1   | 192.168.1.63  |
| Finance/HR                 |   20 | 192.168.1.64/26  | 192.168.1.65  | 192.168.1.127 |
| Customer Service/Reception |   30 | 192.168.1.128/26 | 192.168.1.129 | 192.168.1.191 |

Each /26 subnet contains 64 total addresses and 62 usable host addresses.

The remaining subnet, 192.168.1.192/26, is reserved for potential future expansion.
