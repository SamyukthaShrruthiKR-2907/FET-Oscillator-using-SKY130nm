I am a passionate 2nd year ECE Student in SRM Easwari Engineering College with a CGPA of 9.3% and my curiousity to learn new things is always high.
I have designed FET based RC Phase Shift Oscillator using esim and sky130pdk.
I first designed the circuit in Esim and then downloaded sky130pdk and then did the process required to generate the output
I initially used BJT like I mentioned in my literature survey but got many errors like unknown subcircuit in npn transistor line and then I changed
it to N-channel MOSFET and got the output waveform successfully 
I initially used capacitor in sky130 but got many errors like can't find model in sky130_fd_pr and then I just mentioned the values of the capacitor
Note : I used npn transistor initially but wasn't able to get the output waveform in spice so I replaced N-Channel MOSFET and in .cir file I renamed it as
sky130_fd_pr__nfet_01v8 w=1 l=0.5.And the reference waveform in literature survey is for RC phase shift oscillator using BJT,but I have changed it to FET
when I was practically experimenting using Esim and Sky130pdk 
So I kindly request you to please consider my circuit using FET and allow me to make changes to literature survey.
Thank You	
