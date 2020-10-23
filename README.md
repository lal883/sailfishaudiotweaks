# Sailfish OS Audio-Tweaks

An effort to run a system wide DSP on Sailfish OS, to hopefully have better audio output.

Main objective is to be able to process the sound with appropriate corrections so that the connected headphones sound close to ideal and music is heard as it was actually recorded. The technicality behind this and the need for it is well docuemented in AutoEQ project - reference [2]. A second objective is to try make the loud seaker of the phone sound better. And the third objective is to hopefully convolve the sound signals to possibly create a virtual surround environment when using headphones. 

### References
[1] https://github.com/bmc0/dsp - The DSP software we are to run on Sailfish OS. 

[2] https://github.com/jaakkopasanen/AutoEq - The AutoEQ project.

### Step 1 Installing the DSP
The DSP has a number of interesting functions. For the first objective, only the LADSPA (Linux Audio Developer's Simple Plugin API) plugin is needed. I don't know yet on how to achieve the remaining two objectives.
