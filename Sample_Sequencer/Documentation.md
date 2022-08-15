##Sample Sequencer (V2)

###Description
The Sample Sequencer was created in order to make chopping audio files for expiremental audio easier, and more fun in Live. This device allows you upload an audio file from within live, then sequencer portions of the audio file based on the parameters set on each step. To begin upload a file to the devie, drap and drop an audio file into the step preview window on the far right of the device. 

##Features
 - 3 Clock Modes
 - Tuned and Untuned Playback Modes
 - 8 Unique Patterns
 - 8 Unique Steps per pattern
 - ADSR Control for each step
 - Swing Capabilites (Rigid Mode)
 - Sample Step Preview Window and Playback Cursor

 -
 

Each step contains the following parameters...

**On/Off Toggle** - Enables or disables a step's playback. If a step is turned off, then the clock will still play through this step with the proper duration, but no audio will play. This is useful for putting rests in your sequence.

**Reverse Toggle** - Enables or disables reverse playback of the selected step. If toggled on, then all length adjustments displayed on the step preview window will also be reversed.

**Step Indicator** - This is the button on the top right of each step. Whenever a step begins playback, this will light up, indicating its response. 

**Start %** - This dial determines where in the sample you would like to begin playback for the selected step, as a percentage of the entire sample. When the sequencer is not playing, editing this will be displayed in the preview window.

**Playback** - This dial controls at what speed you would like the sample to playback. Depending on which playback mode is selected, this can either be in terms of semitone transpositions, or a multiple of normal playback speed. Playback speed and pitch are not decoupled so transposing to a higher pitch will result in a fast playback; this will be displayed when editing in the preview window.

**Duration/Length** - This dial has various purposes depending on the sequencer mode selected.

- Rigid Mode - In Rigid mode, the length of the step is already determined, thus the duration knob allows for cutting off the sample early as a percentage of it's full duration.

- Loose Mode - In Loose Mode, this knob allows you to selected a unique duration for each step in terms of note/bar lengths. i.e. 1/4 notes, 1/8 notes, 2 bars, etc.

- Free Mode - In Free Mode, the name of this knob changes to 'Length'. Since Live's clock is ignored in this mode, this knob determines how long the selected step should play for as a percentage of the total sample.

**Gain** - This dial allows you to adjust the gain for the selected step.

All of these parameters, except for the step indicator, can be automated and mapped.

-

###Sequencer and Playback Modes
There are three unique modes for controlling how each step's duration will be determined...

- Rigid Mode - This mode gets its clock from Live, and each step will have the same duration. The duration can be controlled by the 'Division' dial on the far left of the device. This is the only mode which the 'Division' and 'Swing' dial have any affect.

- Loose Mode - This mode also gets its clock from Live, however, each step can have a unique duration which can be set by the duration knob on each step (See Duration/Length dial above)

- Free Mode - This mode ignores Live's clock and each steps duration is controlled by the 'Length' dial on each step. Each step will continue to play until it has reached the end of the selection. 

There are also two modes for selecting playback speed...

- Untuned - In untuned playback mode, the 'Playback' dial on each step can be a value from 0 to 3, where 1.0 is normal playback, 2.0 is twice as fast (and an octave above normal playback pitch) and 0.5 is half as fast (and an octave below normal playback pitch).

- Tuned - In tuned playback mode, the 'Playback' dial is in terms of semitones, allowing for proper tuning of each step. Since playback speed and pitch are not decoupled, raising or lowing the semitone playback will also change the playback speed of the selected step. This will be reflected in the step preview window.

-
###ADSR
The ADSR for this device applies when each step begins playback. Its imporant to note that since the duration of each step is determined by other dials on the device, adjusting the attack and release does not extend the duration. If the release is raised, then it will be applied based on whatever the selected duration is. 

**Note** - if the duration of the release is longer than duration of any step, then that step will not play. This becomes especially apparent when working with particulary short step durations (32nd notes).

-
###Patterns
This device is capable of storing eight unique patterns, all of which are saved with the live set. The clear button will set the selected step to default values. 

Pattern selected can also be mapped and automated. Since this device does not do anything with MIDI, it may be helpful to automate pattern changes in the track's clips.

-
###Clock Controls
**Division** - This dial controls the duration of each step in 'Rigid Mode'. The value of this dial represents how many divisions will be in a single bar. Selecting '1' will give each step an entire bar's duration, '2' will be half a bar, '8' would be eight notes, etc. Values like 7, 11, or even 31 will create very unorthodox patterns. If you wish to have longer durations (2 or 4 bars) then you can choose loose mode, which allows each step to be as long as 4 bars.

**Swing %** - This dial controls the amount of swing applied to the sequencer in 'Rigid Mode'. You may choose up to 100%, but this will just eliminate every other note. It should be noted that adjusting the swing value will not extend the step of the previous step and will leave a gap between the swung and unswung notes.

**# of Steps** - This dial controls how many steps the sequencer will step through until starting back at step 1. This dial applies for all sequencer modes. 

**Offset** - This dial will offset which step beat one will start on. A value of zero will start on step 1, while a value of 7 will start on step 8.

-
###Step Preview/File Drop
On the far right of the device is the step preview screen. Dropping an audio file on this area will upload that file into the device and it will display a preview of the entire file. To replace the file, just drop another file into this area. 

When editing a step, a highlighted portion will appear on this screen represented where in the file that step will playback. Changing parameters like duration and playback speed will shorten or lengthen this highlighted portion. Furthermore, when Live's transport is on, this area will update as the sequencer moves through each step and a playback head will move through highlighted portion to visualize which section of the audio file is being played back.

 
