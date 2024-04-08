# Readme

This is a project, that provides an example of the usage of github and bash.

## Requirements

- First, install  [git](https://git-scm.com/downloads) for your operating system. After the installation there is a new program called **Git Bash** available on your Windows machine. This is a basics command line interface, that works like a unix shell. If You are working on Linux or Mac, Your terminal is already a unix shell. You still have to install git.
- Second, install Python on Your operating system. You can check which version on Python is installed yet by typing  ```Python -V``` in Your command line. If no Python is installed, install Python 3.11 via the Windows Store (preferred) or the Python [website](https://www.python.org/).

## Usage

- Clone the [git repository](https://github.com/jhumci/test_git_shell) on Your machine
    - in git bash, navigate to the folder You want to download the repository to
    - enter ```git clone https://github.com/jhumci/test_git_shell.git```
    - now, You have a copy of the repository on Your machine
    - use the windows explorer to make sure that this worked
    - alternatively use VS Code `File/Open new window` and select `Clone git repository`

## Tasks

- Make sure to use a git bash and not a power shell
- Create a virtual environment using `python-m venv new_env`
- activate the virtual environment using `source new_env/bin/activate` 
- 🤓 create Your own branch using ```git branch <your_branch_name>```
- execute the file ```hello_world.py``` by entering ```python hello_world.py```. Make sure, that You are in the right directory or enter the relative file path 
- Create the file ```primes.txt``` in the subfolder data
    - navigate to the data subfolder ```cd data```
    - create a new file ```touch primes.txt```
- Try running the Python-Skript ```make_primes.py```
- Fix the problems within the Python code using the nano editor or any other text editor on Your PC
    - You can open the editor using ```nano make_primes.py```
    - use nano the to edit the file
    - the `^` indicates the `Ctrl` (`Strg`) key on Your keyboard 
    - replace `x` and `y` ```for n in range (x,y):``` by a reasonable range You want to find the prime number in
- Try running the Python-Skript ```make_primes.py``` again
- Check Your results in 
Show the results in ```primes.txt``` using nano
- make a new directory `data/results` and copy Your results ```primes.txt``` into the directory
    - `cp <from_path> <to_path>`
- change the file to read only for all users
    - `chmod a-w primes.txt`
    - use `ls -l` to check whether it worked
- Store your environment in a file `pip freeze > requirements.txt`
- 🤓 commit the changes to Your branch using ```git commit -m <your_commit_comment>```
