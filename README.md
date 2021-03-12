# 3d-print-camera-2
Cinema-Style Camera Housing For Raspberry Pi 4 and HQ Camera

## Overview

This is an actively-cooled cinema-style camera housing for a Raspberry Pi 4B and a Raspberry Pi HQ Camera that features a 45* articulating LCD touch screen, mounting for external accessories, as well as space for a high-capacity battery.

If you are looking for software to run on this camera, consider this [camera](https://github.com/eat-sleep-code/camera) software that includes on-screen controls and raw image capture.

## Getting Started

### You will need the following non-included parts:

* (1) - Raspberry Pi 4B
* (1) - Micro SD card (Sandisk preferred)
* (1) - USB Storage Device (Sandisk or Samsung preferred)
* (1) - Raspberry Pi HQ Camera
* (1) - [Adafruit Flex Cable for Raspberry Pi Camera or Display - 300mm / 12"](https://smile.amazon.com/gp/product/B00I6LJ19G)
* (1) - [Set of 20cm Male to Male Jumper Wires](https://smile.amazon.com/gp/product/B072L1XMJR)
* (1) - [Waveshare 5.5" Capacitive Touch LCD with DSI Connector](https://smile.amazon.com/gp/product/B08J821VQK)
* (2) - [Noctua 40mm x 10mm **5-volt** Fans](https://smile.amazon.com/gp/product/B00NEMGCIA)
* (1) - [Noctua Y Splitter Cable](https://smile.amazon.com/gp/product/B076542HBN)
* (1) - [40mm Fan Grill/Guard](https://smile.amazon.com/gp/product/B07JM67CZ5)
* (1) - [Assorted Camera Screws](https://smile.amazon.com/gp/product/B07BKPXR72)
* (1) - [Left and Right set of Torque Friction Type Positioning Hinges](https://smile.amazon.com/gp/product/B0863T8894)
* (1) - [Set of M3, M4, M5 Cap Head Screws](https://smile.amazon.com/gp/product/B07Q24FV8T)
* (1) - [Set of assorted M2.5 Cap Head Screws](https://smile.amazon.com/gp/product/B07VG889RW)
* (3) - Assorted 1/4-20 Cap Head Screws
* (4) - [M2.5 x 35mm Cap Head Screws](https://www.accu.co.uk/en/cap-head-screws/10635-SSC-M2-5-35-A2)
* (1) - [M6 Stainless Threaded Stud with Thrust Pad](https://www.jwwinco.com/en-us/products/2.2-Tensioning-clamping-with-handles/Star-knobs/GN-6336.12-Technopolymer-Plastic-Star-Knobs-with-Stainless-Steel-Threaded-Stud-with-Toggle-Thrust-Pad)
* (5) - Black round rubberized padded "feet"
* (4) - 5.9mm x 4mm Neodymium Disc Magnets
* (1) - [Aluminum Heatsink Set](https://smile.amazon.com/gp/product/B07VPP642H)
* (1) - [Anker PowerCore Essential 20000 PD battery](https://smile.amazon.com/gp/product/B07SQ5MQ6K)
* (1) - CS Lens or other lens with C or CS mount adapter

### You may need the following additional tools:

* [1/4"-20 tap set](https://smile.amazon.com//B003A2GXQK)
* [Metric tap set](https://smile.amazon.com/gp/B07FG1MJND)
* Needle nose pliers
* Xacto Knife (for cleaning up small imperfections in prints)
* WD-40 (for lubricating threads of fasteners)

## Printing Instructions

:warning: **IMPORTANT:** Please review each part in your slicing software before printing to ensure a logical face is touching the build plate!      

This was printed on a Creality CR-6 SE with the hot end set at 200C and the bed set at 65C.

Please see the following individual print notes below.   

:warning:  80% infill is used for many of these pieces to ensure there is minimal flex when the camera is equipped with heavier lenses.   If you choose to decrease this, you do so at the risk of part failure which may result in damage to your lens or other property.

* **Badge**
   * Infill: 30%
   * Material Required: 1g - Hatchbox True Red (or Transparent Red) 1.75mm PLA
   * Adhesion Type: Skirt
   * Supports: None
   * Positioning: Rear Side Down / Number Up
   * Quantity: 1

* **Camera Mount**
   * Infill: 80%
   * Material Required: ~ 28g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Rear Side Down / Support Bosses Up
   * Quantity: 1

* **Front Housing**
   * Infill: 80%
   * Material Required: ~ 314g - Hatchbox True Black 1.75mm PLA
   * Supports: Touching Buildplate *(In addition, two small custom supports are included in this model near the hinge area.   These can be easily snipped away after the print is complete.)*
   * Adhesion Type: Skirt
   * Positioning: Left Side Down
   * Quantity: 1

* **Handle - Right**
   * Infill: 80%
   * Material Required: ~ 58g - Hatchbox True Black 1.75mm PLA
   * Supports: Yes
   * Adhesion Type: Brim
   * Positioning: Bottom Side Down
   * Quantity: 1

* ** Handle - Top**
   * Infill: 80%
   * Material Required: ~ 81g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Right Side Down
   * Quantity: 1

* **HDMI & USB-C Port Recess Housing**
   * Infill: 80%
   * Material Required: ~12g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Right Side Down
   * Quantity: 1

* **Inner Lid**
   * Infill: 80%
   * Material Required: ~ 29g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Interior Side Down
   * Quantity: 1
<br>
* **Panel - Left**
   * Infill: 80%
   * Material Required: ~ 10g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Exterior Side Down
   * Quantity: 1

* **Panel - Right**
   * Infill: 80%
   * Material Required: ~ 11g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Interior Side Down
   * Quantity: 1

* **Rear Housing**
   * Infill: 80%
   * Material Required: ~ 133g - Hatchbox True Black 1.75mm PLA
   * Supports: Touching Buildplate
   * Adhesion Type: Skirt
   * Positioning: Interior/Hinge Side Down
   * Quantity: 1

* **Stylus Clip **
   * Infill: 80%
   * Material Required: ~ 1g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Bottom Side Down
   * Quantity: 1 (OPTIONAL)

* **USB-C Cable Clip**
   * Infill: 80%
   * Material Required: ~ 1g - Hatchbox True Black 1.75mm PLA
   * Supports: None
   * Adhesion Type: Skirt
   * Positioning: Bottom Side Down
   * Quantity: 2   

* **Wire Clip**
   * Infill: 80%
   * Material Required: ~ 4g - Hatchbox True Black 1.75mm PLA
   * Supports: Touching Buildplate
   * Adhesion Type: Brim
   * Positioning: Side Opposite Wire Recesses Down
   * Quantity: 2

