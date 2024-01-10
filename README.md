## Git Super Basic

- version control system (tracking files versions)

## Getting Started (with https://jupyter.inspire.hk)

1. create an account on https://github.com
1. create a new repository (repo), "notebooks"
1. launch https://jupyter.inspire.hk, login with your github account
1. in JupyterLab, launch Terminal (change language: Setting - Language)

```
 $ cd ~
 $ ln -s /home/public ~/public # link /home/public to your home directory

 $ ls -laR ~/public/  # list a directory
 $ cp -r /home/public/basic .  # copy the directory 'basic'

```

## Make Change & Push (upload to github.com)

```
 $ mkdir notebooks
 $ cd notebooks
 $ git init .  # initialize local repo

 $ cp ~/public/some-file.ipynb .
 # open the file and make change

 $ git add .
 $ git commit -m "initial version" # commit (save) the change
 $ git push origin main # upload to github.com
```

## At own computer

1. install Python (interpreter) from https://www.python.org/downloads/
1. install Microsoft VS Code form https://code.visualstudio.com/download
1. launch VS Code & install extensions: Python, Jupyter
1. open terminal (press ctrl + `)

```
 $ cd ~
 $ git clone https://github.com/[your-account]/notebooks # clone from github.com
 $ cd ~/notebooks
```
