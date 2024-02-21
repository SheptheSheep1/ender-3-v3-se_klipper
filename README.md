# ender-3-v3-se_klipper
- My Klipper Configs for the Creality Ender 3 V3 SE 3D Printer
- Based on the work of [0xD34D](https://github.com/0xD34D/ender3-v3-se-klipper-config)
- Runs on an old pc as primary mcu and webhost for mainsail
- Used [KAMP](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging) for adaptive bed mesh and adaptive purge, KlipperScreen for output on an old android tablet, [moonraker-timelapse](https://github.com/mainsail-crew/moonraker-timelapse), and [mobileraker](https://github.com/Clon1998/mobileraker) for phone notifications
### Tips
##### Bed Mesh
- If your bed mesh has a lot of variance, meaning more than ~0.2mm, then getting it to have less variance will help a lot with first layers and general print quality
- In order to decrease variance run a 5x5 bed mesh when heated and locate your high points and sand or file the necessary spacer down using the indicated measurement you determine using your bed mesh low points and check before and after with calipers that can measure in the thousanths of an inch or hundredth of a millimeter
- Then, try heating the bed, running a bed mesh again, and repeating the above stated steps until you are satisfied with the variance across the bed
- If you have points that are much lower than others, some users have created spacers that can be put underneath the spacers to space them up, such as [IAmAnEngineer](https://www.printables.com/model/733411-ender-3-v3-seke-bed-leveling-shims) on Printables.com, I would recommend printing these in PETG, although I have had no need to use them
- Make sure your x-axis gantry is even, [Creality Guide](https://www.crealitycloud.com/post-detail/65015353ae72d153c2ef4e89)
- 
### TO-DO:
- Add Input Shaping
- Fix temperature display of primary MCU
- Change over to Raspberry Pi 3B as primary MCU
- Use Raspberry Pi Pico or Arduino/ESP32 as secondary MCU
