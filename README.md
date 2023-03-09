File List:

printer.cfg - This is my Klipper config for the Two Trees Bluer Plus (BLU-5) (V2)
Robin_nano43.bin - This is the Klipper firmware compiled for the Bluer Plus (V2)
README.md - This file.

*The V2 is not in the model name, it is just a way to differentiate from the original Bluer Plus.

This config file should get you started with your Klipper install. Please note that this
WILL NOT WORK with the original Bluer Plus (2020-2021 model with the 0.9° steppers).

The Bluer Plus (V2) has 5 x Usongshine 42SHDC3045Z-16BD stepper motors which are ALL 1.8° motors.
Note that the display does not have any functionality in Klipper and will just read "Booting..".
You WILL need to calibrate your probe z offset by homing your printer and running the PROBE_CALIBRATE command. You may also want to tram your bed using the BED_SCREWS_ADJUST command for manual tramming or the SCREWS_TILT_CALCULATE command for tramming with the probe. You may also need to setup a virtual sd card and any other macros you wish to use.

Two Trees Bluer Plus (V2):
MKS Robin Nano V1.2
3D touch
5 x TMC2209
5 x Usongshine 42SHDC3045Z-16BD 1.8°