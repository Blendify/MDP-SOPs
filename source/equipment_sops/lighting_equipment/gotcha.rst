
**************************
Lighting Equipment Gotchas
**************************

This page documents **known quirks, limitations, and non-obvious behaviors** of lighting equipment
used by Maryland Productions (MP) and Event Revolution (RV). These are not failures, but *operational
idiosyncrasies* that can cause confusion, wasted time, or incorrect assumptions if not understood.

This page exists to prevent repeat mistakes and speed up troubleshooting in prep and on-site.


Purpose
=======

- Capture non-obvious behaviors of lighting equipment.
- Prevent incorrect assumptions during prep and show setup.
- Reduce troubleshooting time caused by known quirks.
- Share institutional knowledge across technicians and freelancers.
- Serve as a living reference for lessons learned.


Who This Page Is For
====================

- Lighting technicians  
- Lighting leads / LDs  
- Warehouse prep staff  
- Project Managers reviewing lighting scope  
- Freelancers unfamiliar with MP/RV inventory  

Anyone working with MP/RV lighting gear should review this page.


Important Notes
===============

- These are **known behaviors**, not defects.
- Do not assume all units of the same model behave identically.
- Always test *your specific unit* when behavior matters.
- When in doubt, document new findings and add them here.

If a gotcha causes real risk, it should also appear in the relevant SOP.


Known Lighting Equipment Gotchas
================================

Cameo SP5 Fixtures
------------------

Wireless DMX Compatibility
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Wireless DMX Compatibility**
- Cameo SP5 units support **Wireless DMX via G5 W-DMX**.
- Not all SP5 units behave identically with regard to DMX passthrough.

**Critical Gotcha**

- Only **some SP5 units pass W-DMX signal through the physical DMX output**.
- Other units will:

  - Receive W-DMX correctly
  - Output **no DMX** on the wired DMX port

**Implications**
- You cannot assume SP5 fixtures will act as a wireless-to-wired bridge.
- Daisy-chaining wired fixtures downstream of an SP5 may silently fail.
- Mixed behavior can occur within the same batch of fixtures.

**Best Practices**
- Never rely on SP5 fixtures for W-DMX passthrough.
- Use dedicated W-DMX receivers for wired downstream fixtures.
- Test passthrough behavior during prep if attempting hybrid setups.
- Clearly label any units confirmed to pass W-DMX (if kept in inventory).

This is expected behavior for this model and firmware combination.


Dimming Behavior Inconsistency
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Observed Behavior**
- Cameo SP5 fixtures exhibit **inconsistent dimming response between units**.
- Differences may appear in:

  - Low-end fade smoothness  
  - Perceived brightness at identical DMX values  
  - Response curve near 0–20%  

Two fixtures set to the same intensity value may not visually match.


**Implications**
- Smooth fades may appear uneven across a group of SP5s.
- Low-intensity looks can expose unit-to-unit variation.
- Matched intensity cues may look inconsistent on camera.
- Programming by eye on one fixture may not translate cleanly to others.


**Contributing Factors (Suspected)**
- Firmware differences between units
- Internal calibration variance
- LED binning tolerances

These variations have been observed even when fixtures appear externally identical.

**Best Practices**
- Avoid relying on SP5s for critical low-end fades.
- Do not use for film critical work.
- Test dimming response during prep, especially for theatrical or camera-facing looks.
- Use **grouped programming** and visual balancing where possible.
- Consider applying:

  - Console-level dimmer curves  
  - Per-fixture intensity offsets

- Do not assume dimming behavior is consistent across the fleet.

**Programming Guidance**
- Treat SP5 dimming as *acceptable but not precision-matched*.
- For applications requiring extremely smooth or matched fades:

  - Test carefully
  - Or consider alternate fixture choices


This behavior is considered a **known characteristic** of the SP5 units in inventory and should be
accounted for during design and programming.


Mixed Firmware Behavior (General)
---------------------------------

- Identical fixture models may have:
  - Different firmware versions
  - Different default personalities
- Behavior may vary between units even if externally identical.

**Best Practices**
- Standardize firmware where possible.
- Verify DMX modes during prep.
- Do not assume mode consistency across the fleet.


Wireless DMX Is Not Transparent
-------------------------------

- Wireless DMX systems do **not** always behave like a wired cable.
- Some fixtures:
  - Receive wireless DMX
  - Do not forward it
  - Or require explicit configuration to do so

**Best Practices**
- Treat wireless DMX as an endpoint unless explicitly documented otherwise.
- Use dedicated transmitters and receivers.
- Avoid hybrid chains without testing.


Fixture Power-On Defaults
-------------------------

- Some fixtures:
  - Default to last-used mode
  - Default to a manufacturer demo mode
  - Require manual confirmation to enable DMX

**Best Practices**
- Power-cycle and verify control mode during prep.
- Never assume DMX mode persists across power loss.


RDM Behavior Is Inconsistent
----------------------------

- RDM support varies widely across fixture models.
- Some fixtures:
  - Respond inconsistently
  - Drop off RDM discovery
  - Misreport parameters

**Best Practices**
- Use RDM cautiously.
- Do not rely on RDM for mission-critical addressing unless verified.
- Fall back to manual addressing when necessary.


Passthrough Assumptions Are Dangerous
-------------------------------------

- DMX passthrough is **not guaranteed**, even if a fixture has:
  - DMX In
  - DMX Out
- Wireless + wired passthrough is especially inconsistent.

**Best Practices**
- Never assume passthrough without testing.
- Label known-safe passthrough devices.
- Use opto-splitters or nodes when reliability matters.


Operational Lessons Learned
===========================

- If a lighting setup feels “almost right,” it probably is.
- Silent failures often indicate passthrough or mode assumptions.
- Test edge cases during prep, not on-site.
- Document anything unexpected immediately.

Institutional memory prevents repeated mistakes.


How to Add New Gotchas
======================

When a new behavior is discovered:

1. Confirm it is repeatable.
2. Identify affected models and firmware if possible.
3. Document:
   - What was expected  
   - What actually happened  
   - How to avoid it  
4. Add it to this page.
5. Notify warehouse and department leads.

This page should evolve continuously.


Related Documentation
=====================

- Lighting Prep SOP
- Lighting Addressing SOP
- Lighting Networks SOP
- Lighting Troubleshooting SOP
- Equipment SOPs Overview
