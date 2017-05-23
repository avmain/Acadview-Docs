# How to install Virtualenv on Windows

## Get PIP

1. Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py). (Make sure that it is saved as a Python file, that is, with extension .py)

2. We need to start command prompt as an admin.

To start a command prompt as an administrator - 

Click Start, click All Programs, and then click Accessories.

3. Right-click Command prompt, and then click Run as administrator - If the User Account Control dialog box appears, confirm that the action it displays is what you want, and then click Continue.

4. Go to the directory where get-pip.py was download. For eg, if it was on Desktop, use cd Desktop in the command prompt.

![](/img/pip.png)


5. Then, run it from the command prompt - `python get-pip.py`

![](/img/pipinstalled.png)


## Get Virtualenv
**Note: Make sure that Python scripts is added into the Path variable (C:\Python27\Scripts;)**

1. We need to start command prompt as an admin. 

To start a command prompt as an administrator - 

Click Start, click All Programs, and then click Accessories.

2. Right-click Command prompt, and then click Run as administrator - If the User Account Control dialog box appears, confirm that the action it displays is what you want, and then click Continue.

3. Install distribute using pip as shown below.

`pip install distribute`

![](/img/distribute.png)


4. Next, install virtualenv - `pip install virtualenv`

![](/img/virtualenv.png)