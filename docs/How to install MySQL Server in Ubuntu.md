# How to install MySQL Server in Ubuntu

1. Open the terminal. Use the command `sudo apt-get install mysql-server`.

2. It will start the installation. Type `Y` or `y` when asked to continue.

![](/img/mysql1.png)


3. You may be asked to type a password to for the user. Enter a password of you choice. **Remember this password or better write it down as it will be needed to access mysql server later.**

4. Once the installation is done, you will see something like the below.

![](/img/mysql2.png)


5. You can check by using `mysql` in the terminal. In case it throws an error, use the command `sudo mysql -p` to start mysql. You will need to enter the password you kept while installing mysql before.

![](/img/mysql5.png)

# How to install MySQL Workbench in Ubuntu

Note: You should have MySQL server installed in your system.

1. Open the terminal. Use the command `sudo apt-get install mysql-workbench`. Enter password when prompted.

2. Enter yes to continue the installation. You will see something as below when the installation is successful.

![](/img/mysql3.png)


![](/img/mysql4.png)


3. After the installation is done, search for the workbench in the dashboard and double click on it to start it.

![](/img/mysql6.png)


4. You can right click and lock the workbench to launcher for easy access in the future.

![](/img/mysql7.png)
