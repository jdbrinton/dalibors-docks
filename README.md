# dalibors-docks
This is a 1 Nixie Tube holder board with 3-channel LED lighting. Pretty Simple.


## Overview

This holes 1 Nixie Tube (Dalibor Farney P/N R|Z568M). It is wired to a 2.5mm pitch connector (JST P/N S12B-XH-A). The mating connector is JST P/N XHP-12. The crimp pins are JST P/N SXH-001T-P0.6 and supports 28 to 22-gauge wire.

The LEDs are wired to a 1.5mm pitch connector (JST P/N S6B-ZR). The mating connector is JST P/N ZHR-6. The crimp pins are JST P/N SZH-002T-P0.5 and supports 28 to 26-gauge wire.

You can likely use IWISS P/N SN-01BM as a low-cost crimper, but your mileage may vary.

Tubes can be purchased here: https://www.daliborfarny.com/


## Connections

There are two connections. One 12-pin 2.5mm pitch connector on the top for the Nixe tube. Another 6-pin 1.5mm pitch connector for the 3 LEDs (red, green, blue).

Nixie Tube Connector:

|pin|signal|
|----|----|
|1|anode|
|2|channel 0|
|3|channel 1|
|4|channel 2|
|5|channel 3|
|6|channel 4|
|7|channel 5|
|8|channel 6|
|9|channel 7|
|10|channel 8|
|11|channel 9|
|12|no connect|


LED Connector:

|pin|signal|
|----|----|
|1|Blue Positive (Anode)|
|2|Blue Negative (Cathode)|
|3|Green Positive (Anode)|
|4|Green Negative (Cathode)|
|5|Red Positive (Anode)|
|5|Red Negative (Cathode)|

Pin #1 is indicated by a dot.

## Bias Resistors

There are no bias resistors on this board. Make sure to include them with your driver.

## Dimensions

The board is 60mm wide x 75mm high. It is designed to have nixie tubes side-by-side at 60mm spacing.

The mounting holes are designed to accomodate up to a 1/4-20 inch cap screw (1/4 inch finished hole size). Note that the mounting hole positions are not symetric:

|Y|X|
|-----|-----|
|9mm |8.5mm|
|9mm |51.5mm|
|66mm |8.5mm|
|66mm |51.5mm|


## Manufacturing

If you don't have access to Altium Designer then you can take the the zip file in the output directory and just send that over to any regular PCB Manufacturer. Specify the board thickness (I used 0.092") and the color. This is a simple 2-layer board.

The Excel BOM file is a complete parts purchase list. There is a PDF of the schematics in the output directory for your reference.
