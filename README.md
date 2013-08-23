LGX Eagle Resources
====================

Contains resources for CadSoft's Eagle EDA tool: http://www.cadsoftusa.com/eagle-pcb-design-software/

To use, clone the repository then add each subdirectory to Eagle's search paths.

On Windows:
 1. Install and set up [Git for Windows](http://windows.github.com/)
 2. Clone lgxlogic/Eagle-Resources using the Git client
 3. Open the repository, click Tools->Open in Explorer
 4. In the Eagle Control Panel, click Options->Directories
 5. Append the path to each of the subdirectories in the repository to the corresponding field, 
 seperated by a semicolon (templates/ goes in the Projects field)
 6. If using the EagleUp models, follow instructions in EagleUp-models/README.md

----

In this repository:

 * **EagleUp-models/** - SkethUp component models for EagleUp, see EagleUp-models/README.md
 * **cam/**
   * **gerbers-rs274x-excellon.cam** - Generates rs274x Gerbers and an Excellon drill file
   * **gerbers-rs274x-excellon-vscore.cam** - Same as above plus a v-score layer
 * **lbr/**
   * **logic-supply.lbr**
     * BeagleBone cape parts
         * **BBH** - BeagleBone header sub-assembly
         * **BBHD** - BeagleBone header sub-assembly with BB Black with debug header
         * **BBHD-NH** - Same as BBHD but with the pins reserved for HDMI unpopulated
     * Graphics
         * **LOGO-LGX** - LGX logo, believe it or not
         * **OSHW-LOGO** - Open Source Hardware logo
     * **EEPROM-I2C** - Standard 8-pin i2c EEPROM footprint (e.g. BB cape EEPROM)
     * And lots more...
 * **templates/** - Eagle project templates
   * **BeagleBone/**
     * **BB-cape-mitered-0603.sch/.brd** - BB cape, mitered corners, EEPROM, 0603 passives

----

Check out Logic Supply at http://www.logicsupply.com/

Follow us on Google+ for updates and more information: https://plus.google.com/u/0/b/103613886667848850929/

Created by Alexander Hiam for LGX / Logic Supply.

All included files, unless stated otherwise, are provided under the Creative Commons Attribution-ShareAlike 3.0 Unported License.   
To view a copy of this license, visit http://http://creativecommons.org/licenses/by-sa/3.0/  
All text above must be included in any redistribution.