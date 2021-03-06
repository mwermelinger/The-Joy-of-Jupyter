# Audio

This folder of [_The Joy of Jupyter_](http://tiny.cc/JoJ) has examples of
notebooks that generate, manipulate and play sound.

Sound can be represented very simply as a list of numbers that represent
the sound volume at each point in time. 
One list is mono sound, two lists is stereo.
Manipulating the numbers in the lists can lead to various sound effects.

Thus, Python and Jupyter notebooks could be used to support 
Physics, Music, and Music Technology classes, 
or to enrich Maths and Computing classes with audio examples.

You may wish to use headphones and keep the volume low with these notebooks.
They all have the generated sounds embedded, i.e. stored within the notebook,
so that you can hear them even without installing Jupyter.
However, GitHub doesn't support that feature.
If you click on the file names in the list above,
you will only be able to read the notebooks. 
If you also want to hear them, go
[here](http://nbviewer.jupyter.org/github/mwermelinger/The-Joy-of-Jupyter/tree/master/audio/).

The notebooks in this folder are as follows.

**`audio-1-sine.ipynb`** generates and plays sine waves to obtain specific notes, using basic Python and the built-in notebook audio player.

**`audio-2-guitar.ipynb`** implements the Karplus-Strong algorithm, 
which synthesises guitar-like sounds, 
and uses it to generate and play an arpeggiated C major chord. 
This notebook only uses basic Python too.

**`audio-3-wav.ipynb`** shows how to use the SciPy and NumPy libraries 
to easily read, change, and write WAV files. 
This notebook requires the `Fast_Talkin.wav` file. 
It will generate two further sound files; 
you can delete them after using the notebook.

All notebooks use the matplotlib library to show the waveforms.