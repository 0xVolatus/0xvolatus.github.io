# 0xParadoxic | 0xParoxystique
These are my aliases (Paradoxic / Paroxystique), which I prefer to be identified by online. I am 20 this year, currently studying to be a penetration tester. I love joining Capture the Flag events and would post my write ups whenever time permits me.

The index page of my GitHub pages website will be used for random stuff that I do not want to Google again (which may also be useful to others). My Write Ups will be on separate pages, which I will link under this segment.

## Latest Articles:
[Using GitHub with VSCode](https://0xvolatus.github.io/)  
[Hacktivity 2020 Writeup](https://0xvolatus.github.io/Hacktivity-2020/)

---

## Using Git with VSCode
At first, I thought this was going to be difficult. But I managed to get everything set up within 5 minutes. These are the steps I followed to set up Git to pull and push any repositories and changes!

### Download Git
The first step is to, of course, download [Git](https://git-scm.com/downloads). Get the appropriate version for your operating system and set it up. During installation, you will be asked to choose the default editor used by Git. At this stage, you will want to select Visual Studio Code as Git's default editor.

![Select VSC as Git's Default Editor](/Using%20GitHub%20with%20VSCode/VSC%20Selected.png)

### Setting up Git
You will need perform some initial set up for Git. If you do not perform this step, you will not be able to use Git with VS Code. Open up the Git Bash program. You will see a terminal. In it, enter the following commands:

```
git config --global user.name "yourusername"
git config --global user.email youremail@email.com
```
That's all there is to setting up Git!

### Preparing Visual Studio Code
Head to the extensions segment in VSC and search for **Github Pull Requests**. Install it, then reload VSC. Open the command palette using Ctrl+Shift+P and type git clone and select it. 

![Git Clone in Command Palette](/Using%20GitHub%20with%20VSCode/Git%20Clone.png)

It should request the URL of your GitHub repository and once entered, it will clone the folder into your computer.

![Git Clone asking for URL](/Using%20GitHub%20with%20VSCode/Clone%20URL.png)

When it has successfully downloaded, you can choose to open the folder. That's it - you have just successfully cloned your repository from GitHub!

### Committing Changes
Before you can commit any changes to GitHub, you will need to login and authenticate VSCode to use Git. At the bottom left corner of your VSCode, click on your account logo. 

![Account](/Using%20GitHub%20with%20VSCode/Account.png)

It should bring up the GitHub login page. Login with your credentials and it will automatically authenticate VSCode to use Git.

![Authenticating VSCode](/Using%20GitHub%20with%20VSCode/Login.png)

You are now ready to commit any changes you have made to your repository! Click the icon under the search menu for Source Control.

![Source Control](/Using%20GitHub%20with%20VSCode/Source%20Control.png)

Upon entering it, you should see the changes that you have made to your files. You can choose to stage specific changes, or stage and commit all of them by pressing the Tick symbol and pressing Yes or Always on the pop up.

![Staging and Committing](/Using%20GitHub%20with%20VSCode/Staging%20and%20Committing.png)

Once you have committed all your changes, all that's left to do is to push them to your repository! You can easily do so by pressing the menu button and selecting push.

![Pushing Changes](/Using%20GitHub%20with%20VSCode/Pushing.png)

Congratulations! You have now set up GitHub to work perfectly with Visual Studio Code :) However, you may still run into some problems here and there when you changes are performed on other machines. Therefore, we should also set up our Git Bash terminal in VSC!

### Setting up Git Bash on VSC
Open the command palette and search for Default Terminal. Select it, and choose Bash to be your default. Once you have completed the step, launching a new terminal will bring up a bash terminal! How splendid.

![Bash Terminal](/Using%20GitHub%20with%20VSCode/Bash.png)

This is one of the most critical commands that you will need to commit to memory. In essence, it is a combination of fetching and merging the remote repository with your local repository. This command is: ```git pull```. Here's the syntax:
```
git pull (remoterepositorylink)
```

Entering that command will retrieve all the changes from the remote repository and merge if with the repository on your computer. 