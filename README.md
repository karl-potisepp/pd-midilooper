# pd-midilooper
A MIDI looper written in Pure Data. Requires nothing but Vanilla PD (developed using Pd-0.47-1-64bit on a Mac).

The motivation is to provide a Pure Data looper capable of real-time recording MIDI events (notes, cc, pitch bend) and then looping the recording. Currently, the feature set is very simple: only recording, playing, stopping and clearing the loop are supported. In theory it's also possible to improve the looper to support step-based recording, quantization and changing the tempo of a loop while it is playing.

Usage demonstration can be found in midilooper-help.pd

TODO:
  * update help and give example of muting, tempo change
  * BUG: pitch bend doesn't seem to work well
