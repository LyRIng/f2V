## f2V Frequency to DC Signal Input Module
(original version 2009 - updated 09.2022)

### Introduction
The f2V board from [L&R Ingeniería](https://www.lyringenieria.com.ar/language/es/) is an auxiliary peripheral board designed to measure RPM in permanent magnet generators (specially from small wind turbines) by isolating and converting the variable frequency and voltage from a pair of phases from the PM generator into a variable dc voltage, proportional to frequency, to a range readable from two 0- 5 Vdc A/D converter channels. Since the n=RPM is related to the frequency via the pole-pair equation n=60f/p, calibrating the Vo output to read RPM is possible.
The module uses a small pcb transformer (turns ratio typical reduction of 6 to 18) and an [LM2917](https://www.ti.com/lit/ds/symlink/lm2907-n.pdf) frequency to voltage IC. It works from an unregulated 12 Vdc or can be supplied with +5V using a reduced R1 value.  

In the **/schem** directory a schematic of the circuit is described. The board is available with or without a DIN-R28T plastic cabinet, contact L&R Ing. for details. 


