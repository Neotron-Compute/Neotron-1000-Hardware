# Neotron 1000
## A contemporary modern computer. 

The Neotron 1000 brings modern low power hardware to retro design. Our tech is based on the tried and true single board ARM computer model offering a hacker friendly platform for your retro project. 

With an ARM Cortex M7 based MCU the Neotron gets you right back into the hardware. It offers a real time platform ideal for everything from hardware experimentation to making twitchy platformers. With dual video output you can get up and running fast in text mode without compromising stunning sprite based hardware accelerated graphics. Raspberry Pi compatible expasion offers limitless customisability and extenstion.

The neotron aims to bring the retro computing feel, with DOS and BASIC like environments minus all the hastle of using obsolete equipment. HDMI output and USB peripheral support means you can plug it straight into your normal setup. It even has a headphone jack!

## Development Rationale

The Neotron 1000 is a Pi form factor SBC with a Cortex M7 CPU core. The Neotron is set apart from other Pi like devices in how its designed for realtime applications. It has not been designed with running a UNIX alike OS in mind. The neotron was is brainchild of @thejpster and @IGBC and is primarily designed with the goals of expanding the world of embedded Rust development and Rust OS development. Retro computer design provides a compelling platform for testing hardware, as many of the challenges of bringing fast paced 90's style gaming experiances to a modern hi res Display (while trivial for a modern computer) can really stress the limits of what can be acheived with contemporary embedded hardware. 

## Hardware

  - **CPU:** STMicroelectronics H7 Series CPU 400MHz
  - **Memory:** 8MB DRAM
  - **GPU:** Lattice ICE40 Series Soft Core (Hardware Accelerated Rendering)
  - **GPU RAM:** 16MB SRAM
  - **Storage:** SD Card Slot
  - **Network:** Base 10T Ethernet
  - **USB:** 2x USB2 High speed host ports 
  - **Audio:** Line Out / In Combo Jack
  - **Video:** Dual HDMI (1 CPU, 1 GPU)
  - **Other IO:** PS2 Keyboard/Mouse Port, Pi compatible Hat Connector (40 pin)
  - **Mechanical Form Factor:** Raspberry Pi 4B
