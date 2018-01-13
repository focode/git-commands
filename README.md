#Before git pull , do git fetch
git fetch                      - Load changes from remote server
git diff master origin/master  - Show differences
git merge origin/master        - Merge remote changes with local changes

To pull tagged version from master
git checkout <tagname>

To delete remote branch:
git push origin --delete <remote_branch_name>
To create feature branch from existing branch :  
	1. git checkout -b <to_branch> <from_branch>
	2. Move to new branch : git checkout <new_branch_name>
	3. Commit code and create the same branch in remote : git push origin <name_of_new_branch>
