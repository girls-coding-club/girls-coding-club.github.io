How to Contribute to Girl's Coding Club Repository
==================================================

**1. Make sure Git is installed on your computer**
You need to first make sure you have git installed. A quick way to check is open a new terminal/command prompt (Mac/Linux: search for terminal / Windows: search for command prompt in your apps) and type

	git

If you receive a list of options you are good to go. If not [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


**2. Fork the Girls Club repository**
Forking the repository(repo) means you are creating a copy under your own account. Any changes made with your copy will not directly affect the repo.

![fork repo image][fork]
[fork]: contribute_assets/fork.png

**3. Get Clone Link**

![fork repo image][clone]
[clone]: contribute_assets/clone.png

**4. Clone Repo on Your System** Open a new Terminal window. Enter the following command:
 
    git clone https://github.com/girls....
*This will clone the girl's club repo into a directory on your system*

## Committing Your Changes

**1. Add Files**

	git add --a 

or
	
	git add {specific file}

**2. Commit Changes**

	git commit -m 'Add your message here'
or
	
	git commit
*This will open an editor screen where you can add your commit message*

**3. Push Your Commits**

	git push

If this is your first time pushing, you may get this error:

	fatal: The current branch logo has no upstream branch. To push the current branch and set the remote as upstream...

just type the suggested command:

    git push --set-upstream origin {your branch name}

## Create a Pull Request
A pull request should only be made once you are finish with your changes and ready to request your changes to be merged with the Girl's Coding Club repo. For example, if you know you will create more changes and commits, wait to make the pull request.
-Add comments explaining your changes

![pull request][pr]
[pr]: contribute_assets/pullrequest.png

 
#Ending Notes

If you are unfamiliar with some of the terms used (i.e. push, pull request, merge, etc) or you are not very familiar with git/github, please check out the links below as they offer a great reference to pick up the basics of Git. You can also ask any questions on our slack channel.

[Github Help][]

[Github Help]: https://help.github.com/

[try.Github.io](https://try.github.io/levels/1/challenges/1)