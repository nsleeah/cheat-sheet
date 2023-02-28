# Terminal and Git Cheatsheet.

## Terminal Commands.

|Command|Function|
|-------|--------|
|pwd|Shows what the working (current) directory is used at the moment.|
|ls|Lists files.|
|ls -l|List of files and folders along with permissions, owner and date last modified.|
|ls -al|A list of files and folders including hidden files.|
|cd ~ |Shortcut for the home directory of user.|
|cd|Allows to move between different directories.|
|**Creating Files and Folders**|
|mkdir|Creates a directory.|
|touch|Creates new file.|
|**Opening Files**|
|open|Opens files in a text editor. |
|**Manipulating Files and Folders**|
|mv|Moves a file.|
|cp|Copies a file.|
|cp-r|Copies an entire directory.|
|**Deleting Files and Folders**|
|rm|Deletes file.|
|rm -r|Deletes directory.|


## Git Commands.

|Command|Function|
|-------|--------|
|git init|Short for initialise, sets up Git in this directory.|
|git add |Adds a change in the working directory to the staging area.|
|git status |Displays the state of the working directory and the staging area.|
|git commit -m ""|A snapshot of your Git repository at one point in time.|
|git remote add origin| Adds a new remote repository to a local git project.|
|git push -u origin main|Pushes the local branch named "main" to the remote repository named "origin" and also set the local branch to track the remote branch.|
|git branch |Checks what branch were on|
|git branch [branch name]|Creates new branch|
|q|Exit mode|
|git merge main | Merges |
|git checkout [branch name] |Changes branch we are on to branch name|
|gco main|shortcut|
|git branch -d [branch name]|Deletes branch|
|pkill java |-|
|gsa|git status shortcut|
|git checkout -b|create a new branch and switch to it in a single step.|

## Node Commands
[Node Package Management](https://www.npmjs.com/)
|Command|Function|
|-------|--------|
|npm init|Used to set up a new or existing npm package|
|npm init -y| The -y flag when passed to npm commands tells the generator to use the defaults instead of asking questions.|
|npm install [name]|npm install downloads a package and it's dependencies|
|npm i|Shortcut for npm install|
|npm install -D [name]|Tells npm to add the package to the project's devDependencies|
|rm -ref node_modules| Removes node modules, use npm i to return them|
|npm tests|Run the test command|
|npm run test:coverage||
Note always remove node modules when uploading to Github.

