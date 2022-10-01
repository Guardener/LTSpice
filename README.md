# LTSpice
Group Homework Assignment: Bulk Cap Simulation

Also scratch space for all SPICE simulations for the Guardener

To update the LTSpice schematic with the ZLLS500TA Schottky Diode, either move the copy of `standard.dio` to `C:\Users\<USER_NAME>\Documents\LTspiceXVII\lib\cmp\standard.dio` and reopen LTSpice, or append the following to your LTSpice's diode library:  
`.model ZLLS500TA D(Is=610n Rs=0.27 N=1.03 Eg=0.63 Xti=2 Cjo=71p Vj=0.6 M=0.36 Iave=0.70 Vpk=40.0 Isr=1.4u Nr=2 Ikf=0.32 Bv=42 Ibv=200u Tt=3n Trs1=4M mfg=DiodesInc type=Schottky)`
