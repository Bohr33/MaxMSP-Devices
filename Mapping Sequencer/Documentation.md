#Mapping Sequencer
-
###Description
This device is an attempt to replicate sequencer capabilities found on modular devices where the control voltage signal from the sequencer can be sent to any control voltage input. For ableton, this translates to mapping capabilites. This device allows you to create maximum 16 step pattern and map the signal from the pattern to any mappable parameter in ableton. 

##Features
**Mapping** - 
Each device instance can be can be mapped to seven individual parameters. To access the other six parameters, click the icon to the far right of the visible map parameter. Each map also can be scaled individually in the same way Live's native mapping features work; a minimum %, and a maximum % (to invert the signal, raise the minimum to any value above the maximum).  
The scaling factors can be mapped and automated.

**Patterns** - 
You are also allotted 8 patterns for your device which will be saved with your live set. Use the clear button to clear the current selected pattern. Pattern selected can be automated and mapped. 
Note - A good way to make this feel more native is to set up clips on your track with automation on the pattern select. That way you can change the pattern select using MIDI clips and launch them like other clips.

**Bar Divison** - This controls the clock rate of the sequencer. The value is how many steps you want per 4/4 bar. Thus 16 is a step per 16th notes, 8 = 1/8 notes, etc. However, you are also allowed to do unusual divions like 7, 11, or anything else. This control can be automated and mapped.

**Swing %** - Controls the swing amount for every other note, no matter what division. This control effectively pushes the note that percentage of the alloted space further towards the next note. 0% is straight, 33% is 'perfect' triplet swing, 50% creates dotted 16ths. This control can be automated and mapped.

**Number of Steps** - Determines the number of steps the sequencer steps through. This control can be automated and mapped.

**Offset** - Offsets where the start of the sequence is. Effectively pushes the entire sequence relative to the clock. This control can be automated and mapped.

**Scale All** - Scales the control of every mapped parameter. Is useful for automating the depth of the entire device at once. This control can be automated and mapped.
