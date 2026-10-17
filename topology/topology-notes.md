# SOHO Network Topology

## Overview

The network serves three departments using one Cisco router and one central Cisco switch.

## Network Devices

- One Cisco 2901 router
- One Cisco switch
- Three wireless access points
- End devices including PCs, laptops, smartphones, printers, and a tablet

## Department Segmentation

| Department                 | VLAN |
| -------------------------- | ---: |
| Admin/IT                   |   10 |
| Finance/HR                 |   20 |
| Customer Service/Reception |   30 |

## Routing Design

Router-on-a-stick will be used to route traffic between VLANs through one physical router interface with three 802.1Q subinterfaces.

## Wireless Design

Each department will have its own wireless network associated with its respective VLAN.

## Diagram

See `soho-network-topology.png`.
