# TeachingGit
A basic repository containing text files for teaching COBRA team members git basics. 

Key Terms:
==========
	repository – (aka repo) a storage location for files, most commonly one per project
	clone – copy a repository’s files into a directory on your own machine
	remote – a repository that exists on the internet, for example on Github
	origin – a remote that a project was originally cloned from
  	branch – a series of changes, multiple branches of the same repository can exist at once
	main – (aka master) the original or most unified branch in the repository
	fetch – track changes to the remote that don’t exist on local repository
	pull – retrieve changes from a branch and copy onto local repository
	add – track changes to a file on your local machine
  	commit – set up a series of changes on the added files without sending them to the remote, consider each commit as a potential “update”
	push – submit the most recent commit to the remote, updating the files
  	gitignore – a manifest of the files that git should not track, like those with sensitive information

7/13 - Today’s Topics:
======================
Retrieving code from a git repository, and updating it with changes on your local machine..

Updating your own local repository with changes from the remote.



Part 0 - Prerequisites
---------
Install Git for your machine – https://github.com/git-guides/install-git 

Be familiar with the command line, at least for changing directories:
[Windows](https://www.howtogeek.com/659411/how-to-change-directories-in-command-prompt-on-windows-10/)
[macOS](https://www.macworld.com/article/221277/command-line-navigating-files-folders-mac-terminal.html#:~:text=If%20you%20type%20cd%20..,you%20issued%20the%20cd%20command.) 
[Linux](https://man7.org/linux/man-pages/man1/cd.1p.html)

Then, navigate to a directory where you can put the project code in using command line/shell

Part 1 - Cloning from a repository, and committing and pushing changes
---------
Once in the directory you want to copy the TeachingGit repo in, type:
	git clone https://github.com/alxqiu/TeachingGit.git
This will copy the files over to your local machine. 

on your local machine, edit hello.py with any text, whether it be comments or code

then, type
    git add hello.py
this will track the changes to hello.py

then:
    git commit -m "where normal descriptions go"

commits require a message, and the above text behind -m tells other people and yourself what your commit does

then type:
    git push origin main
	
this will push the changes to the remote, directly to the main branch


