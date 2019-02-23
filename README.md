# Data Science Portfolio and Python Machine Learning


#### To do an end-to-end Machine Learning project we need to do the following steps

1. Understand the requirements of the business.
2. Acquire the dataset.
3. Visualize the data to understand it better and develop our intuition.
4. Pre-process the data to make it ready to feed to our ML model.
5. Try various models and train them. Select one that we find best.
6. Fine-tune our model by tuning hyper-parameters
7. Present your solution to the team.
8. Launch, monitor, and maintain your system.


# Installation

First, you will need to install [git](https://git-scm.com/), if you don't have it already.

Next, clone this repository by opening a terminal and typing the following commands:

    $ cd $HOME  # or any other development directory you prefer
    $ git clone https://github.com/gurupratap-matharu/Data-Science-Projects


If you are familiar with Python and you know how to install Python libraries, go ahead and install the libraries 

## Python & Required Libraries

You can check which version(s) you have by typing the following commands:

    $ python3 --version  # for Python 3


* If you don't have Python 3, I recommend installing it (Python 3.6+ is preferable). 


On Linux, unless you know what you are doing, you should use your system's packaging system. For example, on Debian or Ubuntu, type:

    $ sudo apt-get update
    $ sudo apt-get install python3


## Using Anaconda

When using Anaconda, you can optionally create an isolated Python environment dedicated to this project. This is recommended as it makes it possible to have a different environment for each project (e.g. one for this project), with potentially different libraries and library versions:

    $ conda create -n venv python=3.5 anaconda
    $ conda activate venv

This creates a fresh Python 3.5 environment called `venv` (you can change the name if you want to), and it activates it. This environment contains all the scientific libraries that come with Anaconda. This includes all the libraries we will need (NumPy, Matplotlib, Pandas, Jupyter and a few others), except for TensorFlow, so let's install it:

   
Great! You're all set, you just need to start Jupyter now.

## Starting Jupyter

You can start Jupyter, simply type:

    $ jupyter notebook

This should open up your browser, and you should see Jupyter's tree view, with the contents of the current directory. If your browser does not open automatically, visit [localhost:8888](http://localhost:8888/tree).  

Great! We are all setup to do some data science and machine learning!


## Note of Thanks

I would like to thank authors of various books especially Aurélien Géron and Frank Kane their wonderful books on Handson DataScience and Machine Learning with ScikitLearn and TensorFlow. I highly recommend both of these books.


