# Minerva-for-QL

A compact ROM for Sinclair QL.

Use a 27c512 to load Minerva firmware and update your computer.

The Minerva ROM is also useful for diagnosing RAM problems.

Update with two version SMD & THT

SMD:

![alt text](https://github.com/zeus074/Minerva-for-QL/blob/main/Images/minerva.jpg)

**Components:**

U1		AT27C512R-70JU

R1		10Kohm (0805)

R2		1Kohm (0805)

Q1		MMBT3904-T  (SOT23)

J1		PIN HEADER or 1544210-2 (SIL CONTACT Y1 THROUGH HOLE)

![alt text](https://github.com/zeus074/Minerva-for-QL/blob/main/Images/minerva_top.jpg)

THT:

![alt text](https://github.com/zeus074/Minerva-for-QL/blob/main/Images/Minerva_THT.jpg)

**Components:**

U1		27C512

R1		10Kohm

R2		1Kohm 

Q1		2N3904

J1		PIN HEADER or 1544210-2 (SIL CONTACT Y1 THROUGH HOLE)

![alt text](https://github.com/zeus074/Minerva-for-QL/blob/main/Images/Minerva_THT_Bottom.jpg)

**Directory**

Gerber : https://www.pcbway.com/project/shareproject/Minerva_ROM_fo_Sinclair_QL_644a941d.html
Gerber THT : https://www.pcbway.com/project/shareproject/Minerva_ROM_fo_Sinclair_QL_THT_Version_e9b613d4.html

IMG : Some pictures

Schematic: project outline

**How program**

Program the 27C512 memory before soldering it to the pcb, example with a plcc32-dip adapter and the TL866II, THT version not required the adapter.

The Minerva firmware can be found here:

https://dilwyn.qlforum.co.uk/qlrom/index.html

Once programmed you can solder the components such as the resistors and the transistor and finally the ROM and the pins.
