Lighting Networks
*****************

The Lighting Networks SOP defines the standards and procedures for designing, deploying, and
maintaining lighting control networks for Maryland Productions (MP) and Event Revolution (RV).
Reliable networking is critical for stable DMX transport, console communication, and modern
multi-universe lighting systems.

This SOP applies to all lighting control networks, including DMX512, Art-Net, and sACN-based systems.


Purpose
=======

- Standardize lighting network design across all jobs.
- Ensure reliable and predictable data delivery.
- Prevent network-related show failures.
- Provide clear rules for configuration, labeling, and troubleshooting.
- Support scalable systems from small rentals to large productions.


Scope
=====

This SOP applies to:

- Lighting consoles
- Network switches
- DMX nodes and gateways
- Art-Net and sACN networks
- DMX splitters and distribution
- Network cabling and accessories


Control Protocols
=================

The following protocols may be used:

- **DMX512** – Traditional serial DMX over XLR.
- **Art-Net** – Ethernet-based DMX transport.
- **sACN (E1.31)** – Ethernet-based DMX transport (preferred for large systems).

sACN is the default protocol for:
- Multi-universe systems
- Managed networks
- Installations requiring multicast stability

Art-Net may be used for:
- Small systems
- Legacy equipment
- Direct console-to-node configurations


Network Topology
================

Approved Topologies
-------------------

- **Star topology** (preferred)
- **Tree topology** (managed switches only)

Avoid:
- Daisy-chaining switches
- Looped networks without proper management
- Mixing lighting control with unrelated network traffic


Switch Standards
================

- Use managed switches for systems larger than 4 universes.
- Label all switches with:
  - Job name
  - IP range
  - VLAN or network purpose (if applicable)
- Disable unused ports when possible.
- Avoid consumer-grade unmanaged switches for complex systems.

Lighting networks must remain isolated from:
- Audio networks
- Video networks
- Internet access
- Guest Wi-Fi


IP Addressing Standards
=======================

Default Scheme
--------------

- Consoles: Static IP (documented)
- Nodes: Static IP or DHCP reservation
- Subnet: /24 unless otherwise required

Example:
- Console: 10.101.1.10
- Nodes: 10.101.1.100–199
- Subnet: 255.255.255.0

All IP schemes must be documented in the advance packet.


Universe Mapping
================

- Each universe must be clearly mapped:
  - Console → Protocol → Node → Output → Fixtures
- Universe numbers must match:
  - Console configuration
  - Node settings
  - Fixture addressing
  - Documentation

Avoid reusing universe numbers across protocols unless intentionally merged and documented.


DMX Distribution
================

DMX Output Rules
----------------

- Do not exceed manufacturer limits for DMX chain length.
- Use DMX splitters for:
  - Long runs
  - Multiple branches
  - Redundancy
- Use terminators at the end of DMX chains when required.

Cable Standards
---------------

- Use proper DMX-rated cable (110–120 ohm).
- Do not substitute microphone cable for long DMX runs.
- Label DMX cables by length and type.


Node Configuration
==================

- Label each node with:
  - Universe assignments
  - Output port numbers
- Verify firmware versions before deployment.
- Test each output port during prep.
- Document:
  - IP address
  - Protocol
  - Universe range
  - Physical location (e.g., FOH, US truss)


Redundancy & Best Practices
===========================

- Use primary and backup consoles when required.
- Avoid single points of failure.
- Keep spare network cables and nodes available.
- Avoid unnecessary protocol conversion.
- Test the full network before focus.


Testing & Verification
======================

Warehouse Testing
-----------------

- Verify console communicates with all nodes.
- Test each universe output.
- Confirm fixture response on all ports.
- Monitor for packet loss or latency issues.

On-Site Testing
---------------

- Verify IP addresses after setup.
- Confirm switches and nodes boot correctly.
- Test each universe before focus.
- Observe for flicker or dropped data.


Common Failure Points
=====================

- IP conflicts
- Incorrect subnet masks
- Mixed protocols without proper configuration
- Unlabeled nodes or ports
- Damaged Ethernet cables
- Overloaded switches


Safety Considerations
=====================

- Secure network equipment away from foot traffic.
- Use strain relief on network cables.
- Avoid running Ethernet parallel to high-voltage power where possible.
- Keep network gear dry and protected.
