## Git commands

#### Beginner Level

- `git init` : initializes a new git repository. What is a repo? 
it is a folder managed by git where we can track all the changes we are making in the project.

- `git add <filename>` : starts tracking your new changes for the nextr commit

- `git commit -m <message>` : this creates a new version based on your prev changes

- `git push origin master` : pushes the changes to main branch on github repo (master is name of the branch)

- `git cat-file <flag> <hash>` : flag = -t -> tells you about the type of the object
                                 flag = -p -> tells you about the content of the object

- `git checkout -b <name>` : create a new branch of the repo apart from main (master)

- `git checkout master` : switch branches (master is the name of the branch)