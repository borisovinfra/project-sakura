# Node Inventory

## Sakura

Platform:
- Keenetic Giga

Role:
- Policy Engine
- Routing Control

---

## Russinka

Role:
- Transport / Relay Node

Services:
- SSH
- Xray Relay
- Mita
- Mieru

Status:
- Production

---

## Pearl

Role:
- Edge / Security Node

Services:
- Xray
- Unbound DNS
- WARP
- AmneziaWG
- Mita
- Fail2Ban
- SSH

Status:
- Production

---

## Design Principle

Sakura controls policy.

Russinka transports traffic.

Pearl provides edge connectivity and security services.

Node responsibilities are intentionally separated.
