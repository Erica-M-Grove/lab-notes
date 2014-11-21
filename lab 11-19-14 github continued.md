#Github, versioning 11-19-14  

##branching - model one
- you decide which versions you want and you journal the process
- two models of working with branching in Github: the first involves using the same remote server
	- equal access version: permissioning for your team: each member gets permission to write into the repository (good for a small team) - the google docs model 
	- for long project you need to branch: at some point in the production of the document (for instance, version 5) create another branch.
		- think about syllabi: 2014 syllabus (branch), but then 2015 syllabus branches off - 2014 is abandoned/done but you can look back at it, 2015 is changing
		- the branches diverge 

##branching - model two  
- two remote servers - each member works with their copy of the remote server, changes are pushed from each local level to each remote and transferred between the remote servers
	- this way, one of the remote servers (R1) is the master branch, you choose whether to accept the changes made in the copy of the remote server (R2) - you get to prevent some of the work you want to keep from being clobbered
	- useful for editing: copy the whole journal/whatever, fix the problem, then they can choose to merge it into the main branch
	- note: only possible in plain text (has to be human understandable so you know what changes are made)