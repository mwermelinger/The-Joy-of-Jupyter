# Audio

This folder of [_The Joy of Jupyter_](http://tiny.cc/JoJ) has examples of
notebooks that generate, manipulate and play sound.

Sound can be represented very simply as a list of numbers that represent
the sound volume at each point in time. 
One list is mono sound, two lists is stereo.
Manipulating the numbers in the lists can lead to various sound effects.

As such, Python and Jupyter notebooks could be used to support Physics, Music,
Music Technology and Maths classes.

The notebooks in this folder are as follows:

1. _Sine waves_ (**to be done**) shows that pure sounds are sine waves that can be easily generated and played, using basic Python and the built-in notebook audio player.
2. _Guitar_ implements the Karplus-Strong algorithm that synthesises guitar-like sounds, and uses it to generate and play an arpeggiated C major chord. This notebook also only uses basic Python.
3. _Processing WAV files_ shows how to use the SciPy and NumPy libraries to easily read, change, and write WAV files. 