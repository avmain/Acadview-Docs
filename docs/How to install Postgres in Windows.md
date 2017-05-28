# How to install PostgreSQL in Windows

The PostgreSQL installer for Windows has PostgreSQL server and pgAdmin which is a GUI for managing databases. We'll look how to install them and then connect to the server.

1. Use this [link]() to download the executible file of the installer. Choose a version of PostgreSQL (for example, 9.5) and choose your system type, that is, 32 or 64 bit. Click on Download.

![](/img/postgresw1.png)


2. When the download finishes, double click on the executible file and let the installer start. If you see a c++ window like below, let it finish processesing.

![](/img/postgresw2.png)


3. Once the installer starts, click Next. Let the directory location for Postgres and the data remain default and click Next.

![](/img/postgresw3.png)


![](/img/postgresw4.png)


![](/img/postgresw5.png)


4. It will ask for setting a password. Remember the password you enter or note it down as it will be required when you access the server in future.

![](/img/postgresw6.png)


5. You can le the port number stay 5432 qnd the locale as default. Click on Next on the ready to install window.

![](/img/postgresw7.png)


![](/img/postgresw8.png)


![](/img/postgresw9.png)


6. Once the installation finishes, unheck the build stack option and then finish the setup.

![](/img/postgresw10.png)


![](/img/postgresw11.png)


7. You can check if the installation was succesfull by searching for pgAdmin in your system and it pas part of the installation package.

![](/img/postgresw12.png)


8. Open pgAdmin3 and you will be able to see PostgreSQL server on post 5432. DOuble click on the server to connect to it.

9. Enter the password that you kept while installing PostgreSQl.

![](/img/postgresw13.png)


10. Once you connect to the server, you will be able to see the databses and stuff.

![](/img/postgresw14.png)