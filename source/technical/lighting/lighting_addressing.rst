Lighting Addressing
*******************

The Lighting Addressing SOP defines the standards and procedures for assigning DMX addresses, modes,
and universe mappings for all lighting fixtures used by Maryland Productions (MP) and Event
Revolution (RV). Correct addressing is critical to system stability, predictable programming, and
efficient troubleshooting.

This SOP applies to **all lighting fixtures**, including moving lights, static fixtures, LED bars,
and pixel-based systems.


Purpose
=======

- Standardize how fixtures are addressed and configured.
- Prevent address overlap and mode mismatches.
- Ensure addressing matches console profiles and documentation.
- Support efficient prep, programming, and on-site troubleshooting.
- Provide clear labeling standards for hung fixtures.


Scope
=====

This SOP applies during:

- Warehouse prep
- Console show file creation
- On-site installation
- Show operation
- Strike and reset


Addressing Fundamentals
=======================

DMX Basics
----------

- Each DMX universe contains **512 channels**.
- Fixtures consume a defined number of channels based on their mode.
- A fixture’s **starting address** determines which channels it occupies.
- Overlapping addresses are not permitted unless intentionally merged and documented.

Example:
- Fixture uses 16 channels
- Starting address = 001
- Channels used = 001–016


Universe Numbering
==================

- Universes are numbered sequentially starting at **Universe 1**.
- Do not skip universe numbers unless required by the system design.
- Universe numbering must be consistent across:
  - Console
  - Nodes
  - Fixtures
  - Documentation

Universe numbering changes must be approved by the PM or Lead Lighting Tech.


Mode Selection
==============

Mode Standards
--------------

1. Fixture mode must match the console profile exactly.
2. Use the **standard full-feature mode** unless otherwise specified.
3. Pixel fixtures must use the mode defined in the advance.
4. Disable unused modes such as:
   - Wireless DMX
   - Auto programs
   - Sound-active modes

Mode mismatches are one of the most common causes of on-site failures.


Address Assignment Rules
========================

General Rules
-------------

- Addresses must be assigned sequentially within each universe.
- Leave no gaps unless required by system design.
- Do not exceed channel 512.
- Never overlap addresses unless intentional and documented.

Preferred Workflow
------------------

1. Group fixtures by type and position.
2. Assign addresses starting at 001.
3. Increment addresses by channel count.
4. Move to the next universe when approaching channel limits.
5. Document assignments immediately.


Pixel & LED Addressing
======================

Pixel Fixtures
--------------

- Pixel fixtures may consume large channel counts.
- Verify pixel mapping mode (RGB, RGBW, etc.).
- Confirm orientation and pixel order.
- Assign pixel universes intentionally and document clearly.

Avoid mixing pixel fixtures and conventional fixtures on the same universe unless planned.


RDM Usage
=========

- RDM may be used only when:
  - All fixtures support it reliably
  - The network is stable
- Never use RDM on:
  - Mixed manufacturer chains without testing
  - Large pixel-heavy universes
- Disable RDM after addressing if stability is uncertain.


Labeling Requirements
=====================

Each fixture must be labeled with:

- Universe number
- Starting address
- Fixture ID or position
- Mode (if ambiguous)

Labels must be:
- Durable
- Legible when hung
- Placed consistently

Example Label:

```
U2 / 145
Mode: 16ch
DS Truss Spot 3
```


Documentation Standards
=======================

Addressing must be documented in:

- Console patch
- Advance packet
- Patch sheets
- Job notes (if changes occur)

Any addressing changes made on-site must be:
- Updated in the console
- Communicated to PM or Lead Tech
- Reflected in final documentation


Verification & Testing
======================

Warehouse Verification
----------------------

- Verify each fixture responds correctly at its assigned address.
- Test all parameters.
- Confirm no address conflicts.

On-Site Verification
--------------------

- Confirm addressing after hanging fixtures.
- Test each fixture individually.
- Resolve issues before focus begins.


Common Addressing Errors
========================

- Incorrect mode selected
- Address overlap
- Universe mismatch
- RDM conflicts
- Pixel mapping errors
- Address labels missing or incorrect


Troubleshooting
===============

If a fixture does not respond:

1. Confirm power.
2. Verify data path.
3. Check mode and address.
4. Confirm universe assignment.
5. Test with a known-good fixture or tester.

Never guess—verify systematically.
