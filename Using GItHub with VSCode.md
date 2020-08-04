## Using Git with VSCode
At first, I thought this was going to be difficult. But I managed to get everything set up within 5 minutes. These are the steps I followed to set up Git to pull and push any repositories and changes!

### Download Git
The first step is to, of course, download [Git](https://git-scm.com/downloads). Get the appropriate version for your operating system and set it up. During installation, you will be asked to choose the default editor used by Git. At this stage, you will want to select Visual Studio Code as Git's default editor.

![Select VSC as Git's Default Editor](VSC%20Selected.png)

### Setting up Git
You will need perform some initial set up for Git. If you do not perform this step, you will not be able to use Git with VS Code. Open up the Git Bash program. You will see a terminal. In it, enter the following commands:

```
git config --global user.name "yourusername"
git config --global user.email youremail@email.com
```
