# Setting up your computer for Physics 67

We will be using [Jupyter notebooks](https://jupyter.org/) with the interactive [IPython](http://ipython.org/) environment to do the labs in this course.

Each week you will be working through 1-3 notebooks during the lab time, and then spending some additional time writing up a short report on what you did.

Getting set up to run these notebooks on your computer has been described as anywhere from "pretty trivial" to "rather painful", so hopefully everything works well for you, but please don't worry if you have problems getting set up.  We have a lot of options and will make sure that everyone can work effectively.


## Running these notebooks on your computer

Quick option:  [Run on the cloud](#Backup plan)

To run these notebooks you are going to install some software on your computer.  Depending on the type of computer you have, and how tech-savvy you are, the details are going to differ a bit, but there are many very good online installation guides.

Again, don't worry if you get stuck or have problems installing the software.  We will have some time during the first week to help you get set up.  You won't really need the software until the second week, and you can actually run the notebooks on the cloud (though we strongly recommend you run them on your own computer).

You will need:

1. A python installation and python package manager, typically this will be either:
   1. miniconda (recommenced)
	  1. You wil have to use the terminal window to install miniconda, it isn't complicated, but that might be new to some of you.
	  2. You will have to install a few extra data analysis packages by hand, again, it isn't complicated.
   2. anaconda
	  1. You won't need the terminal window, and the installation will install all the packages you need (and a whole lot more)	
2. The notebooks and data for this course, there are three ways you can access these:
   1. Using the git tool
   2. Using the github-desktop tool
   3. Downloading them from the repository directly



## Installing python and a python package manager on your computer

Python is the standard programming language for doing data analysis in most of physics and astronomy.  It is very easy to get started with, so if you are completely new to Python, don't worry.  We won't be doing anything terribly fancy with python and we will take care to explain the things that we do.

One of the advantages of python is that there is a huge python-based software ecosystem that includes some great data analysis tools.  In particular we will
be using a few of these python packages in this class.

- numpy: (i.e., "numerical python") a package for doing mathematical computations and manipulations
- scipy: (i.e., "scientific python") a scientific tool-kit for python
- matplotlib: a graphics and plotting package

Depending on how you install python, you might have to install these packages separately.  Fortunately, there are some great tools to manage python packages.  We will be using the "conda" tool.


### Option 1:  Installing 'miniconda'

The fastest way to get up and running is with [Miniconda](https://conda.io/en/latest/miniconda.html).
This will require that you do a number of things in the terminal window, but the instructions should be clear enough that you can set things up even if you haven't used a terminal window before.

Once you have installed and setup up miniconda, you can run this command in the terminal window to install the extra packages that you will need

	`conda install python=3.8 numpy scipy matplotlib` 


### Option 2: Installing 'anaconda'

The "Anaconda" data analysis environment is much more complete that miniconda, and includes some other things that you might find useful, but you certainly don't need it for this course.

It does have the nice feature of complete environment, so you won't have to use the terminal to install anything.

You can download anaconda for free here:

https://www.anaconda.com/products/individual
https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html

This installation will include numpy, matplotlib, scipy and jupyter so you shouldn't have to do anything else.


### Installing and updating this Repository on your computer

### Option 1: using git (easy to do if you are comfortable using the terminal)

`git` is a software versioning tool.  It will allow you to fetch the latest version of the repository to your computer.
You can find instructions on how to install git here:

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Once you have installed git, from a terminal window you can do:

`git clone https://github.com/KIPAC/Physics67`

To install the repository on your computer.

Then at any point you can update the repository on your computer to the latest version by doing two commands

`git stash`

This will move all of the changes that you have made to a backup area so they don't get overwritten when you get new files
for the repository.

`git pull`

This will fetch all the new changes form the repository and merge them into your version.


### Option 2: using github desktop app (a bit longer to setup, but easy to update each week)

The github desktop app is both a nice tool to interface with git, and a way to use git without needing to use a terminal.  Here is what you will need to do to use the github desktop app.

1. Install the github desktop app from here: https://desktop.github.com/
2. Once you have installed it, click on the "Current Repository" box in the upper left corner.  This gives you a text box and a pull-down menu. 
3. Type in 'KIPAC/Physics67' into the test box and select "Clone Repository..." from the pull down menu
4. This will "clone" the repository onto your computer, for example putting it in "Documents/GitHub/Physics67"
5. At any point you can then update your local copy from the "origin" repository by clicking on "Fetch Origin" button.
6. This will show all the changes that you have made to your local version.  Git allows you do to many things, such as saving your local version and keeping track of the differences, but the simplest thing to do is either rename the files that you have changed or just to right-click on the little box next to the each file and select "Discard Changes"


### Option 3: by downloading it (easy, but you will have to manually update each week)

If you don't want to use git, you can always just download a snapshot of the repository each week before class.

Go to https://github.com/KIPAC/Physics67 and click on the green "Code" button in and select "Download ZIP" from the drop-down menu.

Note that this will download the current version of the repository, so you will want to do this each week before class.  You probably want to save the older version first so that you can refer to previous work.


## Opening Notebooks

If you installed jupyter using miniconda you can start jupyter from a terminal by typing:

`jupyter-notebook`

If you installed anaconda, then you can start jupyter from the anaconda App graphical interface.  (Applications -> Anaconda Navigator, then click on the "Launch" button in the "Jupyter Notebook" box.

One you have started jupyter, it will pop up a browser window showing the contents of what jupyter treats as your home folder.  (Either the folder you ran the `jupyter-notebook` command from, or a folder that you can set in the anaconda preferences).  From there you should navigate to the folder that you have installed the course in and click on the notebook you want to run.


## Backup plan

Running these notebooks using jupyter on the web. 

If for some reason you have issues installing the software on your computer, you can also use the service "binder" to run the notebooks on a remote server on the web.  This works, but has the disadvantage that it can be difficult to save the work you do in the notebook, so you will probably end up copying things to
a file.

1. Go to https://mybinder.org/
2. Type "KIPAC/Physics67" into the "GitHub repository name or URL" text box and then click on the orange "Launch" button, it will take a few minutes to set up a machine somewhere off in the cloud and connect you to it. 

It is fine to run binder the first week, but we would like to get everyone set up with the software on their computers by the second week.  This will make it easier for you to save you work and include it in the lab reports.


<!--  LocalWords:  Jupyter IPython miniconda github-desktop numpy
 -->
<!--  LocalWords:  scipy matplotlib github
 -->
