# RPi Zero custom firstboot

These are a set of files that set up for Raspberry Pi Zero:

* Default user/password: `pi` / `raspberry`
* Hostname: `pi`
* USB RNDIS/CDC-ECM composite gadget compatiable with Windows/macOS/Linux
* LED heartbeat to indicate active state of the USB gadget

## Usage

Simply mount the `bootfs` of the default Raspberry Pi OS image, and copy all files over, replacing existing files.

When the USB gadget becomes active, the LED trigger will become the classic Linux "heartbeat".

## References

* https://gitlab.com/JimDanner/pi-boot-script
* https://github.com/rundekugel/USBGadgetNetwork
