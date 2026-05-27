# Team Win Recovery Project (TWRP)

## Install on Linux via heimdall

heimdall

sudo apt install heimdall-flash

## Install (TWRP) - 3.3.0-2 (P3110)

Sha1sum:

c49b20717564d1a38d886eadb4be3f3b0e1d92a6  GT-P3110_TWRP_3.3.0-2.img

sudo heimdall flash --RECOVERY GT-P3110_TWRP_3.3.0-2.img --no-reboot
s
## Enter Team Win Recovery Project - Recovery Mode

1. Turn Off Device:
2. Press Power Button + Volume up Key
3. When logo pops up release "Power Button"
4. Hold Volume up for a few more seconds
5. Team Win Recovery Project

![TWRP1](/pic/TWRP-3.1.1.0.png "Main Screen")

See more info on reboot.

![TWRP2](/pic/Reboot.png "Reboot")

## Enter Custom OS Warning Menu

1. Turn Off:
2. Press Power Button + Volume down Key
3. Custom OS Warning Menu Appears

![CustomOS](/pic/CustomOS.png "CustomOS" )

Connect your device via USB and run:

sudo heimdall detect
Expected output:

Device detected

If not, check:

USB cable/port
USB debugging / driver issues
That you're really in Download Mode