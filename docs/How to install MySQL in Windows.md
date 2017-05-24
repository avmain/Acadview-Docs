# How to Install MySQL Server and Workbench in Windows

1. Use this [link](https://dev.mysql.com/downloads/mysql/) and go for MySql MSI, click on Go to download page. From there you will land onto another page from where you can download the installer.

![](/img/server.png)


![](/img/server_1.png)


2. It might ask you to login or sign up but you can simly skip this step for now.

![](/img/server_2.png)


3. A .msi file will be downloaded. After its download is complete, double click on the file and click on Run.

![](/img/server_3.png)


4. The installer will start and will present a license. Accept it and click Next.

![](/img/server_4.png)


5. In the setup tool, choose custom. It will allow you to download specific tools of your choice. Click on Next.

![](/img/server_5.png)


6. In the next window, you need to choose the tools you want to install. Select the following for MySql server and workbench. Make your choise based on your system(32 bit or 64 bit). The following choices are for a 64 bit system. (Choose X84 if y options you have 32 bit system)

    1. MySql servers -> MySQL Server - X64

    2. Applications -> MySQL Workbench - X64

    3. MySQL Notifier -> MySQL Notifier - X86

    4. MySQL Connectors -> Connector/Python for Python 2.7 X64 (You need python 2.7 in the system for installing this)

    5. Documentations -> MySQL Documentation

    ![](/img/server_6.png)

    ![](/img/server_7.png)

    ![](/img/server_8.png)

    ![](/img/server_9.png)

    ![](/img/server_10.png)
5. Click Next and then if you see a Check requirements page, select all the options and then Execute. After it is succcessful, close the pop up and click Next in the installer.

![](/img/server_11.png)


![](/img/server_12.png)


![](/img/server_19.png)


6. You will see a list of all the products that you selected before ready to be installed. Click on Execute.

![](/img/server_24.png)

7. In the Configuration window, click Next.

![](/img/server_18.png)


8. For Networking, let the entries remain default and click Next.

![](/img/server_13.png)


9. In the Accounts and Roles, you need to enter a root password, **remember this or write it down somewhere because this password will be needed to access MySQL later**.

![](/img/server_14.png)


10. In Window service, let the entries remian default. Click Execute on the Apply configuration step.

![](/img/server_15.png)


![](/img/server_16.png)


![](/img/server_20.png)


11. Finish this up. You will now be able to access the workbench from the password used before. You can search for MySQL workbench in your system and start it by double clicks.

![](/img/server_21.png)


![](/img/server_22.png)


![](/img/server_23.png)

