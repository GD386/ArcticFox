# ArcticFox
*Custom Firmware for Joyetech, Wismec and Eleaf battery mods*

![](http://i.imgur.com/JP4KC8A.png)
![](http://i.imgur.com/E1e7cs1.png)

![](http://i.imgur.com/DCy4wYg.png)
![](http://i.imgur.com/TnqNYK1.png)
![](http://i.imgur.com/0XTV9xD.png)

**Use [NFE Toolbox](https://github.com/TBXin/NFirmwareEditor/releases) for flashing and configuring your device.**

## List of supported devices:
* eVic VTC Mini
* eVic VTC Dual
* eVic VTwo Mini
* eVic VTwo
* eVic AIO
* eVic Basic
* eGrip II / Light
* Cuboid
* Cuboid Mini
* Wismec Presa TC75W
* Wismec Presa TC100W
* Wismec Reuleaux RX75
* Wismec Reuleaux RX200
* Wismec Reuleaux RX200S
* Wismec Reuleaux RX2/3
* Eleaf iStick Pico 75W

## Profiles
The main difference is the profile based user interface, so to say, the DNA-style, and the larger focus on customization than original Joyetech firmware.
Profile is the set of parameters of used atomizer, such as coil material, resistance, power and temperature values.
The user have 8 profiles which can be edited with NFE Toolbox, and which can be assigned to his favourite atomizers.

![](http://i.imgur.com/UjtY7Ir.png)

Profiles can be switched automatically, based on saved coil resistance, and in manual mode. All you need to use the automatic switch is to enable "Smart" mode, install atomizer and assign them to the desired profile.

![](http://i.imgur.com/fadryzQ.png)

When you re-install this atomizer later, assigned profile will be activated automatically.
If resistance of installed atomizer is not found in profiles, you'll be prompted to select new profile or re-assign existing.
When you switching manually to profile that have saved resistance mismatch, you'll be prompted to update or keep settings of selected profile.

## Main Menu

Hold Fire and Plus buttons for a 1 second to enter menu.

![](http://i.imgur.com/XSWOLDJ.png)

## Profile Menu

![](http://i.imgur.com/mpg5ukP.png) ![](http://i.imgur.com/2UPcLHy.png) ![](http://i.imgur.com/yNH5crk.png) ![](http://i.imgur.com/kc0PYf7.png) ![](http://i.imgur.com/CNzn7vQ.png)

* **Wire** - coil material, temperature sensing or not (VW), can be set to standard or user-defined TFR;
* **Coil** - saved resistance;
* **TCR** - value can be edited when selected Joyetech TC algo with custom TCR;
* **T. Dom** - temperature-dominant regulation style;
* **Preheat** - power control, use preheat or power curve;

## Screen Menu

![](http://i.imgur.com/6jddZL9.png) ![](http://i.imgur.com/3fRgkGN.png) ![](http://i.imgur.com/FmVjNro.png) ![](http://i.imgur.com/2UYldpC.png)

* **Dim** - time to dim display;
* **Wake <>** - waking mod by pressing regulatory buttons;
* **Charge** - show additional information on charging screen, battery voltage(s) and board temperature;
* **Logo** - show logo on main screen;
* **Clock** - show clock on screen:
     - Type - analog or digital;
     - On Main - show clock on main screen;
     - Saver - show clock in standby mode;
* **Selector** - show additional profile info on "Select Profile" screen;
* **Contrast** - adjust brightness of display;
* **Skin** - change main screen style.

## Settings Menu

![](http://i.imgur.com/aDuSk3n.png) ![](http://i.imgur.com/3JeWUqf.png) ![](http://i.imgur.com/8V1VCeo.png)

* **1 Watt** - increment/decrement power by 1,0 Watt;
* **Menu** - New - switch profiles using Selector, Old - switching via standard Edit Main action;
* **Smart** - automatic switching profiles settings:
     - On/Off;
     - resistance tolerance;
     - show Profile Menu after assigning new;
* **Clicks** - actions assigned on 2/3/4 Fire button clicks:
     - None;
     - Edit Main - Joyetech default 3-clicks action;
     - Profiles - Profiles Selector;
     - T. Dom - temperature-dominant on/off;
     - Clock - show/hide clock on main screen;
     - On/Off - switch mod on/off;
     - LSL - switch light sleep mode on/off;
     - Main Menu - enter Main Menu, the same as Fire + ;
     - Preheat - preheat settings for active profile;
     - Edit Profile - enter Profile Menu;
     - Smart On/Off
* **RTC** - realtime clock setup;
* **Expert** - settings for advanced users:

![](http://i.imgur.com/UZBrHjJ.png) ![](http://i.imgur.com/7fT0pNi.png) ![](http://i.imgur.com/edejq3z.png) ![](http://i.imgur.com/FoH1vaE.png)

* **USB**
     - Mode - default is HID for connecting to NFE Toolbox, firmware update etc.; COM - adds virtual COM Port; DSK - adds virtual drive with firmware image (read only);
     - NoSlp - do not enter deep sleep mode while connected to USB;
     - Charge - device is charging batteries while connected to USB;
* **BVO** - batteries voltages offset;
* **BATT** - battery discharge profile;
* **SHUNT** - Ohm-meter correction;
* **ChkTCR** - check coil material TCR, switching this option to off can eliminate TCR Error on heavy coils;
* **RCOBC** - Reset Counters on Battery Change, clear vaping statistics;
* **X32** - RTC module uses secondary 32768 Hz oscillator, if present;
* **LSL** - Light Sleep Mode, for devices without secondary oscillator keep RTC accurate. It takes some more energy in standby mode, so user will be warned by ! sign right of battery indicator;
* **DBG** - debug mode, for internal test purposes.


## Info Screen
![](http://i.imgur.com/2QoKfkX.png)

Shows brief hardware information and some stats.

### Many thanks to:
     * TBXin - for NFE Products, ideas and tests
     * Zinger - for graphics, ideas and tests
     * ClockSelect - for great project called myevic
     

# Disclaimer:

The firmware is distributed in the hope that it will be useful, but without any warranty. It is provided "as is" without warranty of any kind, either expressed or implied, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose. The entire risk as to the quality and performance of the firmware is with you.
