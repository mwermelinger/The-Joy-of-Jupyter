# Images

This folder of [_The Joy of Jupyter_](http://tiny.cc/JoJ) has examples of
notebooks that generate, manipulate and display images.

Raster images (like photos) can be represented very simply as a matrix of 
numbers that represent the colour of each pixel in the image. 
There are many file formats for raster images, e.g. JPEG, PNG, GIF, BMP, TIFF.
Manipulating the matrix and its numbers leads to various image effects.

Thus, Python and Jupyter notebooks can be used to support Art and Design classes, 
or to enrich Computing classes with imaging examples.

The notebooks in this folder are: 

**`images-1-raster.ipynb`** reads, manipulates, saves and shows PNG and JPG images, 
using the Python Image Library (PIL) and the notebook's image displayer.
This notebook requires two files included in the folder. 
It generates intermediate files with name `result...`. You can delete those.

**`exercises-greyscale.ipynb`** is an exercise workbook to practice manipulating
nested lists. It requires the `moon.tiff` image.
It generates `__temporary__.png` which you can delete afterwards.

The notebooks have all images embedded, i.e. stored within the notebook,
so that you can see them in a static rendering of the notebook, 
without running the code. 