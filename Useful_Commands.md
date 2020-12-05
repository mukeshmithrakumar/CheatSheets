# Conda

| Command        | Description                    |
|----------------|--------------------------------|
| conda info       | Verify conda is installed, check version number |
| conda create --name py35 python=3.5 | Create a new environment named py35, install Python 3.5 |
| conda env remove --name py35 | Delete an environment and everything in it |
| conda env list | Get a list of all my environments |
| conda list | List all packages and versions installed in active environment |
| activate py35 /  source activate py35 | Activate the new environment |
| deactivate / source deactivate| Deactivate the current environment |
| conda install jupyter | Install a new package (Jupyter Notebook) |
| jupyter-notebook | Run an installed package (Jupyter Notebook) |
| conda install --name py35 toolz | Install a new package (toolz) in a different environment |
| conda remove --name py35 toolz boltons | Remove one or more packages |



# GitHub

| Command                                                              | Description                      |
| -------------------------------------------------------------------- | -------------------------------- |
| git config --global user.name "Mukesh Mithrakumar"                   | Setting Global Username |
| git config --global user.email "mukesh.mithrakumar@generalassemb.ly" | Setting Global Email |
| git clone <url>                                                      | Clone a Repo from URL |
| git init                                                             | Creating an empty GIT repository |
| git add .                                                            | Adding all files to Git |
| git add <file1> <file2>                                              | Adds files to Git |
| git add <foldername>                                                 | Add folder to Git |
| git rm <file1> <file2>                                               | Remove File from the Project |
| git commit <file> -m "Message"                                       | Performing Commit with Message |
| git commit -a -m "Message"                                           | Perform Commit to All Tracked Files |
| git push origin master                                               | Update the remote repository |
| git log                                                              | All Git Commits (Reverse Chronological Order) |
| git status                                                           | Show status of files |
