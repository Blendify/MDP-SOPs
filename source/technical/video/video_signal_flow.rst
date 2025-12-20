Video Signal Flow
*****************

This SOP defines the standards and best practices for designing, verifying, documenting, and
maintaining **video signal flow** for all MP/RV events. Clear and intentional signal flow ensures
stable images, predictable switching, fast troubleshooting, and clean integration between video,
audio, lighting, and control systems.

If the signal path is unclear, the system is not ready.


Purpose
=======

- Ensure reliable video signal delivery from source to display.
- Prevent resolution, frame rate, and scaling mismatches.
- Standardize how video signal paths are designed and documented.
- Enable fast troubleshooting under show conditions.
- Support consistent workflows across operators and venues.


Who This SOP Is For
===================

- Video leads / V1s  
- Switcher and playback operators  
- Video technicians  
- Warehouse staff assisting with system prep  
- Project Managers overseeing video scope  
- Authorized freelancers  

Anyone configuring routing or signal paths must understand this SOP.


Scope
=====

This SOP applies to:

- Playback devices and media servers
- Camera systems
- Video switchers and routers
- Scalers and converters
- LED processors and projectors
- SDI, HDMI, and fiber signal paths
- Confidence monitors and auxiliary outputs


Video Signal Flow Principles
============================

All video systems must follow these principles:

- **Source → Control → Processing → Display**
- Minimize format conversions.
- Maintain consistent resolution and frame rate.
- Avoid unnecessary signal splitting.
- Document all non-standard routing.

Video failures are usually signal-flow failures.


Standard Signal Flow Overview
=============================

Typical MP/RV video signal flow:

1. Source (camera, playback, graphics)
2. Input cabling
3. Switcher or router
4. Scaler or processor (if required)
5. Distribution (DA or processor outputs)
6. Display devices (LED wall, projector, monitors)

Every step must be verified.


Input Stage
===========

- Verify source output format.
- Confirm cable type and integrity.
- Label inputs clearly.
- Test signal presence before routing.

Source issues propagate downstream.


Switcher & Router Stage
=======================

- Match input formats where possible.
- Verify switcher input assignments.
- Confirm program, preview, and aux outputs.
- Avoid routing loops or redundant paths.

Clear routing prevents confusion.


Scaling & Processing
====================

- Apply scaling only when necessary.
- Match display native resolutions.
- Manage EDID intentionally.
- Avoid cascading scalers.

Excess processing degrades image quality.


Distribution & Splitting
========================

- Use proper distribution amplifiers or processor outputs.
- Avoid passive splitting.
- Verify signal integrity at each output.
- Label all distribution paths.

Improper splitting causes signal loss.


Display Integration
===================

- Verify display input requirements.
- Confirm signal compatibility.
- Test full path from source to display.
- Verify sync between multiple displays.

Displays are the final verification point.


Auxiliary & Confidence Feeds
============================

- Define tap points clearly.
- Avoid affecting primary program output.
- Label feeds for operators and presenters.
- Test auxiliary outputs thoroughly.

Aux feeds must not compromise main output.


Testing & Verification
======================

- Test every signal path end-to-end.
- Use test patterns and known content.
- Verify resolution, frame rate, and color.
- Test backup paths if applicable.

Testing confirms design assumptions.


Documentation
=============

- Maintain signal flow diagrams when required.
- Document:
  - Input sources  
  - Routing decisions  
  - Processing steps  
  - Output assignments  
- Save switcher and processor files with notes.

Documentation supports consistency.


Changes During Show
===================

- Avoid structural signal flow changes mid-show.
- If changes are required:
  - Communicate clearly  
  - Document immediately  
- Restore standard routing post-show.

Unplanned changes increase failure risk.


Troubleshooting Signal Flow
===========================

When issues occur:

- Start at the source.
- Verify each stage sequentially.
- Check format compatibility.
- Swap components methodically.

Systematic troubleshooting saves time.


Roles & Responsibilities
========================

Video Leads / V1
----------------

- Design and approve signal flow.
- Verify routing and processing.
- Document system configuration.

Video Technicians
-----------------

- Assist with patching and testing.
- Follow approved signal paths.
- Report inconsistencies.

Warehouse Staff
---------------

- Support prep and documentation.
- Maintain standard templates.

Project Managers
----------------

- Understand signal flow implications for scope and staffing.


Quality Control
===============

- Signal flow verified before doors.
- Formats consistent across the system.
- Documentation complete.
- Issues reviewed post-show.

Clear signal flow prevents show failures.
