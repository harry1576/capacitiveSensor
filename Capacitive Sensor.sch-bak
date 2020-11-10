EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Timer:TLC555 U1
U 1 1 5FA921E9
P 5650 3700
F 0 "U1" H 5800 4150 50  0000 C CNN
F 1 "TLC555" H 5750 4100 50  0000 L TNN
F 2 "Package_SO:SOIC-8-1EP_3.9x4.9mm_P1.27mm_EP2.29x3mm" H 5700 3450 50  0001 L CNN
F 3 "http://www.ti.com/lit/ds/symlink/tlc555.pdf" H 6300 3150 50  0001 C CNN
	1    5650 3700
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0101
U 1 1 5FA94F93
P 5650 4150
F 0 "#PWR0101" H 5650 3900 50  0001 C CNN
F 1 "GND" H 5655 3977 50  0000 C CNN
F 2 "" H 5650 4150 50  0001 C CNN
F 3 "" H 5650 4150 50  0001 C CNN
	1    5650 4150
	1    0    0    -1  
$EndComp
Wire Wire Line
	5650 4000 5650 4150
$Comp
L Device:R R1
U 1 1 5FA9575E
P 4950 3350
F 0 "R1" H 4800 3400 50  0000 L CNN
F 1 "R" H 4800 3300 50  0000 L CNN
F 2 "Resistor_SMD:R_0603_1608Metric" V 4880 3350 50  0001 C CNN
F 3 "~" H 4950 3350 50  0001 C CNN
	1    4950 3350
	1    0    0    -1  
$EndComp
Connection ~ 5650 3200
Wire Wire Line
	5650 3200 5650 3300
Wire Wire Line
	6150 3500 6150 3200
Wire Wire Line
	6150 3200 5650 3200
Wire Wire Line
	5150 3800 5100 3800
Wire Wire Line
	5150 3700 5100 3700
Wire Wire Line
	5100 3700 5100 3800
Connection ~ 5100 3800
$Comp
L Device:R R2
U 1 1 5FAA3E43
P 4950 3650
F 0 "R2" H 4800 3700 50  0000 L CNN
F 1 "R" H 4800 3600 50  0000 L CNN
F 2 "Resistor_SMD:R_0603_1608Metric" V 4880 3650 50  0001 C CNN
F 3 "~" H 4950 3650 50  0001 C CNN
	1    4950 3650
	1    0    0    -1  
$EndComp
Wire Wire Line
	4950 3500 5150 3500
Connection ~ 4950 3500
Wire Wire Line
	4950 3200 5650 3200
Wire Wire Line
	4950 3800 5100 3800
Wire Wire Line
	4950 4150 5650 4150
Connection ~ 5650 4150
$Comp
L Device:C C1
U 1 1 5FAAB15B
P 5950 3050
F 0 "C1" V 6202 3050 50  0000 C CNN
F 1 "C" V 6111 3050 50  0000 C CNN
F 2 "Capacitor_SMD:C_0603_1608Metric" H 5988 2900 50  0001 C CNN
F 3 "~" H 5950 3050 50  0001 C CNN
	1    5950 3050
	0    -1   -1   0   
$EndComp
Wire Wire Line
	5650 3050 5650 3200
$Comp
L power:+3V3 #PWR0102
U 1 1 5FA95FE1
P 5650 3050
F 0 "#PWR0102" H 5650 2900 50  0001 C CNN
F 1 "+3V3" H 5665 3223 50  0000 C CNN
F 2 "" H 5650 3050 50  0001 C CNN
F 3 "" H 5650 3050 50  0001 C CNN
	1    5650 3050
	1    0    0    -1  
$EndComp
Wire Wire Line
	5800 3050 5650 3050
Connection ~ 5650 3050
$Comp
L power:GND #PWR0103
U 1 1 5FAB1081
P 6100 3050
F 0 "#PWR0103" H 6100 2800 50  0001 C CNN
F 1 "GND" V 6105 2922 50  0000 R CNN
F 2 "" H 6100 3050 50  0001 C CNN
F 3 "" H 6100 3050 50  0001 C CNN
	1    6100 3050
	0    -1   -1   0   
$EndComp
Text Notes 4800 4500 0    50   ~ 0
t1 (output high) = 0.693 (Ra + Rb) C                                                                                             
Text Notes 4800 4600 0    50   ~ 0
t2 (output low) = 0.693 (Rb) C
Text Notes 4600 3350 0    50   ~ 0
Ra\n
Text Notes 4600 3700 0    50   ~ 0
Rb
Text GLabel 6300 3700 2    50   Output ~ 0
555_Output
Wire Wire Line
	6150 3700 6300 3700
Text Notes 4600 4000 0    50   ~ 0
C
Text GLabel 4900 3900 0    50   Output ~ 0
C+
Text GLabel 4900 4000 0    50   Output ~ 0
C-
Wire Wire Line
	4900 4000 4950 4000
Wire Wire Line
	4950 4000 4950 4150
Wire Wire Line
	4900 3900 4950 3900
Wire Wire Line
	4950 3900 4950 3800
Connection ~ 4950 3800
$Comp
L Connector_Generic:Conn_01x03 J1
U 1 1 5FAC5899
P 7200 3250
F 0 "J1" V 7164 3062 50  0000 R CNN
F 1 "Conn_01x03" V 7073 3062 50  0000 R CNN
F 2 "Connector_Molex:Molex_CLIK-Mate_502386-0370_1x03-1MP_P1.25mm_Horizontal" H 7200 3250 50  0001 C CNN
F 3 "~" H 7200 3250 50  0001 C CNN
	1    7200 3250
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR0104
U 1 1 5FAC6A66
P 7200 3500
F 0 "#PWR0104" H 7200 3250 50  0001 C CNN
F 1 "GND" V 7205 3327 50  0000 C CNN
F 2 "" H 7200 3500 50  0001 C CNN
F 3 "" H 7200 3500 50  0001 C CNN
	1    7200 3500
	1    0    0    -1  
$EndComp
Wire Wire Line
	7200 3500 7200 3450
$Comp
L power:+3V3 #PWR0105
U 1 1 5FAC8431
P 7100 3500
F 0 "#PWR0105" H 7100 3350 50  0001 C CNN
F 1 "+3V3" V 7100 3700 50  0000 C CNN
F 2 "" H 7100 3500 50  0001 C CNN
F 3 "" H 7100 3500 50  0001 C CNN
	1    7100 3500
	-1   0    0    1   
$EndComp
Wire Wire Line
	7100 3500 7100 3450
Text GLabel 7300 3550 3    50   Output ~ 0
555_Output
Wire Wire Line
	7300 3550 7300 3450
NoConn ~ 6150 3800
$EndSCHEMATC
