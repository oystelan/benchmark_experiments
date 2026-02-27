# Note on wave paddle motion
the files *_waveinput.dat provides the wave paddle motions, in a format that is directly readable by CFDwavemaker (https://github.com/oystelan?tab=repositories). 
First column: time [sec]
Second column: wave paddle motions [m], derived from the voltage signal on the wave maker.
Third column: wave paddle velocity [m/s] derived from the position signal by numerical derivation (np.gradient)
Forth column: only zeros and not used, so ignore this column. provided because of formating needs when reading into CFDwavemaker