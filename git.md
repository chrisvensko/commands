# Git Commands

**reflog** - View history of local git pointer

This is an easy way to "jump" back to a given point in time.

	Usage:
		git reflog
	
	Results:
		b59b047 HEAD@{0}: commit: TMP
		257a741 HEAD@{1}: checkout: moving from master to tmp
		257a741 HEAD@{2}: clone: from git@github.com:chrisvensko/commands.git

**log --graph --oneline** - Visual display of git commits

Quick way to see visual commit history.

	Usage:
		git log --graph --oneline
	
	Results:
		*   017758c Merge branch 'tmp'
		|\  
		| * cb98a12 WIP: --graph --oneline
		| * b59b047 TMP
		|/  
		* 257a741 Delete LICENSE
		* d9ff29e Initial commit