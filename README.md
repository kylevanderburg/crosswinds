# Crosswinds

For clarinet and live electronics.

For use with sheet music available at https://kylevanderburg.com/music/crosswinds/

Patch Version 4 is for use with Crosswinds Score Revision 4 released after February 2023. If you are using an older revision of Crosswinds, look for the appropriate patch under Releases or contact NoteForge for an updated score.

## Instructions
The cue numbers in the printed music correspond to cues within the performance software. The performance software requires one microphone (on the performer) connected to the computer running the patch, and stereo outputs (patch outputs 1-2) connected to the house left and right loudspeakers. A third channel (patch output 3) can be used as a monitor for the counterpoint section at cue 35. This monitor channel outputs non-manipulated sound from the multiplayer generators. Cues may be advanced by the sound technician or by the performer. The patch is configured to advance on keystroke
32, or the spacebar on most systems. If the performer advances cues, the use of a MIDI or USB pedal is required, which must then be configured to work with the patch's counter. The patch includes both "Panic" and "Initialize" buttons. Initialize clears all sound buffers, resets the matrix to initial parameters, and sets the counter to zero. Panic stops all playback and clears the matrix without clearing the sound buffers. 

On opening the patch, a window will open requiring the user to select Option A (Hard) or Option B (Standard) playback mode. If the wrong mode is selected on initialization, the Option window may be recalled by clicking "Option Configuration."

## Changelog

### v.4 (2023)
- Fixed playback issue at Cue 35
- Created performer options at m. 110 (normal/hard mode)
- Added multiplayer normal/hard selection switch at beginning.

### v.3 (2020)
- Compiled max patch into collective and made available on GitHub
- Rewrote MIDI multiplayer and replaced with audio file playback.


