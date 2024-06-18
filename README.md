# firmware_smart
Firmware releases for TRIMUI Smart (TG2040)

firmware - v1.0.0 20240511
===========================
1. New feature: MENU Force Save.(enable in settings) 
    When press menu in RetroArch, it will save game and you can shutdown directly, 
    the system will go to same location and waiting for your 'Resume' when next boot.
2. Update the Bluetooth logic  as SmartPro, and all applications automatically use Bluetooth.
3. Update the WiFi logic of as SmartPro, allowing for password modification and multiple records.
4. Add X menu launch selection support.
5. Fixed the netplay between smart and Smartpro.
6. Fix the issue of hotspot netplay where hotspots cannot be used as hosts.
7. Fix issue when using 'png' as extlist in config.json and ext case sensitive.
8. Add low-battery LED support, with red double flashing.
9. Add LED indicating that the machine auto-turn-off screen (Telling it is not really shutdown.).
10. Upgrade the RetroArch (ra32.trimui/ra32.trimui_sdl) to version 1.18.0.
11. Developer related: Add standard battery drivers class and fix occasional crashes when RetroArch reads batteries
12. Change MainUI icons (improve contrast).
13. Change expression (as SmartPro) in the device info page.
14. Fix game list text length display issue.
15. SD card hotplug support.
16. Fix issue: SD card becoming read-only when encountering errors.
17. Remove CPU settings in MainUI. Fine tune the CPU frequency logic for each Emu launch.sh
      check 'Emus/_sample_cpufreq_scripts' to find cpufreq.sh to replace.
18. Add multiple languages (Chinese/English/Portuguese/Spanish/German/Italian/French/Japanese/Korean/Russian)
19. Bug fix: do turn off wifi power when WiFi and bluetooth switches are both off.
20. Default grid display.
21. Add fake RTC. The system time will save and recover at at next boot. (except 1970~2023)
      Please use WiFi NTP time synchronization first.
22. Fix MainUI graphic tearing.

