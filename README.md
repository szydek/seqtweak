# seqtweak

**IMPORTANT NOTE:**
This project would not be possible without the wonderful work on
[Pitch Stepper by Dennis DeSantis](https://dennisdesantis.com/max-for-live-devices/pitch-stepper)

Yet Another Max4Live MIDI Sequencer - Use existing notes from any MIDI clip in Ableton Live to create and tweak new sequences. Once notes are loaded, the gates from any playing clip will be used to control the ryhthmic dimensions of how the captured pitches are played back (Forward, Reverse, Repeated Random Order, and Random.

**How to Use:**

1. Add 2 new MIDI tracks in Ableton Live (tested w/Live 10) - NOTE: a second MIDI track is only necessary if you'd like to send feedback control messages to a Novation LaunchControl XL controller. 
2. Add the SeqTweak to track 1 along with any instrument you'd like to control
3. Create a MIDI clip in track 1 and while playing (or after selecting desired notes in the clip), click "Capture" to capture pitches from selected clip MIDI notes.
4. Once the MIDI notes are captured, play either the existing clip or create new clips with different rhythm patterns to control how the captured notes are played
5. OPTIONAL: If you have a Novation LaunchControl XL controller (LC), you can send LC messages to a second MIDI track set to send to a desired user channel for the connected LaunchControl XL using the Max MIDI Reciever device on that channel.

**WIP:** 
Finish up work on reverse order playback mode, additional MIDI mapping options, better documentation / explanations / demos of how it works.

**BUGS:**
Note-Offs may not be working as expected.
