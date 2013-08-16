LGX Eagle Rescources
====================

To use clone the repository then add each directory to the Eagle search paths (Options->Directories from the Control Panel).

Contains:

 * lbr/
   * logic-supply.lbr
     * BeagleBone cape parts
         * BBH - BeagleBone header sub-assembly
         * BBHD - BeagleBone header sub-assembly with BB Black with debug header
         * BBHD-NH - Same as BBHD but with the pins reserved for HDMI unpopulated
     * Graphics
         * LOGO-LGX - LGX logo, believe it or not
         * OSHW-LOGO - Open Source Hardware logo
     * EEPROM-I2C - Standard 8-pin i2c EEPROM footprint (e.g. BB cape EEPROM)
     * And lots more...
 * cam/
   * gerbers-rs274x-excellon.cam - Generates rs274x Gerbers and an Excellon drill file
   * gerbers-rs274x-excellon-vscore.cam - Same as above plus a v-score layer
