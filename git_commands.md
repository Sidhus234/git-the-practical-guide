<ol>
<li><i>git status</i>: Provides status of the git repository.</li>
<li><i>git init</i>: Converts the current folder to git repository.</li>
<li><i>git add {filename}</i>: Will add the {filename} to the staging area.</li>
<li><i>git add .</i>: Will add all files which were modified or created to the staging area.</li>
<li><i>git commit -m "{message}"</i>: Commits the added files to the repository. Git will tracking these changes against your email and username</li>
<li><i>git config --global user.email "{email id}"</i>: Congifure email id of the current user.</li>
<li><i>git config --global user.name "{username}"</i>: Configures username of the current user.</li>
<li><i>git log</i>: Provides log of the repo. Press 'q' and 'Enter' key to exit it.</li>
<li><i>git checkout {commit id}</i>: Will provide the repo as of before that commit.</li>
<li><i>git checkout {branch}</i>: Will bring back to the end of that branch.</li>
<li><i>git branch</i>: Lists out all the branches.</li>
<li><i>git branch {name of new branch}</i>: Creates a new branch.</li>
<li><i>git checkout {branch}</i>: Switches to the branch.</li>
<li><i>git checkout -b {branchname}</i>: Creates a new branch {branchname} and moves to the head of the new branch.</li>
<li><i>git merge {branchname}</i>: We must be present in branch in which we want to merge changes for this to work. This will merge changes from {branchname} to current branch.</li>
<li><i>git switch {branchname}</i>: Switch is used explicitly for working with branches. Checkout command works with branches and commits as well. Switches to {branchname}.</li>
<li><i>git switch -c {branchname}</i>: Creates a new branch with {branchname}.</li>
<li><i>git ls-files</i>: Gives list of files in the repo.</li>
<li><i>git rm {filename}</i>: Removes the file. Commit the change after this command.</li>
<li><i>git checkout {filename or .} </i>: Gets rid of uncommited changes in the current branch.</li>
<li><i>git restore {filename or .}</i>: Gets rid of all the uncommited changes in the file or current branch.</li>
<li><i>git clean -dn</i>: Will list out all the files that would be deleted (Which are not commited).</li>
<li><i>git clean -df</i>: Will delete the files. Always first run "git clean -dn" to know which files will be deleted.</li>
<li><i>git reset {filename}</i>: Will move the latest commited data of {filename} to staged area. "git checkout {filename}" will delete those changes. </li>
<li><i>git restore --staged {filename}</i>: Will remove the last staged changes in the {filename}.</li>
<li><i></i>: </li>
<li><i></i>: </li>
<li><i></i>: </li>
<li><i></i>: </li>
<li><i></i>: </li>
<li><i></i>: </li>
</ol>