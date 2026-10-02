# CMPG325-2026-021 – Marumo Hardware & Building Supplies (Taung)

**Student:** KH02A, Shakes
**Student Number:** 44833563
**Project ID:** CMPG325-2026-021

## Project Overview
Network design and simulation for Marumo Hardware & Building Supplies, a retail hardware store in Taung.

## Key Features
- VLAN segmentation (POS, Office, Printer, Server)
- Internal DNS name resolution (marumo.local)
- Shared printer zone (CR8) for two departments
- POS redundancy — stays online if office LAN fails

## Repository Structure
- `packet-tracer/` — Working .pkt file
- `diagrams/` — Physical and logical topology diagrams
- `documentation/` — Requirements, IP plan, evidence
- `screenshots/` — Testing and configuration evidence
- `configs/` — Device configuration exports

## How to Open
1. Open `packet-tracer/marumo-hardware-network.pkt` in Cisco Packet Tracer 8.2+
2. Wait 30–60 seconds for STP convergence
3. Verify connectivity using the tests in `documentation/`