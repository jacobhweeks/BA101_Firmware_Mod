# BA101_Firmware_Mod
Modification to the BA101 firmware for quick testing of batteries between 1 and 25 Ah.
This would allow testing of batteries outside of vehicle batteries that have the same or similar characteristics. i.e., UPS Batteries

TODO:
- Capture firmware file for reverse engineering using appropriate tools.
- This may only be possible by capturing the firmware from the device itself, since no firmware is available from the manufacturer.

## Inside
### Locating possible serial interfaces for debugging.
There are 3 sets of pins where it may be possible to capture the firmware that's on the device, so it can be modified and reuploaded to the device.
![B101](https://github.com/user-attachments/assets/5388a482-deca-4e3b-adec-a2d5548fbcfc)

### Testing with a multimeter
I found the following sets of pins: Ground, 3.3V, 2.7V, what I suspect are data pins with 0 to 30 mV, and a pin with 1.5 mV
![B101a](https://github.com/user-attachments/assets/aeed8b73-e23d-4dbe-9b8b-aeddfff91e17)
