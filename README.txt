STORM
Drone synthesizer and video synth for the original PlayStation (PAL)
HB-STORM-01

STORM turns a PlayStation into a drone instrument. It plays one long,
living tone that never stops, and you shape it with two controllers like
you would turn the knobs on a small modular rack. Press Start + Select and
the screen becomes a storm at sea, seen from the bow of a fishing boat,
where every sound parameter moves something in the picture.

It was made for live shows: one PS1, two pads, audio out to the mixer and
composite video out to a projector.


FILES
-----
storm.bin / storm.cue   disc image (burn it from the .cue)
cover.png               front cover


HOW TO RUN IT
-------------
- Real hardware: burn storm.cue to a CD-R at low speed and play it on a
  PAL PlayStation that can boot burned discs (modchip or similar).
- Emulator: open storm.cue in DuckStation or any PS1 emulator, PAL region.
- Two controllers. A DualShock with the analog LED on adds the sticks,
  but every function also works with digital pads.
- Memory card in slot 1 to save your scenes (optional, 1 block).


THE SOUND
---------
SOURCES  One oscillator with four waves at the same time: sine, square,
         saw and a sub one octave down. A second oscillator (OSC B)
         modulates it at audio rate: FM, AM and pulse width.
GRAIN    Wavefolder, noise, square width and a feedback loop tuned to the
         note.
SHAPE    Drive and a resonant filter: low pass, band pass or high pass.
LAYERS   Four more voices on the PS1 sound chip, one octave up and slightly
         out of tune, with metallic bells and chords.
TEXTURE  A low thump on the rhythm, wind, a pedal that keeps the sub and/or
         the layers on the root note, fine tuning.
SPACE    Stereo width (past 50 it goes wider than the speakers) and the
         PS1 reverb. With TAIL at 99 the reverb tail freezes (HOLD) and you
         can play on top of it.

The drone moves by itself:
MOTION   Three modulators (MOD A, B, C) with sine, triangle, breath,
         random, noise and two pulse shapes. They run at speeds that never
         line up, so the patch never repeats. Each one can move a knob,
         the pitch, the pan, a macro, or the depth or rate of another MOD.
MACROS   Four macros (RISE, DEEP, UNREST, HAZE). Each one turns four knobs
         at once, every knob up or down by its own amount.
SEQ      The note walks on a scale (minor, dorian, pentatonic, fifths,
         octaves, phrygian, lydian, mixolydian, major), one step every
         1-16 beats. MUTATE sets how often a step changes.
PULSE    Two euclidean rhythms. A MOD set to PULSE1 or PULSE2 hits on them.
CLOCK    40-200 BPM, tap tempo, nudge.


CONTROLS
--------
Rule of thumb: hold a button = open a page, then the d-pad and the
shoulder buttons are the four knobs of that page.
Up, Right, R1, R2 turn up. Down, Left, L1, L2 turn down. Hold a direction
and the value keeps moving. Tap a page button twice quickly to keep the
page open, tap it again to close it.

Controller 1: sources and shape

  Hold          Up/Down    Right/Left  R1/L1        R2/L2
  (nothing)     CUTOFF     RES         MODE LP/BP/HP DRIVE
  X             SINE       SQUARE      SAW          SUB
  Square        FOLD       NOISE       WIDTH        FEEDBACK
  Triangle      ROOT       OCTAVE      GLIDE        -
  Circle        DETUNE     BELLS       CHORD        COLOR
  Select        FM         AM          RATIO        PWM
  Select + X    THUMP      WIND        PEDAL        FINE

PLAY mode (tap Select on controller 1): the d-pad becomes playable.
  Hold Up       SWELL, pushes macro 1 while held, then falls back
  Hold Down     SINK, pushes macro 2 while held, then falls back
  Left/Right    previous / next note on the scale
  L1/R1         octave down / up
  L2/R2         chord of the layers

Controller 2: motion, space, time

  Hold            Up/Down   Right/Left  R1/L1         R2/L2
  (nothing)       M1 RISE   REVERB      LAYERS        VOLUME
  X/Square/Tri    RATE      DEPTH       WAVE          DEST     (MOD A/B/C)
  Circle          WIDE      TAIL        ROOM          DAMP
  Select          M1 RISE   M2 DEEP     M3 UNREST     M4 HAZE
  Select + X      STEPS     MUTATE      SCALE         EVERY    (SEQ)
  Select + Square HITS 1    STEPS 1     HITS 2        STEPS 2  (PULSE)
  Select + Tri    BPM       RANGE       NUDGE         TAP      (CLOCK)
  Select + Circle SLOT 1-16 AMOUNT      DESTINATION   -        (macro EDIT)
  Start (held)    SCENE     MORPH       R1 GO, L1 HOME R2 NUDGE, L2 AUTO

Special buttons
  Controller 1 Start (tap)      MUTE, fades out in 3 s, tap again to fade in
  Controller 1 Select (tap)     PLAY mode on / off
  Controller 2 Start (tap)      FREEZE: modulators, sequencer and clock stop
  Start + Select (tap)          STORM visual on / off
  Start + Select (hold 1 s)     GUIDE menu (Up/Down choose, X ok, Triangle close)
  Controller 1 Start + X (2 s)  LOCK: everything ignored except MUTE
  Start + R1 / L1               next / previous step of the tutorial

Analog sticks (DualShock, LED on)
  Controller 1: left stick CUTOFF and FOLD, right stick FM and WIDTH
  Controller 2: left stick M1 and M2, right stick M3 and M4


SCENES
------
Save a sound from the GUIDE (SAVE PATCH): Left/Right picks one of 8 slots,
X saves. Saving pauses the console for about two seconds, so the sound
fades out and comes back in 3 s. Better to save between pieces.

On stage hold Start on controller 2 to open SCENE:
  Up/Down     choose the scene
  Left/Right  MORPH time: 2, 5, 10, 20, 40, 80 or 120 seconds
  R1          GO: glide into the scene over the morph time
  L1          HOME: back to the last scene you loaded, macros at zero
  R2          NUDGE: moves six sound knobs a little, slowly
  L2          AUTO: plays the saved scenes one after another by itself

If you turn a knob during a morph, that knob stays where you put it and
the rest keeps gliding. Without a memory card the scenes stay in memory
until you switch off.


THE STORM
---------
Tap Start + Select. You stand on the bow of a fishing boat in open sea.
The sea, sky and weather follow the synth:
noise = rain, cutoff = light, FM = lightning, fold = foam, sub and sine =
swell, macros = the hurricane, modulators = wind, pulse hits and sequencer
steps = lightning strikes, filter mode = time of day. SWELL lifts the boat
on a huge wave, SINK drops it into the trough.

While you hold a page, a faint line at the bottom shows its values, and
small letters in the top right corner show P F M L A (play, freeze, mute,
lock, auto). The audience sees the storm, you still know what you are
touching.


GUIDE AND TUTORIAL
------------------
Hold Start + Select for one second. The GUIDE has a page for every block
of the instrument with a live picture of it, the special keys, save and
load, and a reset. TUTORIAL builds a drone from a plain sine wave, one
step at a time, and waits for you to do each step.


ON SCREEN
---------
Top line: the note, the filter mode and boxes for PLAY, FREEZE, MUTE,
LOCK and AUTO. NOW shows the values that are really playing (with
modulation and macros), OUT is the output level, the square blinks on the
beat. Under every knob a thin blue bar shows its moving value.


TECH NOTES
----------
- PAL, 320x256, 50 Hz.
- The main voice is computed by the CPU at 22050 Hz and streamed to the
  sound chip; layers, bells, thump, wind and reverb run on the SPU.
- Written in C with PSn00bSDK.
- The memory card file is called STORM DRONE PATCHES.


THANKS
------
The voice and the idea of a drone that keeps moving were inspired by the
modular drone racks of Rijnder Kamerbeek (Monotrail).
