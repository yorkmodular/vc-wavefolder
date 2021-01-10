## Voltage-controlled Lockhart Wavefolder

Finally, a voltage-controlled version of the Lockhart wavefolder. You can hear a short, albeit rather nasty quality, recording of it [here](https://soundcloud.com/yorkmodular/voltage-controlled-lockhart-wavefolder).  

Users of the 2HP module would have noted that the level of the incoming signal has an effect on the sound, so with this in mind I put a differential pair in the way to allow voltage control of the input signal. A similar input is present for the comparator on the square-wave output to make it rather more versatile. The +/- controls which are present on the 2HP module are gone - the voltage-control aspect renders them somewhat obsolete.

The 'main' output gives the folded waveform whilst the 'square' output will, under certain circumstances, give an arrhythmic pulse train which can be used either as a modulation source or a square-wave oscillator in its own right. The two potentiometers control the input levels of the signal and CV - with particularly hot CV levels you can get some extremely gnarly sounds as the transistors saturate (but see below)

Works best with sine or triangle-based waveforms but there's nothing to stop you putting, well, anything into it - altering the level of the input signal can lead to some very interesting filter-like effects. Through judicious use of control voltage you can achieve VCA-like effects too.  

Finally, a couple of technical notes:

* The input signal must be at least 1.4V p-p - this is due to the voltage drops created by the two transistors in the circuit; the practical upshot is that this module will not work with audio signals unless they're amplified (a lot!) whereas most VCOs and CV generators will work just fine. 
* For best results, transistors Q1 and Q2 should be matched - this isn't as essential as it would be in, say, a VCO, but better matching yields better results. Ideally, R11 and R12 should be matched as well - using 1% resistors here is good enough.
* Apropos of R11 and R12, their values are not set in stone - using higher values may reduce distortion at higher CV levels; anything less than 10k will work.
* The trimmer adjusts the offset of the differential pair.
* **THERE IS AN ERROR ON THE SCHEMATIC FOR THIS REVISION OF THE BOARD** - R1 should be a 100nF ceramic capacitor rather than a 1k resistor. This will be corrected in future runs.

**Note that the completed module is 40mm deep**, as measured from the rear of the faceplate to the rearmost edge of the power socket - please make sure your case is deep enough to accommodate it.

