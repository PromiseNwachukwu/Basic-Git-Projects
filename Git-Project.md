# Basic Git Project
#### This project will cover initializing a Repository and Making Commits, Working with Branches, Collaboration and Remote Repositories, and Tagging track changes, highlighting the significance of Git in modern software development workflows.

## Initializing a Repository and Making Commits.
### Initializing a Git Repository.
    • Open a terminal on your computer.
    • Creating a working directory named DevOps folder using this command mkdir DevOps.
    • Move into the working directory using this command cd DevOps.
    • While inside the directory, run git init command.
![Screenshot from 2023-10-06 22-25-04](https://github.com/PromiseNwachukwu/Basic-Git-Projects/assets/109115304/9d4e9086-bbac-43dd-998f-a0cf46acbb6e)

### Making your first Commit
    • Inside the working directory create a file index.txt using this command touch index.txt
    • Writing and saving sentence of choice inside the text file with sudo vi index.txt.
    • Add your changes to git staging area using this command git add .
    • To commit your changes to git, run the command git commit -m "initial commit"
![Screenshot from 2023-10-06 22-52-47](https://github.com/PromiseNwachukwu/Basic-Git-Projects/assets/109115304/bf2d8e1f-fa18-4916-8826-d373e22437ac)

## Working with Branches
### Making a GIT branch
    • Make a new branch by running this command git checkout -b main.
    • Listing the branches on your local git repository; git branch.
    • To change into an exiting or old branch; git checkout master
    • To merge a branch into another branch;  git merge master
![Screenshot from 2023-10-06 23-19-49](https://github.com/PromiseNwachukwu/Basic-Git-Projects/assets/109115304/935b7f2a-dce7-4aef-aafd-2eacf84562ac)

### Deleting a git branch.
    • To delete a GIT branch; git branch -d <branch_name>
![Screenshot from 2023-10-06 23-38-41](https://github.com/PromiseNwachukwu/Basic-Git-Projects/assets/109115304/550a3fe8-005a-4bb2-92e7-d6feaa82f52e)

## Collaboration and Remote Repositories
### Creating a github account and a git repository.
    • Create a github account.
    • Create a git repository named Basic-Git-Project.
![Screenshot from 2023-10-07 00-03-51](https://github.com/PromiseNwachukwu/Basic-Git-Projects/assets/109115304/d79764f8-758b-4382-a6a6-82d573c39a32)

### Pushing your Local git Repository to your Remote github Repository.
    • Adding the remote repository to the local repository.
        git remote add origin https://github.com/PromiseNwachukwu/Basic-Git-Project.git
    • After commiting the changes in your local repo. To push the content to the remote repository.
        git push origin main
