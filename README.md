# NMOS_-OUTPUT_IMPEDENCE
output impedance of various configurations


CASE 1: 
ac analysis
Set the values:  VGS= 900 mV ;    VBS= 0 V
VDS= (vsin) DC magnitude = 900 mV , AC magnitude = 1 V
Plot ID wrt frequency varying frequency from 1 Hz to 100 MHz :-  ID- VDS curve
plot reciprocal of ID curve to get rout
RESULT: rout = 26.19 kΩ


CASE 2:
dide connected load
connect drain and gate terminals of NMOS
Set the values:  VBS= 0V ;    VGS = VDS
VDS= (vsin) DC magnitude = 900 mV , AC magnitude = 1 V
Plot ID wrt frequency varying frequency from 1 Hz to 100 MHz :-  ID- VDS curve
plot reciprocal of ID curve to get req = [rout || (1/gm)]
RESULT: Rout = 1.0456 kΩ


CASE 3:
diode connected load with VSB as vsin
connect drain and gate terminals of NMOS
Set the values:
VDS= (vsin) DC magnitude = 900 mV , AC magnitude = 1 V
VBS= (vsin) DC magnitude = 0 V , AC magnitude = 1 V
Plot ID wrt frequency varying frequency from 1 Hz to 100 MHz :-  ID- VDS curve
plot reciprocal of ID curve to get req = [rout || 1/ (gm + gmb )]
RESULT: Rout = 811.7 Ω
