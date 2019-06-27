# Printed Circuit Board (PCB)

Instead of using a stripboard to make the electrical connections for the fixed set of inputs, a printed circuit board will be made for the actual product itself.

Based on the circuit diagram used for the prototype, most components were preserved for the build of the PCB except for the touch sensors. The PCB will have a self-made touch sensor circuit on it by making use of the reference circuit provided by the TTP223 IC datasheet.

The files required to produce the PCB can be downloaded here:  
[https://github.com/bit-board/bitboard/blob/master/code/bitboard_PCB.zip](https://github.com/bit-board/bitboard/blob/master/code/bitboard_PCB.zip)

## PCB Schematic
The following schematic file details every pin connection required for the implementation of the inputs:

[![Image](https://github.com/bit-board/bitboard-docs/raw/master/images/PCB_Schematic.PNG)](https://github.com/bit-board/bitboard-docs/raw/master/images/PCB_Schematic.PNG)

## PCB Layout
After creating the schematic file, the layout of the components on the PCB is optimised to reduce the wire lengths as shown here:

[![Image2](https://github.com/bit-board/bitboard-docs/raw/master/images/PCB_Layout.PNG)](https://github.com/bit-board/bitboard-docs/raw/master/images/PCB_Layout.PNG)

## Benefits
By using a printed circuit board, the area required can be further reduced since physical wires can be omitted and some through hole components can be replaced with surface mount devices, which are smaller in size.

Another benefit of having a more compact circuitry for the inputs is that the electrical connections are more secure, hence increasing the reliability of the product.
