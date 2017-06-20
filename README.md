# Laser Config

We at Hobart Makers have a K40 laser cutter. We obtained it second hand, and it had 
received a series of mods and upgrades before we got it.

We intend to mod and upgrade it further - including driving it with a Raspberry Pi, 
GRBL Pi-Hat, and the original hardware stepper drivers. This will enable us to use 
it with web based software "LaserWeb" which can run on the Pi. The machine can then 
be accessed and driven via wifi, rather than via. parallel cable, and LinuxCNC.

This repository is intended to contain wiring diagrams, configuration settings, and 
whatever else is needed to recreate our setup.

## Contents

- laserweb3-settings.json: Import this file into your LaserWeb3 (settings
  are per-browser)
- connector_pcb: Cleans up the wiring in the control box onto a single PCB
