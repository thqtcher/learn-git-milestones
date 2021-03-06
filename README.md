# Git Milestones

Below is a list of tasks. By mid-semester, everyone should...

1. Understand what the task is asking
1. Be able to do the task
1. Make it clear through your actions you understand what's happening


### Instructions

1. Fork this repository
1. Complete and check off each of the tasks below, adding content where prompted with: **??**
1. Note: Sometimes I give the instructions or command you need and sometimes you have to read the documentation to find it.
1. After you finish, celebrate your Git proficiency! 🙌  


## Git Basics


### Fork this repository
Create a Github account and make your first commit

- [x] [Create a Github account](https://github.com/join)
- [x] Fork this repository [learn-git-milestones](https://github.com/omundy/learn-git-milestones) (click the Fork button, top right).
- [x] Edit the README file (click the pencil icon) and add your favorite emoji here: 😁
- [x] Commit changes to the README file directly to the master branch with the message `commit #1 from Github.com`
- [x] View the commit history and confirm your edits


### Git Installation
Install your development environment

- [x] Install Git on your machine

Windows: Install [Git for Windows](https://gitforwindows.org/) (includes [Git BASH](https://www.atlassian.com/git/tutorials/git-bash), its own version of the bash shell)

Mac:
1. Install the [homebrew package manager](https://brew.sh/)
1. Install git using Homebrew `brew install git`
1. Set your default shell to bash `chsh -s /bin/bash` - You'll be prompted to type a password. The command line doesn't give you feedback that you're typing. Just type your password and hit enter. Backspace a lot if you make a mistake.

- [x] On the command line, confirm Git is installed by typing `git` at the prompt and hitting enter
- [x] [Install Github Desktop](https://desktop.github.com/)
- [x] Connect your Github account in Githhub Desktop




## Basic Git Workflows
You should be able to perform a basic Git workflow using Github.com, the command line, Github Desktop, and Git in Atom. Using four different interfaces will give you practice and help you understand Git better. You've already forked and made a commit on Github.com so let's move to Github Desktop ...


### In Github Desktop
You should be able to ...

- [x] In Github Desktop, clone the fork (you made above) [learn-git-milestones](https://github.com/omundy/learn-git-milestones) ...
  - [x] File > Clone Repository > Github.com and select it ...
  - [x] Local Path: Click "Choose" and add a new folder on your computer. This will be the base folder for your work in this class: `critical-web-design`
  - [x] Click "Clone" to make a local copy
- [x] Open the repo in Atom: Repository > Open in Atom  
- [x] In Atom, edit this README file and add your *second* favorite emoji here: 😁
- [x] In Github Desktop, confirm the README file was saved and shows your new changes in the Changes tab
- [x] Commit your changes to the README file directly to the master branch with the message `commit #2 from Github Desktop`
- [x] Click Push origin to push your changes back to remote repo  
- [x] Confirm the changes to the README file were pushed: Choose Repository > View on Github
- [x] Click on the README file and then click on History to see the history of this file


### Command line (CLI)
You should have a basic familiarity with the command line in case you need to do advanced Git commands. Many folks use the CLI for file editing, though I'm not going to make you suffer when we have Atom installed. You've used most of these already through a GUI (e.g. `git status`, `git add`, `git commit`, `git push`) ...


- [x] In Github Desktop, with the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo you cloned above selected, click Repository > Open in Terminal ("Bash" in Windows?)
- [x] Use the CLI to navigate directories  
  - [x] List files in this directory: `ls`
  - [x] List files in this directory, including hidden: `ls -la`  
  - [x] Confirm the existence of the `.git` directory (where Git versions and config are stored)
  - [x] View your current directory and copy the full path: `pwd`
  - [x] Open this README file in Atom and paste that path here: /c/Users/thatc/desktop/critical-web-design/milestone-1/learn-git-milestones

- [x] Use Git on the CLI
  - [x] [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
  - [x] View the status of your repo: `git status`
  - [x] View the changed files of your repo: `git diff`
  - [x] Add all changed files to the staging area `git add .`
  - [x] View the status of your repo `git status` to confirm it has been staged
  - [x] Commit your changes with the message `commit #3 from CLI`
  - [x] Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)


### Git in Atom
You should be able to ...

- [x] In Github Desktop, open this repo [learn-git-milestones](https://github.com/omundy/learn-git-milestones) in Atom: Repository > Open in Atom  
- [x] In Atom, edit this README file and add your *third* favorite emoji here: 😁
- [x] Create a new file `hello.txt`, add some text and save it.
- [x] Display the Git panel (click the small Git button at the bottom right).

![atom-git-menu](img/atom-git-menu.png)

- [x] Select on your file(s) in Unstaged changes and confirm your changes match what you expect to see
- [x] Double click on each file with changes to stage them  
- [x] Commit your changes directly to the master branch with the message `commit #4 from Atom`




## Create a new repository

- [ ] Create a repository from scratch
  - [ ] ✏️ In Github Desktop, create a new repository with the name: `my-awesome-project`
  - [ ] Local Path: Click "Choose" and create a new folder `my-awesome-project` inside the `<your-class-name-here>` folder you made above
  - [ ] Click Create Repository
  - [ ] This should now be your class folder's directory structure.
  ```
  <your-class-name-here>
    |-- my-awesome-project
    |-- learn-git-milestones
  ```
  - [ ] Open your new repository in Atom (with Github Desktop or drag the `my-awesome-project` project folder into Atom)
  - [ ] ✏️ Add a README file: `README.md`
  - [ ] ✏️ In the README write your name and the date
  - [ ] ✏️ Use some [Markdown tags](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)




## Create a Github.io page
Create a github.io site for your repository ...

- [ ] ✏️ Create a file called `index.html` in your new repo and add the following html
```
<!DOCTYPE html>
<html>
<head>
<title>My first github.io website</title>
</head>
<body>

<h1>Hello world!</h1>
<p>🙌</p>

</body>
</html>
```
- [ ] Set up a [Github page](https://pages.github.com/) "project site" for your repo
  - [ ] Go to the settings page for your repo on Github.com and scroll aaaaallllll the way down to the Github Pages section
  - [ ] Select the main branch source and click save
  - [ ] Do not use a theme. Start from scratch
  - [ ] Visit your project site at http://*username*.github.io/my-awesome-project
  - [ ] Update your project, push a new commit, and confirm your updates (note: [changes are not always instant](https://github.com/omundy/dig245-a1/deployments/activity_log?environment=github-pages))
  - [ ] Paste this link here:






## Turn in this Assignment
Now that we have basic Git commands out of the way use Git to create and turn in your assignment ...

- [ ] Complete all of the items on this README
- [ ] Test your file(s) in a web browser
- [ ] Commit and push the files to Github
- [ ] Paste the github.io link into the appropriate Moodle forum




## Git Advanced

That is all that is required for this milestone. See the `ADVANCED.md` file if you would like to continue learning Git.



## Grading
- [ ] Points: `20`
	- [ ] Git Basics & Basic Git Workflows
		- [ ] `2` forked repo correctly
		- [ ] `2` linked to correct Github Pages site for repo
		- [ ] `3` favorite emoji
		- [ ] `1` mark steps as complete
		- [ ] `2` commit names
		- [ ] `1` path of local repo
		- [ ] `2` `hello.text` with changes
	- [ ] Create a repository and submit an assignment
		- [ ] `1` create the new `my-awesome-project` repo from scratch
		- [ ] `2` add `README.md` with markdown tags
		- [ ] `2` add `index.html` with tags
		- [ ] `2` turn in this Assignment



## Credits

Thanks to [Jesse Farmer](https://github.com/jfarmer) for inspiring this milestone assignment.
