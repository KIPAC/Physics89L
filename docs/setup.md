# Setting up your computer for Physics 89L

We will be using [Jupyter notebooks](https://jupyter.org/) running Python kernels to do the labs in this course. [This](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) is a brief explanation of what a jupyter notebook is. Please follow the instructions on this page to set up the software needed to run these jupyter notebooks.

Each week you will be working through 1-3 notebooks during the lab time, and then spending some additional time writing up a short report on what you did.

Getting set up to run these notebooks on your computer can be challenging, so hopefully everything works well for you, but please don't worry if you have problems getting set up.  We have a lot of options and will make sure that everyone can work effectively.


## Overview


To run these notebooks you are going to install some software on your computer.  Depending on the type of computer you have, the details are going to differ a bit, but there are many very good online installation guides.

Please follow these steps:

1. Install a python and python package manager, using *one* of two options:
   1. [Install `anaconda`](#option-1-installing-anaconda-easiest) (recommended for ease of installation)
	  1. You won't need the terminal window, and the installation will install all the packages you need (and a whole lot more)
   2. [Install `miniconda`](#option-2-installing-miniconda)
	  1. You wil have to use the terminal window to install miniconda which might be new to some of you.
	  2. You will have to install a few extra data analysis packages by hand.
	  
2. Download the notebooks and data for this course. There are three ways you can access these:
   1. [Using the github-desktop app](#option-1-using-the-github-desktop-application-easiest) (recommended for ease of installation)
        1. This will take longer to set up but will be easier to update each week.
   2. [Using the git tool](#option-2-using-git)
        1. You will have to use the terminal window.
   3. [Downloading them from the repository directly](#option-3-direct-download)

3. [Open the jupyter notebook browser](#open-the-jupyter-notebook-browser)
4. [Test your setup](#test-your-setup)

Backup option:  [Run on the cloud](#backup-plan)


## Installing python and a python package manager on your computer

Python is a commonly used programming language for doing data analysis in most of physics and astronomy.  It is very easy to get started with, so if you are completely new to Python, don't worry.  We won't be doing anything terribly fancy with python and we will take care to explain the things that we do.

One of the advantages of python is that there is a huge python-based software ecosystem that includes some great data analysis tools.  In particular we will
be using a few of these python packages in this class.

- numpy: (i.e., "numerical python") a package for doing mathematical computations and manipulations
- scipy: (i.e., "scientific python") a scientific tool-kit for python
- matplotlib: a graphics and plotting package

Depending on how you install python, you might have to install these packages separately.  Fortunately, there are some great tools to manage python packages.  We will be using the "conda" tool.


### Option 1: Installing 'anaconda' (easiest)

The `Anaconda` data analysis environment is much more complete than miniconda, and includes some other things that you might find useful (although you don't need the added features for this course). We would recommend installing Anaconda if you think you might use python and python packages outside of this course and if you have a lot of disk space.

It does have the nice feature of complete application and environment, so you won't have to use the terminal to install anything.

You can download anaconda for free [HERE](https://www.anaconda.com/download).
- Click "Skip registration" instead of providing your email
- Install Python 3.11 to ensure code compatibility

This installation will include numpy, matplotlib, scipy and jupyter so you shouldn't have to do anything else.


### Option 2: Installing 'miniconda'

You can also get up and running with [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install). Follow the instructions in the link, specific to your operating system. This will require that you do a number of things in the terminal window, but the instructions should be clear enough that you can set things up even if you haven't used a terminal window before.

Once you have installed and setup up Miniconda, run this command in the terminal window to install the extra packages that you will need for this course

	`conda install python=3.11 numpy scipy matplotlib jupyter` 


## Downloading the notebooks and data


### Option 1: Using the Github Desktop application (easiest)

The Github Desktop application is both a nice tool to interface with git, and a way to use git without needing to use a terminal.  Here is what you will need to do to use Github Desktop.

1. Install the github desktop app from here: [https://desktop.github.com/](https://desktop.github.com/)
2. You should make a Github account if you do not have one, as it will be useful beyond this course, and is needed to download the repository
3. Once you have installed github desktop and made an account, click on the "Current Repository" box in the upper left corner.  This gives you a text box and a pull-down menu. 
     1. Alternatively, where it says "Let's get started!", click "Clone a Repository from the Internet", and then select the "URL" tab.
4. Type in 'KIPAC/Physics89L' into the test box and select "Clone Repository..." from the drop-down menu.
5. This will "clone" the repository onto your computer, for example putting it in "Documents/GitHub/Physics89L"
     1. You can always change this installation location if you have already have a file organization structure in place on your laptop.
6. At any point you can then update your local copy from the "origin" repository by clicking on "Fetch Origin" button.
7. This will show all the changes that you have made to your local version.  As part of the course, we'll talk about how to keep your local changes and merge any updates from the "origin".


### Option 2: Using git

`git` is a software versioning tool.  It will allow you to fetch the latest version of the notebook repository to your computer.
You can find instructions on how to install git [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

Once you have installed git, from a terminal window you can do:

`git clone https://github.com/KIPAC/Physics89L`

to install the repository on your computer.

Once you interact with the files and make changes, your code will necessarily diverge from the "origin" repository. As part of the course, we'll talk about git branches and how to keep track of changes locally while still incorporating changes from a "main" branch.


### Option 3: Direct download

If you don't want to use git, you can always just download a snapshot of the repository each week before class.

Go to https://github.com/KIPAC/Physics89L and click on the green "Code" button in and select "Download ZIP" from the drop-down menu.

Note that this will download the current version of the repository, so you will want to do this each week before class to include any changes made.  You probably want to save the older version first so that you can refer to previous work.


## Open the Jupyter Notebook browser

If you installed Anaconda, then you can start jupyter from the Anaconda Navigator, which has a graphical interface.  Navigate to: Applications -> Anaconda Navigator, then click on the "Launch" button in the "Jupyter Notebook" box.

One you have started jupyter, it will pop up a browser window showing the contents of what jupyter treats as your home folder.  (Either the folder you ran the `jupyter-notebook` command from, or a folder that you can set in the anaconda preferences).  From there you should navigate to the folder that you have installed the course in (the git repository you cloned earlier) and click on the notebook you want to run.

If you installed jupyter using miniconda you can start jupyter from a terminal by typing:

`jupyter-notebook`


## Test your setup

To test your setup, navigate to "nb" folder of this repository and run the "Test_Notebook.ipynb" notebook.

If you click on the "Run" button twice, and you have everything set up correctly you should see a plot that looks like this:

[It Works](https://github.com/KIPAC/Physics89L/blob/main/nb/figures/it_works.png)

You can also run each individual "cell" by clicking on it and typing `Shift+Enter`.


## Backup plan

You can run these notebooks using jupyter on the cloud if you run into issues installing the software on your computer. This uses the service "binder" to run the notebooks on a remote server on the web.  This should only be used as a temporary backup option- it has the disadvantage that it can be difficult to save the work you do in the notebook.

You can run the notebooks for week 1 by navigating to this site:

[My Binder](https://mybinder.org/v2/gh/KIPAC/Physics89L/HEAD)

It is fine to run binder the first week, but we would like to get everyone set up with the software on their computers by the second week.  This will make it easier for you to save you work and include it in the lab reports. Please contact one of the instructors for help.



<!--  LocalWords:  Jupyter IPython miniconda github-desktop numpy
 -->
<!--  LocalWords:  scipy matplotlib github
 -->
