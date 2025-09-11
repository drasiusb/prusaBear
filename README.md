# Kliper on Prusa Clone MK3 BEAR
Klipper config for Prusa Clone MK3 BEAR 3D printer

## Prusa MK3 BEAR Clone
* BearLab [GUIDE](https://guides.bear-lab.com/c/Root)
* Prusa MK3 BEAR [Frame](https://hobby-store.pl/en/3d-printer-parts/frame-kits-for-3d-printers) (not availiable anymore) and other minor parts
* Extruder [Voron-Afterburner](https://github.com/VoronDesign/Voron-Afterburner)
* Stepper motors Z-axis, Trapezoid nuts, Y-carriage, Linear bearings LM8UU, Smooth PEI Print Sheet bought from [Prusa store](https://www.prusa3d.com/category/mk3-mk3s-mk3s/)

#### Notes 
~~Minor twist in X-axis (~0.2mm). Software compensation required.~~

SOLVED by new top/bot z axis mounts
* [Axis Twist Compensation](https://www.klipper3d.org/Axis_Twist_Compensation.html)
* [https://github.com/Klipper3d/klipper/pull/6048](https://github.com/Klipper3d/klipper/pull/6048)


## ToDo
- [x] Calibrate min max of gantry
- [x] Probe offset
- [x] X axis twis compensation
- [ ] Start/End print macros
- [ ] Bed mesh
- [ ] Silent steppers
- [ ] Extruder calibration
- [ ] Ellis' print tuning guide
- [ ] Add screen
- [ ] Add lights
- [ ] Neat-up wiring (textile sleeve)
- [ ] Increase speeds

## Nice things ToDo
* [Klipper mesh on print area only install guide](https://gist.github.com/ChipCE/95fdbd3c2f3a064397f9610f915f7d02)

## Sources
* [Ellis' Print-Tuning-Guide](https://ellis3dp.com/Print-Tuning-Guide/)
* [Finding the axis limits](https://github.com/rootiest/zippy_guides/blob/main/guides/axis_limits.md)
* [Kliper on Prusa MK3s Example](https://github.com/dz0ny/klipper-prusa-mk3s/)
* [Voron Software Configuration](https://docs.vorondesign.com/build/software/configuration.html)
* [Klipper probe config for the BIQU Microprobe (V1/V2)](https://gist.github.com/utlandr/c3dab6bbcca1fc19dfc402d81cfd75e4)
* [Orbiter v2.0 Summary (extruder cfg)](https://www.orbiterprojects.com/orbiter-v2-0/)
* [Voron-Switchwire config](https://github.com/VoronDesign/Voron-Switchwire/blob/master/Firmware/skr_mini_e3_v2_config.cfg)
