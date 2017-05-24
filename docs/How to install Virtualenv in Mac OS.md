# How to install Virtualenv in Mac OS
You will need pip for installing virtualenv. There are two ways of installing pip. You can either run a script to install pip or use easy_install if you have Mac OS X.

## Use get-pip.py
1. Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py). (Make sure that it is saved as a Python file, that is, with extension .py)
2. Open up the terminal by going to Applications -> Utilities -> terminal
3. In the terminal, go to the location where get-pip.py is stored, and run this script by `sudo python get-pip.py`. This will install pip.
4. Type `sudo pip install virtualenv` to install virtualenv.

## Use easy_install
1. Open up the terminal by going to Applications -> Utilities -> terminal
2. In the terminal, type `sudo easy_install pip`. This will install pip for you.
3. Now you can use pip to install virtual environment by typing `sudo pip install virtualenv`.