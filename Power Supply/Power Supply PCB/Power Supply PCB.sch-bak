EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "POWER SUPPLY"
Date "2021-10-24"
Rev "V1"
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Device:D_Bridge_+-AA D1
U 1 1 61743090
P 2850 2900
F 0 "D1" H 3050 3050 50  0000 L CNN
F 1 "Diode RF" H 3050 2750 50  0000 L CNN
F 2 "Diode_THT:Diode_Bridge_Vishay_GBL" H 2850 2900 50  0001 C CNN
F 3 "~" H 2850 2900 50  0001 C CNN
	1    2850 2900
	1    0    0    -1  
$EndComp
$Comp
L Device:CP1 C1
U 1 1 6174430C
P 3500 3200
F 0 "C1" H 3615 3246 50  0000 L CNN
F 1 "1000uf/25v" H 3615 3155 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D10.0mm_P3.50mm" H 3500 3200 50  0001 C CNN
F 3 "~" H 3500 3200 50  0001 C CNN
	1    3500 3200
	1    0    0    -1  
$EndComp
$Comp
L Regulator_Linear:LM7812_TO220 U1
U 1 1 61744BA0
P 4250 2900
F 0 "U1" H 4250 3142 50  0000 C CNN
F 1 "12v Regulator" H 4250 3051 50  0000 C CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 4250 3125 50  0001 C CIN
F 3 "https://www.onsemi.cn/PowerSolutions/document/MC7800-D.PDF" H 4250 2850 50  0001 C CNN
	1    4250 2900
	1    0    0    -1  
$EndComp
$Comp
L Device:R R1
U 1 1 61745693
P 5650 3050
F 0 "R1" H 5580 3004 50  0000 R CNN
F 1 "330R" H 5580 3095 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0309_L9.0mm_D3.2mm_P15.24mm_Horizontal" V 5580 3050 50  0001 C CNN
F 3 "~" H 5650 3050 50  0001 C CNN
	1    5650 3050
	-1   0    0    1   
$EndComp
$Comp
L Device:LED D2
U 1 1 61745B6F
P 5650 3550
F 0 "D2" V 5689 3432 50  0000 R CNN
F 1 "LED" V 5598 3432 50  0000 R CNN
F 2 "LED_THT:LED_D3.0mm" H 5650 3550 50  0001 C CNN
F 3 "~" H 5650 3550 50  0001 C CNN
	1    5650 3550
	0    -1   -1   0   
$EndComp
$Comp
L Connector:Conn_01x02_Female J1
U 1 1 61746326
P 1700 2900
F 0 "J1" H 1592 2575 50  0000 C CNN
F 1 "Conn_01x02_Female" H 1592 2666 50  0000 C CNN
F 2 "Connector_Phoenix_MC_HighVoltage:PhoenixContact_MC_1,5_2-GF-5.08_1x02_P5.08mm_Horizontal_ThreadedFlange" H 1700 2900 50  0001 C CNN
F 3 "~" H 1700 2900 50  0001 C CNN
	1    1700 2900
	-1   0    0    1   
$EndComp
$Comp
L Connector:Barrel_Jack J2
U 1 1 61746D2C
P 6400 3150
F 0 "J2" H 6457 3475 50  0000 C CNN
F 1 "DC Output" H 6457 3384 50  0000 C CNN
F 2 "Connector_BarrelJack:BarrelJack_CUI_PJ-063AH_Horizontal" H 6450 3110 50  0001 C CNN
F 3 "~" H 6450 3110 50  0001 C CNN
	1    6400 3150
	1    0    0    -1  
$EndComp
$Comp
L Device:CP1 C2
U 1 1 6174A0B3
P 5000 3150
F 0 "C2" H 5115 3196 50  0000 L CNN
F 1 "1000uf/25v" H 5115 3105 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D10.0mm_P3.50mm" H 5000 3150 50  0001 C CNN
F 3 "~" H 5000 3150 50  0001 C CNN
	1    5000 3150
	1    0    0    -1  
$EndComp
Wire Wire Line
	3150 2900 3500 2900
Wire Wire Line
	3500 2900 3500 3050
Wire Wire Line
	3500 2900 3950 2900
Connection ~ 3500 2900
Wire Wire Line
	4550 2900 5000 2900
Wire Wire Line
	5000 2900 5000 3000
Wire Wire Line
	5000 2900 5650 2900
Connection ~ 5000 2900
Wire Wire Line
	5650 3200 5650 3400
Wire Wire Line
	1900 2800 2300 2800
Wire Wire Line
	1900 2900 2050 2900
Wire Wire Line
	2050 2900 2050 3300
Wire Wire Line
	2050 3300 2850 3300
Wire Wire Line
	2850 3300 2850 3200
$Comp
L power:GND #PWR0101
U 1 1 6174C69D
P 5000 3500
F 0 "#PWR0101" H 5000 3250 50  0001 C CNN
F 1 "GND" H 5005 3327 50  0000 C CNN
F 2 "" H 5000 3500 50  0001 C CNN
F 3 "" H 5000 3500 50  0001 C CNN
	1    5000 3500
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0102
U 1 1 6174CA54
P 5650 3800
F 0 "#PWR0102" H 5650 3550 50  0001 C CNN
F 1 "GND" H 5655 3627 50  0000 C CNN
F 2 "" H 5650 3800 50  0001 C CNN
F 3 "" H 5650 3800 50  0001 C CNN
	1    5650 3800
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0103
U 1 1 6174CC5A
P 4250 3400
F 0 "#PWR0103" H 4250 3150 50  0001 C CNN
F 1 "GND" H 4255 3227 50  0000 C CNN
F 2 "" H 4250 3400 50  0001 C CNN
F 3 "" H 4250 3400 50  0001 C CNN
	1    4250 3400
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0104
U 1 1 6174CE4D
P 3500 3500
F 0 "#PWR0104" H 3500 3250 50  0001 C CNN
F 1 "GND" H 3505 3327 50  0000 C CNN
F 2 "" H 3500 3500 50  0001 C CNN
F 3 "" H 3500 3500 50  0001 C CNN
	1    3500 3500
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0105
U 1 1 6174D039
P 2450 3000
F 0 "#PWR0105" H 2450 2750 50  0001 C CNN
F 1 "GND" H 2455 2827 50  0000 C CNN
F 2 "" H 2450 3000 50  0001 C CNN
F 3 "" H 2450 3000 50  0001 C CNN
	1    2450 3000
	1    0    0    -1  
$EndComp
Wire Wire Line
	5650 3700 5650 3800
Wire Wire Line
	5000 3300 5000 3500
Wire Wire Line
	4250 3200 4250 3400
Wire Wire Line
	3500 3350 3500 3500
Wire Wire Line
	2450 3000 2450 2900
Wire Wire Line
	2450 2900 2550 2900
Wire Wire Line
	6700 3050 6800 3050
Wire Wire Line
	6800 3050 6800 2750
Wire Wire Line
	6800 2750 5650 2750
Wire Wire Line
	5650 2750 5650 2900
Connection ~ 5650 2900
$Comp
L power:GND #PWR0106
U 1 1 61751E3F
P 6800 3400
F 0 "#PWR0106" H 6800 3150 50  0001 C CNN
F 1 "GND" H 6805 3227 50  0000 C CNN
F 2 "" H 6800 3400 50  0001 C CNN
F 3 "" H 6800 3400 50  0001 C CNN
	1    6800 3400
	1    0    0    -1  
$EndComp
Wire Wire Line
	6700 3250 6800 3250
Wire Wire Line
	6800 3250 6800 3400
$Comp
L Switch:SW_DIP_x01 SW1
U 1 1 61757079
P 2550 2200
F 0 "SW1" H 2550 2467 50  0000 C CNN
F 1 "Switch" H 2550 2376 50  0000 C CNN
F 2 "Button_Switch_THT:SW_DIP_SPSTx01_Slide_9.78x4.72mm_W7.62mm_P2.54mm" H 2550 2200 50  0001 C CNN
F 3 "~" H 2550 2200 50  0001 C CNN
	1    2550 2200
	1    0    0    -1  
$EndComp
Wire Wire Line
	2300 2300 2250 2300
Wire Wire Line
	2250 2300 2250 2200
Wire Wire Line
	2300 2300 2300 2800
Wire Wire Line
	2850 2200 2850 2600
$EndSCHEMATC
