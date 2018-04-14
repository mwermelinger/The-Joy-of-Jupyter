# Audio

This folder of [_The Joy of Jupyter_](http://tiny.cc/JoJ) has examples of
notebooks that generate, manipulate and play sound.

Sound can be represented very simply as a list of numbers that represent
the sound volume at each point in time. 
One list is mono sound, two lists is stereo.
Manipulating the numbers in the lists can lead to various sound effects.

Thus, Python and Jupyter notebooks could be used to support Physics, Music,
and Music Technology classes, or to use audio examples in Maths and Computing.

The notebooks in this folder are as follows.

`audio-1-sine.ipynb` (**to be done**) shows that pure sounds are sine waves
that can be easily generated and played, 
using basic Python and the built-in notebook audio player.

`audio-2-guitar.ipynb` implements the Karplus-Strong algorithm, 
which synthesises guitar-like sounds, 
and uses it to generate and play an arpeggiated C major chord. 
This notebook also only uses basic Python.

`audio-3-wav.ipynb` shows how to use the SciPy and NumPy libraries 
to easily read, change, and write WAV files. 
This notebook requires the `Fast_Talkin.wav` file. 
It will generate two further sound files; 
you can delete them after using the notebook.

All notebooks use the matplotlib library to show the waveforms.