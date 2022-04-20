# Github-Backup-Shell-Script
## Step 1:
### Create `.netrc` file which will include github username and a generated token as shown in the example:
```
machine github.com
login ADD-USERNAME-HERE
password ADD-TOKEN-HERE
```
## Step 2:
### Add the repositories links in ``my.list`` file as shown:
```
https://github.com/......
https://github.com/......
https://github.com/......
```
``You can create more than one list with different name and run all of them together using the command in step 2``
## Step 3:
### Run the script
```
bash github-backup.sh *.list
```
