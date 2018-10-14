Audio Extractor - 5 Continuous Inputs for Wekinator
by Ronald F. Bustamante Medina
Requires Tristan Jehan’s analyzer.

The inputs are:

1. Midi Pitch
2. Loudness
3. Speed
4. Acceleration
5. Brightness

The values are not normalised and 2,3,4,5 are (linearly) scaled.

The controls are:

“In”: sets the input volume.
“Intervals in ms”: set the length of the interval used to measure speed and acceleration.
“Loudness sensibility”: determines a threshold for the loudness, inputs 2,3,4, 5 report 0 unless the loudness is above this threshold.

How the patch works:

It takes a monophonic signal. It reports the midi pitch always. When the loudness is above the threshold, it reports the loudness and brightness, and also counts the number of notes and calculates speed and acceleration.

I tested it with a monophonic synth, an electric guitar and a theremin. 
