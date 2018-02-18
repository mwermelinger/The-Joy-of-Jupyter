# The Joy of Jupyter

This repository is an introduction to Jupyter notebooks, a widely used interactive computing environment that is easy enough for school children and powerful enough for professional scientists.

I will be assuming you are reading this text on the [home page of the repository](http://github.com/mwermelinger/The-Joy-of-Jupyter). 
Otherwise certain sentences won't make sense.

## These notebooks

The notebooks in this repository are as follows.

**`audio.ipynb`** shows how to play, manipulate and generate music 
in a notebook.
It uses the IPython audio player, 
the SciPy and NumPy libraries to read, transform and write sound files, 
and the matplotlib library to show the waveforms. 
This notebook requires the `Fast_Talkin.wav` file. 
It will generate two further sound files; 
you can delete them after using the notebook.

**`turtle.ipynb`** shows how to draw turtle graphics from a notebook. 
It only uses Python's built-in turtle library. 
The graphics themselves appear in a separate window, 
as notebooks can only include HTML. 
This notebook includes a simple example of fractal tree drawing.

**`tuberculosis.ipynb`** is a very simple example of reproducible research. 
It shows how to load data from an Excel spreadsheet, 
analyse and visualise the data, and write up the conclusions. 
This notebook uses the pandas library and requires the `WHO_POP_TB.xls` file, 
which contains World Health Organisation data about 
the world's population and deaths due to tuberculosis. 

If you click on any notebook name at the top of the home page,
you will see a static rendering of that notebook. 
You can't execute the code and you can't change the notebook. To do that, 
you must download the notebooks and open them in the right environment. 
To download them to your laptop or desktop (I haven't tried on a tablet):

1. Click on the green 'Clone or download' button in the upper right part of this page.
- You will see a pop-up window with a button 'Download ZIP'. Click on it. The notebooks and data files will be downloaded as a compressed archive: a file with extension `.zip`. The archive will be in the folder where your web browser usually puts downloaded files. 
- You will need to double-click on the downloaded file to uncompress it, if your browser hasn't already done that automatically for you. You should now have a sub-folder named `The-Joy-of-Jupyter-master` or similar. 

Next you need to choose which environment to use for working with notebooks.
You have several choices.

## Try Jupyter!

The simplest way of seeing Jupyter notebooks in action, without installing any software or creating a user account (I know it sounds too good to be true), is to use the [Try Jupyper!](http://try.jupyter.org) website. 

<!--After a little while, it will create a Jupyter environment just for you, and list some demo folders and files that you are free to explore later on. and after a little while you should see the Jupyter dashboard. a list of files. 
- Click on the 'Upload' button in the upper right corner of that site. 
- You will see a file browser dialog. Go to the dowloads folder, then to the downloaded sub-folder, and select one of the _Joy of Jupyter_ notebooks and any necessary data file. Click on the 'OK' or 'Choose' button of the file dialog. Note that you shouldn't select the turtle graphics notebook: unfortunately it doesn't work in _Try Jupyter!_.
- The notebook and data file you selected will now appear at the start of the list of files, with blue 'Upload' buttons. Click on those buttons to confirm the uploading. After they have been uploaded, the files will be put in alphabetical order among the list. Note that the audio notebook and sound file are relatively large and may take a little while to upload.


5. Click on in You can rename the folder to whatever name you prefer. If you will be working on the course using your desktop, e.g. with Anaconda, you need to move that folder to anywhere within your home folder, so that Jupyter can find your notebooks and open them. If you will be working on the course using a web-based service, e.g. CoCalc, you need to upload the folder to that service.-->