#Space Conquest

#### Git Commands

This is a table of basic git commands:

| Git Task                          | Notes                                                                                 | Git Commands                                                                                     |
|-----------------------------------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Tell git who you are              | Configure the author name and email address to be used with your commits.             | ``` git config --global user.name "Sam Smith" git config --global user.email sam@example.com ``` |
| Create new repository             |                                                                                       | ``` git init ```                                                                                 |
| Check out a repository            | Create a working copy of a local repository                                           | ``` git clone /path/to/repo```                                                                   |
|                                   | Create a working repository from a remote server                                      | ``` git clone user@github.com:/path/to/repo/ ```                                                 |
| Add Files                         | adding files  to repo                                                                 | ``` git add . ``` for all files ``` git add <filename> ``` for particular file                   |
| Commit files                      | commit changes to head                                                                | ``` git commit -m "commit message" ```                                                           |
| Push files                        | push the files to git                                                                 | ``` git push origin <branchname> ```                                                             |
| Status                            | List the files you've changed and those you still need to add or commit               | ``` git status ```                                                                               |
| Branches                          | Create a new branch and switch to it                                                  | ``` git checkout -b "branchname" ```                                                             |
|                                   | List all the branches in your repo, and also tell you what branch you're currently in | ``` git branch ```                                                                               |
| Update from the remote repository | Fetch and merge changes on the remote server to your working directory                | ``` git pull ```                                                                                 |
|                                   | To merge a different branch into your active branch                                   | ``` git merge <branchname> ```                                                                   |
| Search                            | Search git repository for "foo()"                                                     | ``` git grep "foo()" ```                                                                         |


#### Git flow

For a new branch, this should be the workflow: 
``` git checkout -b "branchname" ```
```javascript
/* make changes to files */
```
```
git status
git add .  OR git add <filename>
git commit -m "commit comment"
git push origin <branchname>
```
