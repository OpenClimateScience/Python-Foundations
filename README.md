Python Foundations
==================

These introductory Python lessons provide the training necessary for learners interested in the NASA *ScienceCore* curriculum, ["Open Climate Science for Agriculture"](https://openclimatescience.github.io/) Each lesson below is intended to require 2 hours (when taught in a workshop format).

1. [**Introduction to Python**](https://github.com/OpenClimateScience/Python-Foundations/blob/master/01_Introduction.ipynb) - Start here if you have never used Python or any other programming language before
2. [**Building Python Proficiency**](https://github.com/OpenClimateScience/Python-Foundations/blob/master/02_Building_Python_Proficiency.ipynb) - Start here if you have some Python experience or ample experience in other languages
3. [**Introduction to NumPy**](https://github.com/OpenClimateScience/Python-Foundations/blob/master/03_Introduction_to_NumPy.ipynb)
4. [**Raster Data Analysis in Python**](https://github.com/OpenClimateScience/Python-Foundations/blob/master/04_Raster_Data_in_Python.ipynb)


Required Software
-----------------

**If you're running Windows, the recommended way to get started is to use OSGeo4W, which provides Python, the `pip` package manager, and required geospatial libraries.**

From the Windows PowerShell or command line, type the following command and hit ENTER: `whoami`

- This is your Windows username, don't forget it!

1. Now, go to [https://trac.osgeo.org/osgeo4w/](https://trac.osgeo.org/osgeo4w/) and "Download the OSGeo4W network installer."
1. Run the installer, choosing "Express" install and choose to also install GDAL.
1. Next, you need to install the Python libraries we will be using. Start the OSGeo4W Shell by typing "OSGeo4W Shell" in the Start or search menu. A command-line interface should appear; [see the screenshot on this page](https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md) for an example.
1. Type the following and hit ENTER: `pip install numpy scipy notebook`
1. Now, let's change to our Home directory. Type the following and hit ENTER, after replacing `username` with your Windows username: `cd C:/Users/username`
1. You're now ready to start Jupyter Notebook, which is the environment we recommend you use to write Python code. Type the following and hit ENTER: `python -m notebook`
1. Jupyter Notebook should have opened in your web browser. You should see something that looks like a file tree (files and folders) for your Home directory. You're all set! [You can read this article](https://jupyter-notebook.readthedocs.io/en/latest/notebook.html) for more information about how to use Jupyter Notebook.

[For Mac OS X, GNU Linux, or for experienced Windows users, see the installation guide here.](https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md)


Acknowledgements
----------------

This curriculum was enabled by a grant from NASA's Transition to Open Science (TOPS) Training program (80NSSC23K0864).
