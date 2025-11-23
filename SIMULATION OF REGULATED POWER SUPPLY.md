# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
<img width="974" height="457" alt="image" src="https://github.com/user-attachments/assets/5029525d-eac4-4be5-adb7-b9f40f751b3c" />


## AC INPUT WAVEFORM:

<img width="973" height="494" alt="image" src="https://github.com/user-attachments/assets/abc72b10-fccf-470c-8f6d-dda9ada1574f" />

## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="975" height="493" alt="image" src="https://github.com/user-attachments/assets/6092d7c8-9498-4eea-af4e-4850005b06b0" />

## SIGNAL OUTPUT(WITH FILTER)


<img width="973" height="491" alt="image" src="https://github.com/user-attachments/assets/6b7385df-2c40-4ab1-95de-06569637e8ce" />

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 




## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
