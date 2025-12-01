Scanning & Asset Control
************************

The Scanning & Asset Control workflow ensures that all equipment entering or leaving the warehouse
is properly tracked using Flex (for RV assets) and Current RMS (for MP assets). Accurate scanning is
critical for inventory reliability, preventing losses, and ensuring clear ownership between MP and
RV assets during all stages of job prep, transport, and return.

This SOP standardizes how equipment is scanned for **pulls, staging, loading, returns, and
maintenance**, ensuring a consistent and auditable trail for every asset movement.


Purpose
=======

- Maintain accurate inventory availability.
- Track MP vs RV ownership for financial reporting.
- Prevent losses, misplacements, and unreturned gear.
- Support real-time updates to job status and equipment readiness.
- Create a consistent workflow for all warehouse and logistics staff.


Responsibilities
================

Warehouse Staff
   - Perform all equipment scanning during pulls, staging, and returns.
   - Verify asset numbers, condition, and correct system assignment.
   - Document exceptions, substitutions, and discrepancies.

Drivers & Crew Leads
   - Confirm scanned gear matches the loaded equipment.
   - Report missing or unscanned items during load and unload.

Project Managers
   - Ensure job builds in Flex / Current RMS accurately reflect equipment lists.
   - Approve substitutions or last-minute gear changes.

Repair Technicians
   - Scan gear into maintenance status when repairing or testing.
   - Return repaired gear to inventory using the correct system process.


Required Tools
==============

- Flex mobile app or scanner (RV assets)
- Current RMS picking/scanning interface (MP assets)
- Barcode scanners or mobile devices
- Network access (Wi-Fi or mobile data)
- PPE as required (gloves, steel-toe shoes)
- Handheld radios (optional)


Procedure
=========

1. Identify Asset Ownership
---------------------------

Before scanning any item:

1. Check the barcode prefix:
   - **MP-xxxx** → Maryland Productions asset (Current RMS)
   - **RV-xxxx** → Event Revolution asset (Flex)
2. Scan the asset using the correct system.
3. If an asset has no barcode:
   - Set it aside in the “Needs Tagging” bin.
   - Notify the warehouse manager before proceeding.

Never scan an MP asset into Flex or an RV asset into Current RMS.


2. Scanning for Pulls
---------------------

1. Begin with the job’s pull sheet.
2. As each item is pulled from the shelf:
   - Scan it into **the job’s pull or pick list**.
   - Confirm it registers with the correct asset number and description.
3. Items without barcodes must be added manually and set aside for tagging.
4. If the system flags:
   - **Unavailable** → already on another job  
   - **Missing** → flagged missing from last job  
   - **Damaged** → marked under repair  
   Contact the project manager for substitution approval.


3. Scanning During Staging
--------------------------

1. After pulling, place gear in the staging zone.
2. Re-scan **all items** as they enter staging to verify:
   - Correct asset count  
   - Correct ownership  
   - No duplicates  
3. Replace any incorrectly scanned asset (wrong company, wrong variant, etc.).
4. Confirm total items match the pull sheet.
5. Update the system status to **“Ready for Load”** once staging is complete.


4. Scanning for Truck Loading
-----------------------------

1. Optional but strongly recommended for large jobs:
   - Scan items **as they are loaded** into the truck.
2. If the workflow is followed:
   - This creates a *departure manifest* (Flex / Current RMS).
3. Confirm no unscanned items are placed on the truck.
4. If last-minute add-ons appear:
   - They **must** be scanned before loading.
   - Updated items must be reflected on the pull sheet.


5. Scanning Returns
-------------------

1. As equipment returns to the warehouse:
   - Scan each item to **check it back in** from the job.
2. Place returned items in the proper return zones:
   - Clean/dirty  
   - Prep/testing  
   - Repair  
   - Straight-to-shelf (cables, simple gear)
3. If an item does not scan into the job:
   - It may have been misplaced or not checked out properly.
   - Report discrepancies immediately.
4. Mark any damaged gear as:
   - **Needs Repair**
   - **Missing Parts**
   - **Not Functional**
5. Download and review the “Not Returned” or “Missing” report for final reconciliation.


6. Scanning for Maintenance & Repair
------------------------------------

1. Items removed from inventory for maintenance:
   - Must be scanned into a repair job or repair queue.
2. After repair:
   - Test gear thoroughly.
   - Scan the item back into general inventory.
   - Clear temporary repair flags in the system.


Quality Control
===============

- No item should ever move without being scanned.
- Never scan an item to the wrong company’s system.
- Confirm every scan with a visual check of the item’s label and description.
- Keep scanners charged and test them at the start of every shift.
- Use the “open items,” “missing,” and “damaged” reports regularly.


Troubleshooting & Exceptions
============================

**Item Won’t Scan**  
- Clean the barcode.  
- Try manual entry.  
- If still invalid → route to “Needs Tagging” bin.

**System Shows Wrong Availability**  
- Sync or refresh the system.  
- Re-check the job number and variant.  
- Contact PM if conflict remains.

**Item Has No Barcode**  
- Place in tagging bin for asset management.  
- Do not scan it under a placeholder number.

**Client Add-Ons at Load-Out**  
- PM must update the job.  
- Do not add gear without confirming ownership and scanning.
