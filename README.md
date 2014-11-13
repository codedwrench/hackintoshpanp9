Hackintoshed System76 Panp 9
=============================
Yosemite 10.10
Macbookpro 9,2 <= SMBIOS


WORKING:

Sound, except internal mic and HDMI -> AppleHDA patched for VT1802P(Mirones kext on insanelymac)
VoodooHDA works with the internal microphone, but still no hdmi sound. 
Acpi lid is working, brightness controls work with hotkeys, not with slider on OSX.
Speedstepping and sleep working too.
Ethernet using RTL8111 kext. Batterystats using my dsdt and rehabmans battery management kext.
Touchpad using voodoops2controller.kext


NOT-WORKING:

Wifi, but thats to be expected with Intel Wifi+BT, replaced with atheros ar9280.
HDMI sound.
