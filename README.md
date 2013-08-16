LGX Eagle Resources
====================

To use clone the repository then add each directory to the Eagle search paths.

On Windows:
 1. Install and set up [Git for Windows](http://windows.github.com/)
 2. Clone lgxlogic/Eagle-Resources using the Git client
 3. Open the repository, click Tools->Open in Explorer
 4. In the Eagle Control Panel, click Options->Directories
 5. Append the path to each of the directories in the repository to the corresponding field, 
 seperated by a semicolon (templates/ in the Projects field)

Don't forget to sync the repository in the Git client any time changes are made.
 
In this repository:

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
 * **cam/**
   * **gerbers-rs274x-excellon.cam** - Generates rs274x Gerbers and an Excellon drill file
   * **gerbers-rs274x-excellon-vscore.cam** - Same as above plus a v-score layer
 * **templates/** - Eagle project templates
   * **BeagleBone/**
     * **BB-cape-mitered-0603.sch/.brd** - BB cape, mitered corners, EEPROM, 0603 passives
