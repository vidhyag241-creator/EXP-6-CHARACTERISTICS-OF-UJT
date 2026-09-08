# EXP-6-CHARACTERISTICS-OF-UJT
# AIM
To plot the characteristics of UJT (2N2446) and to determine the intrinsic stand-off ratio from the graph.
# APPARATUS REQUIRED
S. No.	Components	Specification	Qty.
1	UJT	2N2446	1
2	Resistor	1 kΩ	2
3	Regulated dual power supply	Dual (0–30) V	1
4	Voltmeter	0–30 V	2
5	Ammeter	0–30 mA	1
6	Connecting wires & Bread Board	As required	As required
# THEORY
UJT is the Uni Junction Transistor. It is a three-terminal device. The three terminals are emitter, base 1 and base 2. The equivalent circuit consists of two resistors, one variable resistor and one fixed resistor. The ratio of internal resistance is referred to as intrinsic stand-off ratio (η). It is defined as the ratio of the variable resistance to the total resistance.
Due to the existing PN junction, there will be a voltage drop. If voltage is applied to the emitter, the device will not turn on until the input voltage is less than the drop across the diode plus the drop at the variable resistance R1.
When the device is turned on, holes move from emitter to base resulting in a current flow. Due to the sudden increase in charge concentration in the base region, conductivity increases. This causes a drop at base 1. If we further increase the emitter voltage, the device undergoes saturation. Hence UJT has three operating regions: (i) cut-off region, (ii) negative resistance region and (iii) saturation region.
# CIRCUIT DIAGRAM
 <img width="579" height="640" alt="image" src="https://github.com/user-attachments/assets/bfe32517-f8d7-4a2d-93aa-4c341842d36a" />

Reference circuit diagram reproduced from the supplied record.
# UJT EQUIVALENT CIRCUIT
The UJT equivalent circuit consists of the inter-base resistance RBB divided into two portions, RB1 and RB2, with the emitter PN junction represented by a diode.
# UJT CHARACTERISTIC CURVE
The emitter characteristic is plotted between emitter voltage VE and emitter current IE. The curve contains the cut-off region, peak point, negative resistance region, valley point and saturation region.
 
Reference model graph from the supplied record.

<img width="600" height="456" alt="image" src="https://github.com/user-attachments/assets/0fa9eb52-ecef-495b-bac4-2ea562291024" />

# PROCEDURE
1. Set up the circuit as shown in the circuit diagram.
2. Give the power supply.
3. By varying the input power supply, take the values of voltage (VE) and current (IE).
4. Plot the graph between VE and IE.
5. Find the intrinsic stand-off ratio from the graph.
8. FORMULA
VBB = 12 V
VP = VD + ηVBB
Therefore, η = (VP − VD) / VBB
Find the value of VP from the graph and calculate η. Similarly, determine the intrinsic stand-off ratio for all values of VBB.
# OBSERVATION
<img width="608" height="769" alt="image" src="https://github.com/user-attachments/assets/4681f8cf-d626-483a-8a7b-b0d291e7f5ed" />

Simulation Results:

For VBB = 5 V and VBB = 8 V
VBB = 5 V		VBB = 8 V	
VE (V)	IE (mA)	VE (V)	IE (mA)
			
			
# CALCULATION
<img width="446" height="555" alt="image" src="https://github.com/user-attachments/assets/e21725c2-c21e-45b3-bd71-311dfc81848b" />



For VBB = 5 V:
Peak voltage, VP = 3.3 V
Diode voltage, VD = 3.3 − 2.8 = 0.5 V
η = (VP − VD) / VBB
η = (3.3 − 0.5) / 5 = 2.8 / 5 = 0.56
Therefore, η = 0.56
# RESULT
The characteristics of UJT were plotted and the intrinsic stand-off ratio was found.
Intrinsic stand-off ratio, η = 0.56
Peak voltage, VP = 3.3 V
