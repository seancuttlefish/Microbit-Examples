# BBC Micro:bit Examples

To be used with a Micro:bit V1 or V2 with a Grove adapter.

## Basics

### Happy Sad Face

Press Button A for a happy face and Button B for a sad face. 

### Shake Dice

Shake the Micro:bit to get a random number.

## Lighting

### Clap Light

Clap your hands to switch the **Neopixels** on P2 on and off. Uses a variable to store the current state of the lights. Uses Neopixel Extension. **Requires a Micro:bit V2, with a microphone.**

### Distance Light

The **Ultrasonic Uensor** on P1 measures the distance up to 1m and lights up the **Neopixels** on P2 accordingly. Uses Neopixel and Sonar Extension.

### Turn Light

As you turn the potentiometer (**Turn Sensor**) on P1, the **Neopixels** on P2 change colour. Uses Neopixel Extension.

### Remote Control

Transmit A and B button presses over the radio to set Neopixels on P2 to red and green. Uses radio channel 0, but set your own channel if working in a group. You will need two Micro:bits, one powered by a battery to send the messages. Another with **Neopixels** on P2 to receive the messages. Uses Neopixel Extension.

## Servos

### Grove Servo Buttons

Use the A and B buttons to set the **single** analogue servo on P1 to 0 or 180 degrees. **Note that this needs a powered Grove aapter, such as from Seeed Studio, to get sufficient voltage to operate the servo.** When you have programmed the Micro:bit, move the USB cable to the board. Uses Servo Extension.

