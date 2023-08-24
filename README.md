# Spice-Project
1. Simulation of symmetrical and skewed CMOS inverter, and pass transistor:
a) Do an analysis to find out the PMOS to NMOS size ratio of the minimum-sized CMOS inverter to have equal rise
and fall time. Simulate the static VTC of that inverter, and find out signalling threshold values (VIL, VIH, VOL, VOL)
using the slope = –1 criterion from the VTC. Write down high and low noise margins, and the noise immunity of
the inverter. Also, simulate the static VTC of an inverter which is sized S times the minimum-sized inverter (both
NMOS and PMOS are S times the size of the corresponding NMOS and PMOS of the minimum-sized inverter) for
S = 1,2,4, and plot all VTCs in a single graph with clear legends indicating how the sizing affects the VTC.
b) Carry out transient analysis to find out the rise time and fall time delays of a CMOS inverter sized S =1,2,4, when
(i) no external capacitor is attached, (ii) an external capacitor of 5 pF is attached to the output node. Plot the timing
characteristics in a single graph with clearly labelled axes and legends for each value of S and for part (i) and (ii),
and tabulate the rise time and fall time delays obtained. Find out the current drawn from the power supply in all
cases as the input voltage is swept slowly w.r.t the output, and plot the current vs input voltage in a single graph
with clear legends for each value of S and for part (i) and (ii). Calculate and tabulate the static and dynamic power
dissipations in all cases, i.e., for each value of S and for part (i) and (ii).
c) Simulate the static VTC of an inverter in which the NMOS is sized Kn times the size of the corresponding NMOS
of the minimum-sized inverter for Kn = 1,2,4, keeping the size of the PMOS the same as that of the corresponding
PMOS of the minimum-sized inverter. Similarly, simulate the static VTC of an inverter in which the PMOS is sized
Kp times the size of the corresponding PMOS of the minimum-sized inverter for Kp = 1,2,4, keeping the size of the
NMOS the same as that of the corresponding NMOS of the minimum-sized inverter. Plot all these VTCs in a single
graph with clear legends indicating how sizing of skewed CMOS inverter affects the VTC.
d) Carry out transient analysis to find out the rise time and fall time delays in each case when (i) no external capacitor
is attached, (ii) an external capacitor of 5 pF is attached to the output node. Plot the timing characteristics in a single
graph with clearly labelled axes and legends for each case and for part (i) and (ii), and tabulate the rise time and fall
time delays obtained. Also, find out the current drawn from the power supply in all cases as the input voltage is
swept slowly w.r.t the output, and plot the current vs input voltage in a single graph with clear legends for each case
and for part (i) and (ii). Calculate and tabulate the static and dynamic power dissipations in all cases.
e) Create a circuit consisting of a NMOS pass transistor having size Kn=1,2,4, driving an NMOS inverter of minimum
size connected to the source/drain of the NMOS pass transistor (choose the resistor value in the NMOS inverter to
have equal rise and fall times which also should be equal to that of a minimum-sized symmetrical CMOS inverter).
Apply an input signal to the source/drain of the NMOS pass transistor of which the gate is connected to VDD, and
plot the voltage waveform at the input and output of the inverter and tabulate the delay at both the input and output
of the inverter for all values of Kn, when the input signal varies slowly from (i) low to high, (ii) high to low. From
these results, plot the resistance of the pass transistor vs input voltage in a single graph with clearly labelled axes
and legends for all values of Kn.
Do another simulation to plot the voltage waveform at the input and output of the inverter and tabulate the delay at
both the input and output of the inverter for all values of Kn, when the source/drain of the NMOS pass transistor is
connected to VDD and the input signal which is applied to the gate of the NMOS pass transistor varies slowly from
(i) low to high, (ii) high to low. From these results, plot the resistance of the pass transistor vs input voltage in a
single graph with clearly labelled axes and legends for all values of Kn.

