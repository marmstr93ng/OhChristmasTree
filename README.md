# OhChristmasTree
The initial concept for a electronic desk christmas tree.

## Parameters
* Small enough to not be unobtrusive on a desk
* Must resemble a christmas tree (PCB tree shaped)
* Decorated (LEDs as lights(differnt colours - RGB?), silk screen art, star LED (twinkle?))
* LED blink pattern selectable pattern
* Portable (battery powered)
* Standable (cross piece stand)
* Complete kit

## Steps
1. Model prototype
* Size, Shape, stand mechanics
2. Schematic/breadboard prototyping - (think of final pcb manufacturing)
* LED Control - simple patterns - button to cycle through (cycle off - indicated by star going out which is normally always on)
* reflash capability
* Power
3. PCB Layout

### Questions
* How to drive multiple LEDs off a few pins (ATtiny has five pins)?
* How to control fading? Achievable on as few pins as possible?

### Patterns
* Chase (one on at a time up the string of lights)
* FiftyFifty (half on, half off, switch back and forth)
* All (all permanantly on)
* Fade (all fade on and off) - requires power control!
* Pulse (all lights on, alternating lights pulse brighter)

## Future Ideas
* tune making
* custom patterns
* other christmas decoration features

## Links 
* [PCB Art](https://medium.com/@urish/a-practical-guide-to-designing-pcb-art-b5aa22926a5c)
* [Panelised Design](http://docs.oshpark.com/troubleshooting/panelized-designs/)
* [Charlieplexing](https://en.wikipedia.org/wiki/Charlieplexing)
* [Further Charlieplexing](https://www.instructables.com/id/Controlling-20-Leds-from-5-Arduino-pins-using-Cha/)
* [Serial Shifting](https://www.arduino.cc/en/Tutorial/ShiftOut)
* [PWM](https://www.arduino.cc/en/tutorial/fade)
* [PCB Fab](https://jlcpcb.com/)
* [Schematic to PCB](https://www.youtube.com/watch?v=35YuILUlfGs)
* [PCB Basics](https://learn.sparkfun.com/tutorials/pcb-basics)
* [Coin Battery Holder](https://www.mouser.co.uk/Power/Battery-Holders-Clips-Contacts/Coin-Cell-Battery-Holders/_/N-cid2l)
* [ATTiny](https://www.hackster.io/news/making-it-miniature-integrating-the-attiny85-in-your-arduino-project-857b796ac5f0)

### Model Parameters
* probable pcb manufacturer has cheap boards up to 100mm by 100mm
* heavy electronic parts as close to the base as possible (low centre of gravity), tree is wider there anyway
* Eyelet at the top of the tree to hang as tree ornament
* Red and white cord intertwined for hanging (to be included even when intended for stand mode)
* Stand embedded into the tree base (PCB)

Use Uno to similate ATTiny - prototype Charlieplexing (How many LEDs?) - prototype fading

1. Understand stand mechanics
2. Eyelet size and string length
3. Create working prototype with printed model copy (colour) with stand and hanging mechanics included 
4. Print shape copies for design work
* Part size parameters
* Part positioning
* LED number (pin constraints)
