## Use Git and Github on Mac OS
1. Use this [link](https://git-scm.com/downloads) to download git for Mac OS.

2. Click on download for MAc OS X, it will automatically start the download.

3. Open the .dmg folder that gets downloaded and double click on the .pkg file to start the installation.

4. Follow the instructions of the isntaller. Enter the password when prompted.

5. Once the installation is finished, you can check if it was successful by using `which git` in the terminal. Open the terminal by Applications -> Utilities -> Terminal. It will give you the location of git.

**We will now configure our github account through the terminal**
1. Create an account on [github](https://github.com/) if not already created.

	i. Enter the details in each step. For a suitable username, you can use something that includes your name with digits as this github username will be visible on all you profiles in future. This includes resumes, curriculum vitae, open-source lists, etc. It is important to have a meaningful username.

  ![github signup](/img/github_account.png)


  ii. In the next step, choose the free public repository plan.

  ![github repo](/img/github_repo.png)


  iii. After you continue, you will get to step 3, you can fill in your choices as any and press submit or can simply skip that step. In both cases, your account will be created.

  ![github form](/img/github_form.png)
   
2. In the terminal, set up github with git use the command below, and replace 'github_username' with your username on github. (as chosen in the 4th step) `git config --global user.name "github_username"`

  **for example, for username name09, use the command:
   `git config --global user.name "name09"`**

3. Set your email with the command below and replace 'email@example.com' with the email address you used to create the account on github. (as chosen in the 4th step) `git config --global user.email "email@example.com"`   

  **for example, for email name109@gmail.com, use the command :
  `git config --global user.email "name109@gmail.com"`**
