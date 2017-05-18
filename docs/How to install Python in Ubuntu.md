# How to install Python in Ubuntu

1. By default python2 and python 3 come pre-installed in Ubuntu. You can check the version of each of them by following the given procedure.Open the terminal from either of the given two steps

    i. Open the Search Dash by clicking the Ubuntu icon in the upper-left, type "terminal", and select the Terminal application from the results that appear.

![terminal](/img/terminal.png)


    ii. Press `Ctrl+Alt+T` from the keyboard.

2. To check the version of python2, type `python2 --version` in the terminal. You can also type `python --version` in the shell as by default python2 will be displayed. To check the version of python3, use the command `python3 --version`

![python version](/img/python_version.png)


3. In case you do not have python 2.7 installed, you can do it manually.

4. Use this link to land to the download page of Python organisation from where you can then download the latest Python2 which by now is 2.7.13.

![python org](/img/python-download.png)

5. You may also use any other version that are available in the archive. This documentation installs Python 2.7.6. The procedure for any version will remain the same.

![specific python](/img/specific_python.png)


6. Click on the download button. This will prompt you to save an archive. Save it.

![download python](/img/download_python.png)

7. From the terminal, go to the directory where the downloads are saved. This can be `Downloads` directory for you.

8. Unzip the archive folder by using the command `tar xvf Python-2.7.13.tar.xz`

![unzip folder](/img/extract_python.png)


9. Go inside the extracted folder by using the command `cd` and then run the command `./configure`

![configure python](/img/configure_python.png)


10. After this run the command `sudo make`

![make file](/img/makefile_python.png)


## Starting Command line interface
1. Ubuntu can run one version of each Python 2 and Python 3 simultaneously.

2. To start command line interface for Python 2, type `python` in the terminal or `python2`.

![CLI](/img/python_cli.png)
