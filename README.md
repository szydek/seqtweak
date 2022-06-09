# seqtweak

IMPORTANT NOTE:
This project would not be possible without the wonderful work on
Pitch Stepper version 2 by Dennis DeSantis


Yet Another Max4Live MIDI Sequencer - Use existing notes from any MIDI clip in Ableton Live to create and tweak new sequences. Once notes are loaded, the gates from any playng clip will be used to control the ryhthmic dimensions of how the notes are played.

How to Use:

1. Add 2 new MIDI tracks in Ableton Live (tested w/Live 10) - NOTE: a second MIDI track is only necessary if you'd like to send feedback control messages to a Novation LaunchControl XL controller. 
2. Add the SeqTweak to track 1 along with any instrument you'd like to control
3. Create a MIDI clip in track 1 and while playing (or after selecting desired notes in the clip), click "Get pitches from selected MIDI clip notes)
4. Once the MIDI notes are captured, play either the existing clip or create new clips with different rhythm patterns to control how the captured notes are played
5. OPTIONAL: If you have a Novation LaunchControl XL controler, you can use the Max MIDI Sender / Reciever directly after SeqTweak to the second MIDI track set to send to a desired user channel for the LaunchControl XL.

WIP / TODO - Need to finish up work on reverse order playback mode, additional MIDI mapping options, better documentation
