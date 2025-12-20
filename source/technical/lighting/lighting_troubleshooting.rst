Lighting Troubleshooting
************************

The Lighting Troubleshooting SOP defines a structured, methodical approach to diagnosing and
resolving lighting system issues during prep, load-in, rehearsal, and show operation. Consistent
troubleshooting prevents panic-driven changes, reduces downtime, and ensures problems are resolved
safely and efficiently.

This SOP applies to all lighting-related issues involving fixtures, data, power, consoles, and
networking.


Purpose
=======

- Provide a repeatable process for diagnosing lighting problems.
- Minimize show disruption caused by technical failures.
- Prevent unsafe or unnecessary changes under pressure.
- Ensure issues are documented for post-show repair and improvement.
- Support clear communication between technicians, leads, and PMs.


Core Troubleshooting Principles
===============================

Always follow these principles:

- **Stay calm** – Panic causes mistakes.
- **Change one thing at a time** – Never shotgun fixes.
- **Verify assumptions** – Do not assume something is correct.
- **Start simple** – Power and data first.
- **Document issues** – Even if resolved quickly.
- **Escalate when needed** – Do not hide problems.


Troubleshooting Workflow
========================

Follow this order unless safety dictates otherwise:

1. **Safety Check**
2. **Power**
3. **Data**
4. **Addressing / Patch**
5. **Console / Network**
6. **Fixture Hardware**
7. **Environmental Factors**


1. Safety Check
================

Before touching anything:

- Ensure no exposed conductors.
- Verify fixtures are secure.
- Do not work on live power unless approved.
- Clear personnel from unsafe areas.

If the issue presents a safety risk, stop immediately and escalate.


2. Power Issues
===============

Common Symptoms
---------------

- Fixture not powering on
- Random resets
- Flickering output
- Breakers tripping

Checklist
---------

- Confirm circuit is energized.
- Verify correct voltage.
- Check connector seating.
- Inspect power cable for damage.
- Verify distro breaker status.
- Confirm load is not exceeding limits.

If power is unstable, **do not continue troubleshooting data** until resolved.


3. Data Issues
==============

Common Symptoms
---------------

- Fixture powers on but does not respond
- Intermittent response
- Erratic behavior

Checklist
---------

- Confirm data cable connection.
- Swap in a known-good cable.
- Verify correct protocol (DMX / Art-Net / sACN).
- Confirm node output is active.
- Check DMX termination if required.
- Bypass splitters to isolate the problem.

Always test with a single known-good fixture when isolating data issues.


4. Addressing & Patch
=====================

Common Symptoms
---------------

- Wrong fixture responding
- Multiple fixtures moving together
- No response on expected controls

Checklist
---------

- Verify fixture mode.
- Confirm starting address.
- Check universe assignment.
- Compare console patch to physical labels.
- Ensure no address overlap.

Addressing mismatches are the **most common** lighting issue—verify carefully.


5. Console & Network
====================

Common Symptoms
---------------

- Universes not outputting
- Network nodes offline
- Delayed or dropped response

Checklist
---------

- Verify output is enabled.
- Confirm correct IP addressing.
- Check subnet compatibility.
- Power-cycle nodes or switches if needed.
- Check for duplicate IP addresses.
- Confirm console software stability.

Do not update console software during troubleshooting unless approved.


6. Fixture Hardware
===================

Common Symptoms
---------------

- Mechanical noise
- Loss of pan/tilt accuracy
- Color wheel errors
- Gobo wheel stuck
- Overheating warnings

Checklist
---------

- Power-cycle the fixture.
- Inspect fans and vents.
- Check for physical obstructions.
- Reset fixture parameters if applicable.
- Swap fixture with a known-good unit if necessary.

Faulty fixtures should be removed from the rig if possible.


7. Environmental Factors
========================

Consider:

- Excessive heat
- Moisture or condensation
- Dust buildup
- Unstable power sources
- RF interference (for wireless systems)

Environmental issues often cause intermittent failures.


Escalation Guidelines
=====================

Escalate immediately if:

- A safety issue is identified
- Multiple fixtures fail simultaneously
- Power distribution behaves abnormally
- The issue threatens show continuity
- You are unsure how to proceed safely

Escalation path:
1. Crew Lead  
2. Lead Lighting Tech / Programmer  
3. Project Manager or TD  


Documentation Requirements
==========================

All significant issues must be documented:

- Fixture or system affected
- Symptoms observed
- Steps taken
- Resolution (if found)
- Items needing repair or replacement

Documentation should be entered into:
- Job notes
- Repair intake system
- Post-show report


Common Mistakes to Avoid
========================

- Making multiple changes at once
- Ignoring power warnings
- Skipping address verification
- Hot-swapping non-rated connectors
- Blaming the console without evidence
- Failing to document resolved issues


Post-Show Follow-Up
===================

After the event:

- Tag affected equipment.
- Route to repair or maintenance.
- Update SOPs if a recurring issue is identified.
- Review troubleshooting notes with the team.

Lessons learned should improve future shows.
