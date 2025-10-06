# Kliper on Prusa Clone MK3 BEAR
Klipper config for Prusa Clone MK3 BEAR 3D printer

## Prusa MK3 BEAR Clone
* BearLab [GUIDE](https://guides.bear-lab.com/c/Root)
* Prusa MK3 BEAR [Frame](https://hobby-store.pl/en/3d-printer-parts/frame-kits-for-3d-printers) (not availiable anymore) and other minor parts
* Extruder [Voron-Afterburner](https://github.com/VoronDesign/Voron-Afterburner)
* Hot-End [Phaetus Dragon High Flow](https://www.phaetus.com/products/dragon-hotend-hf)
* X-Axis [Parts](https://www.printables.com/model/54545-afterbearner-the-prusa-bear-afterburner-stealthbea)
* Stepper motors Z-axis, Trapezoid nuts, Y-carriage, Linear bearings LM8UU, Smooth PEI Print Sheet bought from [Prusa store](https://www.prusa3d.com/category/mk3-mk3s-mk3s/)
* MCU - [BigTreeTech SKR 2](https://www.anodas.lt/en/biqu-skr-2-motherboard-for-3d-printers)
* Case [Universal BTT SKR V1.3, V1.4 & V2](https://www.thingiverse.com/thing:4178177) and [Modules for Universal Boxes](https://www.thingiverse.com/thing:4210933)
* [Voron StealthBurner Mount for Biqu / BTT MicroProbe](https://www.printables.com/model/937492-voron-stealthburner-mount-for-biqu-btt-microprobe/files)

#### Notes

...

## ToDo
- [x] Calibrate min max of gantry
- [x] Probe offset
- [x] X axis twis compensation
- [x] Start/End print macros
- [x] Silent steppers
- [x] Spool holder for Prusa Bear
- [ ] Bed mesh
- [ ] Extruder calibration
- [ ] Ellis' print tuning guide
- [ ] Add screen
- [ ] Add lights
- [ ] Neat-up wiring (textile sleeve)
- [ ] Increase speeds

## Nice things ToDo
* [Klipper mesh on print area only install guide](https://gist.github.com/ChipCE/95fdbd3c2f3a064397f9610f915f7d02)
* [Klipper Adaptive Meshing & Purging](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)
* [Trad Rack multimaterial system for FFF printers](https://github.com/Annex-Engineering/TradRack)
* [KlipperScreen](https://klipperscreen.readthedocs.io/en/latest/)
  * https://biqu.equipment/collections/lcd-screen
* [Upgrade to Stealthburner](https://github.com/VoronDesign/Voron-Stealthburner)
* Upgrade to high temp thermistor
  

## Sources
* Tuning
  * [Ellis' Print-Tuning-Guide](https://ellis3dp.com/Print-Tuning-Guide/)
  * [Finding the axis limits](https://github.com/rootiest/zippy_guides/blob/main/guides/axis_limits.md)
  * (Prusa Filament Material Guide)[https://help.prusa3d.com/filament-material-guide]
* Configuration examples
  * [Klipper3d/klipper](https://github.com/Klipper3d/klipper/tree/master/config)
  * [Kliper on Prusa MK3s Example](https://github.com/dz0ny/klipper-prusa-mk3s/)
  * [Voron Software Configuration](https://docs.vorondesign.com/build/software/configuration.html)
  * [Klipper probe config for the BIQU Microprobe (V1/V2)](https://gist.github.com/utlandr/c3dab6bbcca1fc19dfc402d81cfd75e4)
  * [Orbiter v2.0 Summary (extruder cfg)](https://www.orbiterprojects.com/orbiter-v2-0/)
  * [Voron-Switchwire config](https://github.com/VoronDesign/Voron-Switchwire/blob/master/Firmware/skr_mini_e3_v2_config.cfg)
  * [https://github.com/simplisticton/v2-2566config](https://github.com/simplisticton/v2-2566config)
* Macros
  * [klipper-macros](https://github.com/jschuh/klipper-macros)
  * [A better print_start macro](https://github.com/jontek2/A-better-print_start-macro)
  * [Creating Your First Macros](https://github.com/rootiest/zippy_guides/blob/main/guides/macros.md)