### Git and Github

* Directory $\rightarrow$  folder
* Terminal or Command Line $\rightarrow$ Interface for Text Commands
* CLI $\rightarrow$ Command Line Interface
* cd $\rightarrow$ change directory
* pwd $\rightarrow$ print working directory
* Repository $\rightarrow$ Project, or the folder/place where your project is kept



### Git Command

- Clone: Bring a repo that is hosted somewhere like Github into a folder on your local machine
- Add: Track your files and changes in Git
- Commit: Save your files in Git
- Push: Upload Git commits to a remote repo, like Github
- Pull: Download changes from remote repo to your local machine, the opposite of push

```
git status	# check status

git add .	# track all files

git add (a specific file)	# track one specific file

git commit -m "_message_" -m "_some description_"	# must have a message, telling what changes have made
```



### Git Push

```
git push 'remote_name' 'branch_name'

git push -u origin master # push the code in your local repository to Github
```