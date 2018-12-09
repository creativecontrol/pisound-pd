# pisound-patches
various audio patches for the pisounds platform

Make sure you've done the standard PiSound setup:
https://blokas.io/pisound/docs/

Then install PD as described here:
https://blokas.io/pisound/docs/Pisound-Config/

These patches are setup to use the PiSound App:
https://blokas.io/pisound/docs/Pisound-App/

## USB Import update

To allow for compiled PD externals to be installed from the USB stick update the usb_import.sh script on the Pi.

copy the file to the Pi:
    
    cd <this cloned repo>
    scp usb_import.sh pi@<pi IP address>:

then ssh to your pi to move the file to the correct place:
    
    ssh pi@<pi IP address>
    sudo mv usb_import.sh /usr/local/pisound-ctl/usb_import.sh


## Patch installation

The easiest way to install the patch files is to copy the project folders to a USB stick and use the method described here:
https://blokas.io/pisound/docs/Pisound-App/#importing-items-from-usb

Copy the entire **pisound-patches** directory to a USB stick and use in the process outlined above
