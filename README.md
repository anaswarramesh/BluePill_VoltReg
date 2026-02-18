# BluePill_VoltReg
PCB design of a circuit that  converts a 12 V DC input into regulated 9 V, 5 V, and 3.3 V outputs using linear voltage regulators.
Overview
The circuit converts a 12 V DC input into regulated 9 V, 5 V, and 3.3 V outputs using linear voltage regulators. The 12 V input directly supplied to  the 9 V regulator,Output of 9V regulator connected to input of 5 V regulators, and the 5 V output is used as the input to the 3.3 V regulator to lower the heat dissipation.A diode is connected from input 12V to 9V regulator to protect the regulators from reverse polarity.Input and output capacitors are connected to regulators as per the datasheet recommendations.

Components 

Designator
Description
Manufacturer
MPN
U3
9V Linear Regulator
STMicroelectronics
L7809CD2T-TR
U2
5V Linear Regulator
STMicroelectronics
L7805CD2T-TR
U1
3.3V LDO Regulator
AMS
AMS1117-3.3
C1, C2
0.33 µF Ceramic Cap
Murata
GRM219R71H334KA88D
C4, C5
0.1 µF Ceramic Cap
TDK
C2012X7R1H104K085AA
C3
10 µF Tantalum Cap
KEMET
T491B106K016AT
C6
22 µF Tantalum Cap
KEMET
T491B226K010AT
J1
12V DC Input Jack
CUI Devices
PJ-002AH-SMT-TR
J2
Output Header (4-pin)
Würth Elektronik
61300411121
D1
Reverse Polarity Protection Diode
ON Semiconductor
S1M-13-F


