# Geeetech_G2s_pro_Marlin-2.0.7.2
Marlin firmware for Geeetech G2s pro

Commands:

<!-- DELTA_ENDSTOP_ADJ -->
echo:  M666 X-0.42 Y-0.15 Z-0.17


M665
M666 Z1.6


/action:notification Calibration sd:0.189
.Height:194.09  Ex:+0.00  Ey:-1.33  Ez:-0.67  Radius:92.19
Save with M500 and/or copy to Configuration.h
Error:Z-Probe failed
Error:Z-Probe failed

.Height:194.20  Ex:+0.00  Ey:-0.28  Ez:-0.63  Radius:92.61
.Height:194.36  Ex:+0.00  Ey:-0.20  Ez:-0.64  Radius:92.86
.Height:194.00  Ex:+0.00  Ey:-0.76  Ez:-0.80  Radius:92.42

Probe offset
X:-25.00 Y:-20.80 Z:7.00 E:0.00 Count A:15474 B:13640 C:13187
X:-23.00 Y:-18.80 Z:4.80 E:0.00 Count A:15227 B:13540 C:13150


.Height:195.80  Ex:+0.00  Ey:-0.55  Ez:-0.46  Radius:94.00
.Height:195.80  Ex:+0.00  Ey:-0.55  Ez:-0.46  Radius:94.00

M665 H195.3


.Height:194.64  Ex:+0.00  Ey:-0.64  Ez:-0.38  Radius:94.29




echo:; Endstop adjustment:
echo:  M666 X0.00 Y-0.55 Z-0.46
echo:; Delta settings: L<diagonal rod> R<radius> H<height> S<segments per sec> XYZ<tower angle trim> ABC<rod trim>
echo:  M665 L196.00 R94.00 H195.00 S160.00 X0.70 Y0.05 Z-0.74 A0.00 B0.00 C0.00


M666 X0.00 Y-0.64 Z-0.38

M665 R94.29


#############
//action:notification Checking... AC
.Height:195.30  Ex:+0.00  Ey:+0.00  Ez:+0.00  Radius:94.00
Iteration : 01                                std dev:0.237
//action:notification Iteration : 01
Iteration : 02                                std dev:0.113
//action:notification Iteration : 02
Iteration : 03                                std dev:0.095
//action:notification Iteration : 03
Iteration : 04                                std dev:0.066
//action:notification Iteration : 04
Iteration : 05                                std dev:0.043
//action:notification Iteration : 05
Iteration : 06                                std dev:0.039
//action:notification Iteration : 06
Calibration OK                                rolling back.
//action:notification Calibration sd:0.039
.Height:194.59  Ex:+0.00  Ey:-0.65  Ez:-0.48  Radius:93.87
Save with M500 and/or copy to Configuration.h
SENDING:


X-30.60 Y-21.80 Z:1.80 E:0.00 Count A:11782 B:14258 C:14535
G1 X-30.60 Y-21.80 Z2.80 F5000


X-30.60 Y-21.80




Checking... AC
//action:notification Checking... AC
.Height:195.30  Ex:+0.00  Ey:+0.00  Ez:+0.00  Radius:94.00
Iteration : 01                                std dev:0.483
//action:notification Iteration : 01
Iteration : 02                                std dev:0.156
//action:notification Iteration : 02
Iteration : 03                                std dev:0.042
//action:notification Iteration : 03
Iteration : 04                                std dev:0.040
//action:notification Iteration : 04
Calibration OK                                rolling back.
//action:notification Calibration sd:0.040
.Height:195.08  Ex:+0.00  Ey:-0.74  Ez:-0.75  Radius:94.05
Save with M500 and/or copy to Configuration.h
SENDING:M500



#########################################################
.Height:192.10  Ex:+0.00  Ey:+0.00  Ez:+0.00  Radius:90.00
Iteration : 01                                std dev:2.557
//action:notification Iteration : 01
Iteration : 02                                std dev:0.994
//action:notification Iteration : 02
Iteration : 03                                std dev:0.508
//action:notification Iteration : 03
Iteration : 04                                std dev:0.463
//action:notification Iteration : 04
Iteration : 05                                std dev:0.189
//action:notification Iteration : 05
Iteration : 06                                std dev:0.159
//action:notification Iteration : 06
Iteration : 07                                std dev:0.081
//action:notification Iteration : 07
Calibration OK                                rolling back.
//action:notification Calibration sd:0.081
.Height:190.00  Ex:+0.00  Ey:-0.51  Ez:-0.62  Radius:93.91
Save with M500 and/or copy to Configuration.h



Iteration : 05                                std dev:0.074
//action:notification Iteration : 05
Calibration OK                                rolling back.
//action:notification Calibration sd:0.074
.Height:191.73  Ex:+0.00  Ey:-1.25  Ez:-0.98  Radius:94.18
Save with M500 and/or copy to Configuration.h
Error:Z-Probe failed
Error:Z-Probe failed

.Height:191.73  Ex:+0.00  Ey:-1.25  Ez:-0.98  Radius:94.18



Commands:
M502
M500
M501
G29 P1
G29 T
G29 S1
G29 F10.0 
G29 A
M851 Z-1.20
G28
G26 P10
