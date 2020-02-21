THIS IS MY FIRST README FILE TO WORK WITH GIT IN THE TERMINAL

/1. LOCATE THE FOLDER I WANT TO PUT MY NEW GIT REPOSITORY ENTER:
$ cd Desktop/FOLDER_NAME

/2. INITIALIZE GIT: AND PLACE IT UNDER GIT, ENTER: 
$ touch README.md    # To create a README file for the repository$
  git init           # Initiates an empty git repository

  /3. Add files to the Staging Area for commit:
Now to add the files to the git repository for commit:

$ git add .  # Adds all the files in the local repository and stages them for commit

OR if you want to add a specific file

$ git add README.md # To add a specific file

Before we commit let’s see what files are staged:

$ git status # Lists all new or modified files to be committed