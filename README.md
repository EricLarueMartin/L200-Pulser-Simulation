# L200-Pulser-Simulation
LT Spice simulations for injecting charge for the LEGEND 200 electronics chain
To compare outputs the inputs need to be adjusted to be similar. Account for the difference in detector capacitance and pulse injection capacitance when pulsing through the HV line vs signal line, and be sure to account for the drop from the resistor network ont he HV pulse line.
The current source should have a current that results in the same total charge.
For example, the following are all 5 pC using a 2 pC detector:

0.5 V on the HV pulse line.

5 V on the LMFE pulse line.

250 uA with 1 ns rise, fall, and on time.
