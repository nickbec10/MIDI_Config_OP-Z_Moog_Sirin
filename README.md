# MIDI_Config_OP-Z_Moog_Sirin
This is a custom MIDI mapping configuration made for the OP-Z to control the Moog Sirin's sound parameters. 

The purpose of this OP-Z MIDI configuration is to create a set of controls, that when given random values, provide some interesting changes in timbre to the voices on the Moog Sirin. This is meant to aid in quick randomized sound design type changes on the synth. It can be used as a controller with automation, but the idea was to give you control over as many sound oriented parameters on the Moog Sirin so you can go deep in changing wave forms, timbre, tunings, lfo’s and amp envelopes. 

When using the OP-Z for generating random values, we are limited to 16 MIDI CC parameters per track. I have copied the MIDI CC controls that I think might be best suited for new voice / patch creation on the Moog Sirin. 

### Installation
Replace the midi.json file on your OP-Z with the one included in this repository. 

As always, I recommend making a backup of your existing midi.json file so you can revert back to whatever settings you had previously if you want to. 

### Usage
Track 8 on the OP-Z has custom MIDI CC mappings that are described and laid out for you on the included web page here. Tracks have been organized according to the types of parameters that they can effect on the Moog Sirin hardware synth. 

Once you load up the OP-Z, connect it to a MIDI interface that is also connected via MIDI to your Moog Sirin. I had the Moog Sirin set to receive MIDI on Channel 1, send on channel 16, program change send off and program change receive to on. 

Choose a patch, play some keys on the OP-Z and then use the randomize feature on the OP-Z to quickly hear immediate changes and try out different randomized settings to the timbre until you have something you like. To perform program changes copy a pattern to another pattern slot and use the pattern chaining feature.

Note that module track 14 can be used to control external MIDI but as of version 1.2.20 the OP-Z does not provide all the features of a drum or synth track. To be able to use step components or punch in effects you will need to "sacrifice" a track from 1 - 8. To play the other OP-Z tracks along in the mix with your other MIDI controlled device(s) and not hear the OP-Z audio from the MIDI track, turn the level of the track to 0. I suggest using one of tracks 6, 7 or 8 on the OP-Z to sequence so that you have the full range of octaves and flexibility to play with polyphony. 

Feel free to go through each page of parameters on the OP-Z and fine tune settings as you prefer. Once you have something you are happy with, go ahead and save this as a patch on the Moog Sirin so you can use it later. 

This is my first release, so I expect to make further revisions if I see a MIDI mapping layout that works better for sound design purposes. 

