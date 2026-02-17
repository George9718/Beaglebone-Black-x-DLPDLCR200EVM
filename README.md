# Beaglebone Black and DLPDLCR200EVM

## What this is
The following instructions and the code above can be used to set up a Beaglebone Black (BBB) with the Texas Instruments' DLPDLCR2000EVM (DLPDLCR) so that users can project files over ssh.

## Example
{images}

## Hardware used
 - Beaglebone Black (no wifi) {link}
 - Texas Instruments' DLPDLCR2000EVM {link}

## Installation
1. Flash the Debian image above to a microSD card and insert this into the BBB.
2. Overlay the DLPDLCR on top of the BBB so that the GPIO pins align (note orientation in image below)
  {image{
3. Connect the BBB via Ethernet to your router and plug in the 5v power supply.
4. SSH into the BBB on your computer. Tip: make sure your computer is on the same network as the BBB, 
