# ltspice_modelgen
A spice VDMOS model generator

![Image](examples/diode_VDMOS.jpg)

# Howto

1. Get the datasheet of the MOSFET.
2. Enter the name and the type of the MOSFET.

8. Press generate and copy the line.

# Usage in LtSpice
Press the button for a spice command and put the model line there. You can put the line somewhere on your schematic. It should look like

    .model 20N60C3 VDMOS (Vto=3.000 Kp=5.413 Rd=0.170 Rs=0.020 Rg=0.540 Is=1.00E-12 Cgs=2.79E-9 Cgdmin=7.00E-12 Cgdmax=3.00E-9 a=2.000 Cjo=7.00E-9 Vtotc=-4.00E-3 tt=531.00E-9 Bex=-1.5)

Put a new NMOS on the Schematic and change the modelname to the name of the MOSFET model.

