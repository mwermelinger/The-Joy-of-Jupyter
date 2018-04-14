# The Joy of Jupyter

This repository is an introduction to Jupyter notebooks, a widely used 
interactive computing environment that is easy enough for 15 year old 
school children and powerful enough for professional scientists.

Although Jupyter notebooks can used with several programming languages,
all examples in this repository are in Python. 
I will therefore assume you are familiar with the basics of Python.

Jupyter notebooks have the extension `.ipynb` because they used 
to be called IPython notebooks. 
The name 'Jupyter' comes from the three programming languages 
it is most widely used with: Julia, Python and R.

Make sure you are reading this text on the [home page of the repository](http://github.com/mwermelinger/The-Joy-of-Jupyter). 
Otherwise certain sentences won't make sense.

## 1 Introduction

A Jupyter notebook is a rich, interactive, computing environment.
It can include a mix of explanatory text, live code, and the code's output.
To work with or on a notebook, a Jupyter environment is required. However, 
a notebook can also be rendered as a static web page or as a PDF document,
for those who just want to read the notebook.

In the file list above this text, click on `turbeculosis.ipynb` to
see how a notebook looks like when rendered as a static web page.
You don't need to read the notebook in detail, just skim it.
It shows that the output of code can be not just text, 
but also tables and charts, all in one single integrated document.

Now that you've seen a concrete example of a notebook, 
read [_What is the Jupyter Notebook?_](https://github.com/jupyter/notebook/blob/master/docs/source/examples/Notebook/What%20is%20the%20Jupyter%20Notebook.ipynb), 
a brief introduction by the Jupyter team to 
the main terminology and features of notebooks.

## 2 These notebooks

The notebooks in this repository are as follows.

The `audio` folder contains notebooks that generate, manipulate and play music.
Click on the folder name in the list above to see their description.

**`complexity.ipynb`** shows how to measure the run-time of
Python code and thereby empirically obtain the complexity of an algorithm.

**`tuberculosis.ipynb`** is a very simple example of reproducible research. 
It shows how to load data from an Excel spreadsheet, 
analyse and visualise the data, and write up the conclusions. 
This notebook uses the pandas library and requires the `WHO_POP_TB.xls` file, 
which contains World Health Organisation data about 
the world's population and deaths due to tuberculosis. 

**`turtle.ipynb`** shows how to draw turtle graphics from a notebook. 
It only uses Python's built-in turtle library. 
The graphics themselves appear in a separate window, 
as notebooks can only include HTML. 
This notebook includes a simple example of fractal tree drawing.

As mentioned before, if you click on any notebook name at the top of this page,
you will see a static rendering of that notebook. 
You can't execute the code and you can't change the notebook. To do that, 
you must download the notebooks and open them in the right environment. 
To download them to your laptop or desktop (I haven't tried on a tablet):

1. Click on the green 'Clone or download' button in the upper right part of this page.
1. You will see a pop-up window with a button 'Download ZIP'. Click on it. The notebooks and data files will be downloaded as a compressed archive: a file with extension `.zip`. The archive will be in the folder where your web browser usually puts downloaded files. 
1. You will need to double-click on the downloaded file to uncompress it, if your browser hasn't done that automatically for you. You should now have a sub-folder named `The-Joy-of-Jupyter-master` or similar. 

Next you need to choose which environment to use for working with notebooks.
You have several choices.

## 3 Try Jupyter!

The simplest and quickest way of seeing Jupyter notebooks in action, 
without installing any software or creating a user account 
(I know it sounds too good to be true), is to use the _Try Jupyter!_ website. 
It will create a Jupyter environment just for you, already with 
some demo folders and files that you are free to explore later on. 
Because the environment is just for you, you can add, delete and edit files 
as you please. It won't affect anyone else. 

You will lose all changes once you close the _Try Jupyter!_ webpage 
or leave it unattended for too long. 
You can however download the notebooks you changed to your machine 
and upload them again in a future session.
_Try Jupyter!_ is meant for quick exploration of Jupyter notebooks 
in short sessions. It is not meant for regular work on notebooks.
There are other, better suited environments for that.

### 3.1 Uploading the files

Now that you're aware of the advantages and disadvantages of this environment,
go to the [Try Jupyter!](http://try.jupyter.org) website. 
After a little while you will see the Notebook Dashboard, 
which is similar to the file browser on your machine. 

Click on the 'Upload' button in the upper right corner of that site. 
You will get the usual file picker dialog on your machine. 
Go to the downloads folder, then to the downloaded sub-folder. 
Select one of the _Joy of Jupyter_ notebooks and any required auxiliary file. 
Don't select the turtle graphics notebook: it won't work in _Try Jupyter!_.
Click on the 'OK' or 'Choose' button of the file dialog. 

The notebook and auxiliary file you selected will now appear 
at the start of the list of files, with blue 'Upload' buttons. 
Click on those buttons to confirm the uploading. 
(The audio notebook and sound file are relatively large 
and may take a little while to upload.)

After the upload, the files will be in alphabetical order among the list. 
I suggest you click once or twice on the 'Last Modified' button 
so that the most recent files are easier to spot, at the start of the list.
You can click the 'Name' button once or twice to list the files
in ascending or descending alphabetical order.

### 3.2 Working with notebooks

With the files uploaded, you can start working on the notebook.

First read the [Notebook Basics](https://github.com/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb), 
written by the Jupyter team. 
The first part has more details about the dashboard,
the second is about working with a notebook.

Next, in the dashboard, click on the name of the notebook you uploaded,
to open it. Before you start working, 
I suggest you click on the Help menu and take the 'User Interface Tour'.

As you work on a notebook, don't forget to regularly save it, 
by clicking on the button with a floppy disk icon, below the File menu.

Once you're done, select File –> Close and Halt. 
This will stop the kernel that executes the code cells.
Afterwards, use your browser's back button to go back to the dashboard.
If you forgot to halt any notebooks, they will be listed in green.
Click the checkbox next to them. 
A new menu appears above the file list, with a 'Shutdown' button. Click it.

### 3.3 Downloading files

As mentioned earlier, if you wish to keep a copy of a notebook you changed, 
you must download it. When you're back in the dashboard, 
click the checkbox to the left of the file you wish to download.
A new 'Download' button appears above the file list. Click on it.

## 4 Other environments

If you have a couple of spare gigabytes on your hard disk,
you should install [Anaconda](https://www.anaconda.com/download). 
It's freely available for Linux, Mac and Windows.
It includes Python, Jupyter, and over hundred libraries.
There are two variants of Anaconda: with Python 2 and with Python 3.
Make sure you install the latter. Python 2 is no longer developed.
Once you have installed Anaconda, launch the Anaconda Navigator.
You will see list of installed applications, one being Jupyter Notebook.
Click the 'Launch' button below it. 

If you don't want or can't install software, there are other web-based
providers, like [CoCalc](http://cocalc.com), 
[Microsoft Azure Notebooks](https://notebooks.azure.com), 
and [Anaconda Cloud](https://anaconda.org).
All of these require to set up a user account, 
so that your notebooks can be saved between sessions.