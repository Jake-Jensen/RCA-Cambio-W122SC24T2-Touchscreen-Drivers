# SileadFirmware
Touchscreen firmware for RCA W122SC4T2 (Cambio 12.2)

This repository is for archival purposes, for those who reinstalled Windows 10 from a clean ISO and lost touchscreen support. 

# Installation
Clone repository, then unzip contents into its own folder.

Open Device Manager, and select the unknown device matching ID "ACPI\VEN_MSSL&DEV_1680".
(To find the hardware ID, right click the unknown device in Device Manager, select properties, then select details. 
Scroll to "Hardware Ids", and compare values)

Right click the unknown device, then select "Update driver".


Select "Browse my computer for driver software".

Click the "Browse" button, then select the directory where you extracted the cloned repo from above. Then click "Next".

Touchscreen will be functional after driver finishes installation. 
