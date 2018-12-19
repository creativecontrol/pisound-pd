# pisound-pd
various PureData audio patches for the PiSound platform

Make sure you've done the standard PiSound setup:
https://blokas.io/pisound/docs/

Then install PD as described here:
https://blokas.io/pisound/docs/Pisound-Config/

These patches are setup to use the PiSound App:
https://blokas.io/pisound/docs/Pisound-App/

## USB Import update

This is no longer necessary. Externals importing from USB has been added to the PiSound core as of 2018.12.19

~~To allow for compiled PD externals to be installed from the USB stick update the usb_import.sh script on the Pi.~~

## Patch installation

The easiest way to install the patch files is to copy the project folders to a USB stick and use the method described here:
https://blokas.io/pisound/docs/Pisound-App/#importing-items-from-usb

Copy the **pisound-patches** directory to a USB stick and use in the process outlined above

## Externals installation

Some of the patches require additional PD Externals not included with the standard distribution.

Copy the **pisound-externals** directory to a USB stick and they will be copied to the RPi during USB import.
