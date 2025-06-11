# Pico W DIN rail enclosure

FreeCAD project for a DIN rail case housing a Raspberry Pi Pico (W). 

Features:
* M2 screw standoffs for the Pico
* two spots for two contact terminal blocks (I went for [WJ126V-5.0-2P](https://www.lcsc.com/product-detail/C8404.html), other Phoenix PT-style should also work)
* three JST XH 3-pin connectors at the front for additional connections (these are soldered to a simple strip board and fit into the case)
* fully constrained
* partially parameterized

The case is heavily inspired by https://www.printables.com/model/1089412-esp32-din-rail-enclosure-rs485. I did lack the options to easily extend this and adapt it to my needs (in this project it houses a Pico W running ESPhome reading S0 pulses from an energy meter in addition to several water meters). And it was a good opportunity to get started in FreeCAD ;-)

If you find anything could be improved, feel free to open a PR.
