# LFSR -Linear Feedback Shift Register
## MATLAB CODE for LFRS
### This MATLAB Code work for any length of LFSR with given taps (feedback polynomial) -Universal, There are three files LFSRnik1.m an LFSRnik2.m, LFSRnik3.m
### LFSRnik1
This function will return all the states of LFSR and will check Three fundamental Property of LFSR 
(1) Balance Property (2) Runlength Property (3) Autocorrelation Property

### LFSRnik2
This function will return only generated sequence will all the states of LFSR, no verification of properties are done
here. Use this function to avoid verification each time you execute the program.

### LFSRnik3 Faster
seq = LFSRnik3(s,t,N)
this function generates N bit sequence only. This is faster then other two functions, as this does not gives each state of LFSR

## Tips
* If you want to use this function in middle of any program, use LFSRnik2 or LFSRnik1 with verification =0. 
* If you want to make it fast for long length of LFSR,use LFSRnik3.m 

______________________________________
If any doubt, confusion or feedback please contact me
### Nikesh Bajaj
### http://nikeshbajaj.in
bajaj.nikkey@gmail.com
Asst. Professor at Lovely Profesional University
Masters from Aligarh Muslim University,India
