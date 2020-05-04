# PythonPackage
This is a simple package created using python and can be installed using commands like pip and conda install. 
This is for educational purposes and was created as a hands on assignment from Udacity Course.

# Installation
You can create a virtual environment and tinker with it yourself. Just clone and download the files available in this repository and test using virtual environment to ensure that it does not affect your current python installation.

### Installing Virtual Environment
For Python 3 and above, the virtual environment package is already installed and this step can be skipped. But for older python version, use this

#### OnMac and Linux(Older Python versions):
python3 -m pip install --user virtualenv

#### Windows(Older Python version):
py -m pip install --user virtualenv

### Creating And Activating Virtual Environment

#### Mac and Linux
python3 -m venv env
source env/bin/activate

#### Windows
py -m venv env
.\env\Scripts\activate

In order to leave the virtual environment just use 'deactivate' command.


## Installing the package
### Use "pip install ." in your virtual environment by setting your working directory to the folders that consists the cloned repo files.
It will install itself using the setup.py file and initialize the based on the __init__.py file

### Use pip install probability-dstbn to install the package directly to your machine 

Then within the Python interpreter, you can use the distributions package like: <br>
from probability_dstbn import Gaussian,Binomial <br>
gaussian_one = Gaussian(25, 2) <br>
gaussian_one.mean <br>
gaussian_one + gaussian_one <br>
binomial= Binomial(0.4,25) <br>

You can view the python files of the package yourself and edit it to better understand it yourself.


