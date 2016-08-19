# CDAC Hyderabad Workshop

This folder contains ipython notebooks and the corresponding required datasets for the following:

  1. SVM
  2. K-nearest Neighbours
  3. Linear Regression
  4. K-means clustering
  5. Boosting / Ensemble Methods
  6. DBSCAN

The aim of this exercise is to give the participants a fundamental understanding of traditional Machine Learning techniques used in the pre-Deep Learning era for solving various problems. Participants are advised to download / clone this repository and create a virtual environment for installing the dependencies required for running this code.

# Instructions

## Setup the Environment


`virtualenv` is a tool to create isolated Python environments. `virtualenv` creates a folder which contains all the necessary executables to use the packages that a Python project would need.

If it is not already installed, execute `sudo apt-get install python-virtualenv` on your Ubuntu 14.04 LTS machine to install the python `virtualenv` package.

Then, to **create the directory and setup the virtualenv**:

    $ mkdir iith_ws
    $ cd iith_ws
    $ virtualenv .
    $ source bin/activate


**Clone this repository**

    $ git clone https://github.com/ArghyaPal/C_DAC_Hyderabad_Workshop.git
    $ cd C_DAC_Hyderabad_Workshop
    

**Deactivate `virtualenv`**

Once you are done working in the virtual environment, execute `$ deactivate$ to deactivate it.


## Install dependencies

To install the dependencies, navigate to the root directory of this repository then execute `$ pip install -r requirements.txt`.
This will install all python modules required for this workshop.


## Starting Jupyter

To get started with the tutorials, execute:

    $ cd Pre-Workshop
    $ jupyter notebook

This will open a browser window with the tutorial files displayed in a list. Simply click on a tutorial file to dive in. Have Fun!


## Contact details for queries.

In case of any difficulties / problems with running the code or any doubts, feel free to reach out to the Indian Institute of Technology Hyderabad (IIT-H) team.

  1. Dr. Vineeth N Balasubramanian  (vineethnb@iith.ac.in)
  2. Adepu Ravi Sankar (cs14resch11001@iith.ac.in)
  3. Arghya Pal (cs15resch11001@iith.ac.in)
  4. Akilesh B (cs13b1042@iith.ac.in)
  5. Sahil Manocha (es13b1019@iith.ac.in)
