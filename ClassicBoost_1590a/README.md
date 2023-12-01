# Classic Boost
A simple boost circuit (compare to LPB-1 by Electro-Harmonix), the sound of this pedal ushered in a new era of rock and roll.
It's great for pushing an amp into edge of breakup, or just adding some volume or slight distortion. It is a single knob boost, and
about as simple as it gets. A great beginner project. Cost ~$5.00 for 3 pcbs from OSHPark (free shipping in USA).

This boost has been built and tested using a 1590a enclosure, but a 1590b would also be a great choice for a little more room.

Component values are printed on the PCB itself for easy assembly.


## Resources

Tayda Drill Template:
OSHPark Shared Project (simply go here to order this PCB):

## Parts List

RESISTORS (1/4 watt)
| QTY  |    VALUE   |
---------------------
|  1   |   390 ohm  |
|  1   |   4K7      |
|  1   |   10K      |
|  1   |   43K      |
|  1   |   430K     |

CAPACITORS
| QTY  |    VALUE   |
---------------------
|  2   |    0.1 UF (100nF) |

TRANSISTORS
| QTY  |   Part #   |
---------------------
|  1   |   2N5088   |

DIODES
| QTY  |   Part #   |
---------------------
|  1   |   1N5817   |
|  1   |   5mm LED (color of choice)   | Note: Tayda drill template assumes the LED is in a 5mm bezel, change LED hole size as desired.

POTENTIOMETERS
| QTY  |    VALUE   |
---------------------
|  1   |   A100K   | Note: B100K for linear taper works fine. Use 16mm right angle PCB mount if using 1590a drill template.

SWITCHES
1   |  3DPDT footswitch

JACKS
2   |   1/4" Mono Audio Jack
1   |   9 volt power jack (center negative)    Note: No space for battery in 1590a enclosure


## How it works
1. Download or clone this repo to get the KiCad design files.
2. Use the PCB manufacturing service of your choice to order the boards. PCBWay, JLCPCB, and OSHPark are popular choices. <br>
   These designs have been tested using OSHPark. Simply go to the homepage and drag and drop the KiCad PCB file to upload and
   follow the prompts, no Gerber files required. 
3. Optionally, purchase a pre-drilled enclosure from Tayda. These designs have a tayda drill template that has been tested with the pcb. 
4. Purchase the components needed as shown in the parts list. Popular sources are Tayda, Mouser, Amazon.
5. When you receive your parts, assemble, solder, and wire the pedal.

Note: The pedal wiring works the same as most PedalPCB pedals with a 3PDT footswitch unless otherwise noted. 
      You can use [this build documentation](https://docs.pedalpcb.com/project/Amentum.pdf) as a wiring reference. 

## Wiring

The wiring labels on the board indicate the following:

InG - Intended for input jack ground
In  - Input Jack Signal
SW  - Switch connection to footswitch
SwG - Ground connection to footswitch 
O   - Output Jack Signal
OG  - Intended for output jack ground
Gnd - Intended for power jack ground
9v  - Positive 9v power

LED: IMPORTANT!!! The square hole for the LED on this board indicates NEGATIVE (shorter lead) and the circle hole is POSITIVE (longer lead).


You can use [this build documentation](https://docs.pedalpcb.com/project/Amentum.pdf) from PedalPCB as a reference for intended wiring. 