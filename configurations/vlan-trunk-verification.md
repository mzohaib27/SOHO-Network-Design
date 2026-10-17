# Stage 02 — VLAN and Trunk Verification

## Objective

Configure VLANs 10, 20, and 30 and prepare the switch-to-router link for 802.1Q trunking.

## Configuration

- Switch hostname: SOHO-SW1
- Router uplink: FastEthernet0/1
- VLAN 10: ADMIN_IT
- VLAN 20: FINANCE_HR
- VLAN 30: CUSTOMER_SERVICE
- Trunk allowed VLANs: 10, 20, 30

## Verification Results

| Test                  | Command                  | Result | Notes                           |
| --------------------- | ------------------------ | ------ | ------------------------------- |
| VLAN creation         | `show vlan brief`        | Pass   | Record actual output            |
| Trunk configuration   | `show interfaces trunk`  | Pass   | Record actual output            |
| Interface status      | `show interfaces status` | Pass   | Check connected ports           |
| Configuration review  | `show running-config`    | Pass   | Check VLAN and port settings    |
| Startup configuration | `show startup-config`    | Pass   | Confirm configuration was saved |

## Evidence

Store relevant Packet Tracer screenshots in `05-testing/screenshots/`.

Suggested filenames:

- `stage02-vlan-brief.png`
- `stage02-trunk-status.png`
- `stage02-interface-status.png`

## Notes and Issues

Document any incorrect port assignments, disconnected interfaces, or trunking problems encountered during verification.

## Stage Status

Pending verification.
