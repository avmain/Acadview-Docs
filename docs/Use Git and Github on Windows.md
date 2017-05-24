# Use Git and Github on Windows

1. Use this [link](https://git-scm.com/downloads) to download git. It will automatically start the download. In case it doesn't start, click on the manual download link.

![git dpwnload](/img/git1.png)


2. Run the executible file that has been downloaded (.exe) by double clicking on it.

3. The setup procedure will start, accept the public license and move forward.

![](/img/git2.png)


4. For then location where git will be installed, let it remain default.

![](/img/git3.png)


5. In components window, select the Addditional icon checkbox for easy access of git from the Desktop.

![](/img/git4.png)


6. Next, it will ask for name of the application in the start menu, you can keep it default.

![](/img/git5.png)


7. Choose the option to use git from command prompt.

![](/img/git6.png)


8. In the subsequent three windows, let the entries be default and click next.

![](/img/git7.png)


![](/img/git8.png)


![](/img/git10.png)


9. Click on Install and this will start the extraction.

![](/img/git11.png)


![](/img/git12.png)


10. After the extraction ends, click on finish. This will complete your git setup.

![](/img/git13.png)


**We will now configure our github account through the command prompt**
1. Create an account on [github](https://github.com/) if not already created.

	i. Enter the details in each step. For a suitable username, you can use something that includes your name with digits as this github username will be visible on all you profiles in future. This includes resumes, curriculum vitae, open-source lists, etc. It is important to have a meaningful username.

  ![github signup](/img/github_account.png)


  ii. In the next step, choose the free public repository plan.

  ![github repo](/img/github_repo.png)


  iii. After you continue, you will get to step 3, you can fill in your choices as any and press submit or can simply skip that step. In both cases, your account will be created.

  ![github form](/img/github_form.png)


2. To open the command prompt, search for it.

![](/img/git14.png)
   
3. set up github with git use the command below, and replace 'github_username' with your username on github. (as chosen in the 4th step) `git config --global user.name "github_username"`

  **for example, for username name09, use the command:
   `git config --global user.name "name09"`**

4. Set your email with the command below and replace 'email@example.com' with the email address you used to create the account on github. (as chosen in the 4th step) `git config --global user.email "email@example.com"`   

  **for example, for email name109@gmail.com, use the command :
  `git config --global user.email "name109@gmail.com"`**

![](/img/git15.png)