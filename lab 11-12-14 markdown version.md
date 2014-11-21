##git and github 11-12-14
 - versioning
	 - various models to control versioning
	 - single copy model, google doc model
	 - git
		 - keeping a journal while going about your business on your computer (ledger of what you've done)
		 - git is that journal
		 - file system
			 - project folder (/home/usr/name/project1/) - you're always in some folder
			 - view what's in the folder as a continuum
			 - everytime you do something, you have a sequential number of changes
			 - as you change file under file system (with versions), you lose the history

		- to solve that problem, you get the git/journal layer and the staging layer
			- stage layer: you've done a bunch of stuff in the folder, lots of versions, you take some of the changes (v1 and v4) and combine them to make v1 in the stage layer. then you commit it to the journal/git layer (v1 is where I did x).
				- stage is temporary way to package changes
			- this model forces you to journal. work as you work before, but creating official (but arbitrary) restore points/versions constantly. 
			- also keeping track of labor
- using git
	- git init creates a .git directory (sets up the structure with staging and journaling. this step is on the fs layer)
	- to package certain changes you git add files (on the staging layer)
	- git commit - commits to the journal layer
	- git stuff (each of the layers) is local

- remote server
	- contains copy of your journal
	- git push - synchronizes with remote server, puts copy of your journal in the cloud
	- this remote host is github (or you can host one yourself, but this version is free)
	- another person can synch from the remote server
	- remote server offers a single timeline, we can see what each person is doing to the file on the remote server at each time, see the changes that are being made by others
		- no multiplicity of copies

	- git pull: pull what's happening from the remote server back to my local server

- putting git into practice
	- git status: do this after everything. you're asking what's happening in this folder right now.
	- git commit -m "put your journal stuff here"
	- when you feel like you're at a good point and what to save the changes then stage it at that time (git add)
	- rm -rf
	- git checkout test2.txt: rolls back whatever happened (nothing modified)
	- need to use plaintext files (git compares line by line, so must be in plaintext)
	- git init, git add, git commit, git push: the basic order of steps (with git status thrown in)
	- lab notes due in github repository of choosing
	- use tutorial to go through it, practice github 