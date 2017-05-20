# Use Git and Github on Ubuntu

1. Open the terminal by either

	i. Open the Search Dash by clicking the Ubuntu icon in the upper-left, type "terminal", and select the Terminal application from the results that appear, or

	ii. Press Ctrl+Alt+T from the keyboard.

	![terminal](/img/terminal.png)



2. Type the command `sudo apt-get update`

3. Install through the command `sudo apt-get install git`

4. Create an account on [github](https://github.com/) if not already created.

	i. Enter the details in each step. For a suitable username, you can use something that includes your name with digits as this github username will be visible on all you profiles in future. This includes resumes, curriculum vitae, open-source lists, etc. It is important to have a meaningful username.

	![github signup](/img/github_account.png)


  	ii. In the next step, choose the free public repository plan.

  	![github repo](/img/github_repo.png)


  	iii. After you continue, you will get to step 3, you can fill in your choices as any and press submit or can simply skip that step. In both cases, your account will be created.

  	![github form](/imd/github_form.png)


5. To set up github with git use the command below, and replace 'github_username' with your username on github. (as chosen in the 4th step) `git config --global user.name "github_username"`

  **for example, for username name09, use the command:
   `git config --global user.name"name09"`**

6. Set your email with the command below and replace 'email@example.com' with the email address you used to create the account on github. (as chosen in the 4th step) `git config --global user.email "email@example.com"`   

  **for example, for email name109@gmail.com, use the command :
  `git config --global user.email "name109@gmail.com"`**