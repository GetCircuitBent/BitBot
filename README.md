# Bit Bot
## Robot/Pitch Shift Effect
This is a small, simplified clone of the Death by Audio Robot guitar pedal, stripped down to be installed in toys/keyboards as a mod.

## Notes:
* Can Connect Pin 3 of Control Pot to Ground via a Capacitor (~47nF) to mod the control
* Has an optional PWM LED connection that changes LED brightness to correspond to input volume.
* Add a Wet/Dry Control by Attaching a 100K Lin pot to:
  * Clean/Effect Input (pin 1)
  * Output Jack/Speaker (pin 2)
  * Effect Output (pin 3)

## Parts List:
(Asterisked parts only needed if you use the indicator LED)
* HT8950 (the DIP 18 version, not the 8950A DIP 16 one)
* 500k Linear Potentiometer
* Switches x 3 (if using switches to set mode)
* Momentary Buttons (normally open) x 4 (if using buttons to set mode)
* *LED (pretty much any kind you like will work I expect)
* 100nF film (or ceramic) capacitor x 3
* 100uF electrolytic capacitor (any voltage rating I know of will work, but say 6 volts just to be specific)
* 10uf electrolytic capacitor
* Resistors:
  * *220R (the IC's datasheet doesn't include this resistor, I just can't bring myself to put in an LED without a resistor. You'd probably be fine just to jumper this, or pop in any value between 100R and 1k, I just have a ton of 220Rs and can confirm this value works great)
  * 4.7k x 3
  * 470R x 2
  * 100k 

## Demo:
https://youtu.be/_ONI_Kui6XI

#### Not required or expected at all, but if you like it you can use the Sponsor button to buy me a beer!
