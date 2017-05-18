How to install Python in Windows

1. Download: To download Python version, find the suitable copy here . The latest for Python 2 is 2.7.13

![python.org](/img/python-download.png)

2. Install: After downloading Python, we need to install it in our system.Navigate to the download location on your computer, double click the file and press Run when the dialogue box pops up. It may ask for your admin password, enter where required.
https://d2mxuefqeaa7sj.cloudfront.net/s_EC6E89CD6AB8E58FAEB1741A08DAEF7A7935DFCC68CA1E07CEED87B46A0E0BAB_1494786654032_python_add.png

3. Set Path: Once you have successfully installed Python, you need to add System Path Variable so that Python can be accessed from anywhere in the system.
    i. Begin by opening the start menu and search for System Properties.
    ii. When the “System Properties” window appears, go to “Advanced” tab and the click on “Environment Variables…”
https://d2mxuefqeaa7sj.cloudfront.net/s_EC6E89CD6AB8E58FAEB1741A08DAEF7A7935DFCC68CA1E07CEED87B46A0E0BAB_1494786693199_system.png

    iii. Once you have the “Environment Variables” window open, click on new to create a “New ….“ variable for Python.
    iv. Choose a variable name, say, PythonPath and then add the path of the directory than holds python after installation. This is generally the C:/ drive. So enter the path `C:\Python27\;C:\Python27\Scripts;`
https://d2mxuefqeaa7sj.cloudfront.net/s_EC6E89CD6AB8E58FAEB1741A08DAEF7A7935DFCC68CA1E07CEED87B46A0E0BAB_1494786724215_systemvariable.png



    v. Once this new variable is added, go to the existing variable named `Path` in the System variables and add the `PythonPath` at the end of the complete value string. This will be added as `%PythonPath%`
    vi. Click on OK in the subsequent pop-up windows that appear. Your path will be set. You can check your path variable by using the command `echo %PATH%` in the command prompt.
    vii. Alternatively, you can add the python path without creating a new variable. You can directly add `C:\Python27\;C:\Python27\Scripts;`in the environment variable named `Path` by selecting the variable and then clicking on Edit and subsequently saving it.
