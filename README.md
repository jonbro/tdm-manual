# tdm guide

## Power

### On

![power](https://user-images.githubusercontent.com/1597/169668001-5d3b0e36-71a3-4dd1-bae7-5c0edf356702.png)

Press and hold the power / sound select button to power on.

### Off

Press and hold the esc button & the sound select button for 5 seconds to power off

## Playing Sounds

![power](https://user-images.githubusercontent.com/1597/169668001-5d3b0e36-71a3-4dd1-bae7-5c0edf356702.png)

Select a sound by holding power / sound select button, then pressing a button from 1-15. Key 16 is reserved for global settings.

Once selected, press a button from 1-16 to play a sound. If no sound plays, confirm you are not in write mode.

## Playing Patterns

![pattern](https://user-images.githubusercontent.com/1597/169668019-7df65cb7-40dc-4ac1-8541-8dec7e7adfff.png)

Select a pattern by holding the pattern button, then pressing a button from 1-16.

![play](https://user-images.githubusercontent.com/1597/169668011-9c127b89-8b1f-47b5-baec-abeadbfedf33.png)

Press play to start or stop the pattern.

### Chaining Patterns

While holding the pattern button, press a series of 1-16 buttons. This will store a sequence of patterns.

### Copy Pattern

Hold Record, then hold pattern, then press a button 1-16 to copy the current pattern to a new pattern.

### Erase Pattern

Hold Esc, then hold pattern. The pattern will be erased after a countdown.

### Edit Page

To change the page you are currently editing for the pattern, press the unlabeled button above play.

## Recording Patterns

![write](https://user-images.githubusercontent.com/1597/169668262-6371d1e9-344a-4a2b-99ea-440e1cf02921.png)

There are two ways to record notes into a pattern, step mode & live mode.

### Step Mode

while write is not lit, choose a note by pressing a button 1-16. Then press write to enter write mode. Pressing buttons 1-16 will enter the last selected note on those steps.

### Live Mode

while write is not lit, and the pattern is not playing, hold write, then press play. Once in live mode, notes played using the buttons 1-16 will be stored in the current pattern.

### Parameter Lock

While in step mode, hold down a lit step and move a knob to store a parameter lock for that step. There are 128*16 parameter locks available.

## Editing Sounds

![param](https://user-images.githubusercontent.com/1597/169668189-a29952e5-dec4-4509-9335-b1395ced9cce.png)

While holding the parameter button, press a button 1-16. Once selected, the A & B knobs will modify the current sound.

### All Voice Parameters

- **2** Filter Cutoff / Resonane
- **3** Volume / Pan
- **4** Octave
- **5** Volume Envelope Attack / Decay
- **15** Pattern Length
- **15** Delay Send
- **16** Instrument Type / Subtype

### Synth Parameters
- **1** Timbre / Color

### Sampler Parameters
- **1** Sample In / Out points

### Midi Parameters 

None, it just dumps all notes out to channel 1. "Enjoy".

### Global Channel (voice 16)
- **1** Bpm
- **2** Enable Speaker
- **15** Line In to delay send

## Sampling

Press and hold the arm button to sample. It will append to the currently selected voice.

## Power Off / Somethings Gone Wrong

On the back of the unit, there are two buttons - While looking at the back of the unit they are (uboot / run) - to power off, press the right button. If you are connected to usb, it will immediately power back on, this is expected.

If something has gone wrong, or you want to update your firmware, while holding the uboot button, press the run button while plugged into USB. This will present the unit as a usb drive, where you can drag the new firmware on.
