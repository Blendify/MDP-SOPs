Lighting Console & Show Files
*****************************

The Lighting Console & Show Files SOP defines the standards and procedures for preparing, configuring,
operating, and maintaining lighting consoles and show files for Maryland Productions (MP) and Event
Revolution (RV). Consistent console practices ensure reliable system behavior, predictable
programming, and smooth handoffs between programmers and operators.

This SOP applies to all lighting control surfaces, consoles, playback systems, and show files used
on MP/RV productions.


Purpose
=======

- Standardize console setup and show file structure.
- Prevent show failures caused by corrupted or mismatched files.
- Ensure consistency across programmers and operators.
- Support efficient prep, programming, and on-site operation.
- Provide clear rules for backing up and documenting changes.


Scope
=====

This SOP applies to:

- Lighting consoles (MA, Onyx, Chamsys, etc.)
- Playback controllers and wings
- Offline editors used for show prep
- Show files and backups
- Console networking and output configuration


Console Preparation
===================

Hardware Setup
--------------

Before programming or deployment:

1. Inspect the console for physical damage.
2. Verify power supplies and cables are in good condition.
3. Confirm output ports (DMX, network) are functional.
4. Verify correct voltage selection if applicable.
5. Connect required peripherals:
   - Monitors  
   - Keyboards  
   - Mice  
   - Network adapters  

Any hardware issues must be addressed before show file prep.


Software & Firmware
===================

- Verify console software version.
- Do not update software within 72 hours of a show unless approved.
- Confirm fixture libraries are compatible with the software version.
- Document software versions in the job notes if non-standard.

Firmware consistency is critical for predictable behavior.


Show File Standards
===================

File Naming Convention
----------------------

Use a consistent naming format:

``YYYY-MM-DD_EventName_Venue_LD_v01.show``


Increment version numbers for each major change.

Template Usage
--------------

- Start from a known, approved template when possible.
- Templates should include:
  - Default views
  - Basic groups
  - Network and output configuration
- Avoid starting from old or unrelated show files.

Patch & Labeling
----------------

- Patch must match:
  - Fixture modes
  - Addressing
  - Universe assignments
- Label fixtures clearly using:
  - Type  
  - Position  
  - ID  

Example: ``SPOT_DS_TRUSS_03``



Programming Practices
=====================

- Use consistent group naming.
- Organize cues logically.
- Label all cues and pages.
- Avoid hard-coded values unless necessary.
- Use palettes and presets where possible.

Readable programming supports quick fixes under pressure.


Output Configuration
====================

- Verify output protocol (sACN, Art-Net, DMX).
- Confirm universe mapping.
- Test output to nodes or fixtures during prep.
- Disable unused outputs.

Always test physical output before leaving the warehouse.


Backup & Redundancy
===================

Backup Requirements
-------------------

- Save backups:
  - On console internal storage  
  - On external USB drive  
  - In the job folder (cloud or server)  

Backup Schedule
---------------

- Before leaving the warehouse
- After on-site changes
- At the end of each show day

Label backups clearly with date and version.


On-Site Operation
=================

- Load the correct show file before power-up.
- Verify patch and output after setup.
- Keep backup console or playback system available when required.
- Document any changes made on-site.

Avoid last-minute structural changes unless necessary.


Handoff Between Programmers
===========================

When multiple programmers are involved:

- Communicate file versions clearly.
- Do not overwrite another programmer’s file without approval.
- Use versioned backups.
- Document handoff notes in the job file.

Clear handoffs prevent confusion and data loss.


Shutdown & Storage
==================

After the show:

1. Save the final show file.
2. Create a final backup.
3. Power down the console properly.
4. Disconnect peripherals carefully.
5. Pack console and accessories securely.

Never pack a console while powered on.


Common Console Issues

- Incorrect fixture profiles
- Mismatched software versions
- Output protocol errors
- Network misconfiguration
- Corrupted show files

Address issues methodically—never panic-edit.


Safety Considerations
=====================

- Keep liquids away from consoles.
- Secure consoles to prevent tipping.
- Use proper power conditioning.
- Avoid cable strain on ports.

Consoles are mission-critical assets—handle with care.
