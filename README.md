# ANNOTATIONS ABOUT GIT

## Config global parameters (do not use --global option if not necessary)
You can override the global configuration located in /etc/gitconfig.

Config username:

`$ git config --global(do not use if not global) user.name "pepito"`

Setup user email:

`$ git config --global user.email "pepito@gmail.com"`

To get help from command line:

`$ git help config`

Config the default text editor:

`# git config --global core.exitor vim`

To check your settings

`# git config --list`

## Store credentials 
To caching credentials:

`$ git config credential.heler store`

Setup up caching expire credentials (by default 15 minutes):

`$ git config --global credential.helper "cache --timeout=3600"`


## Avoid SSL issues

`GIT_SSL_NO_VERIFY=true git clone https://...`

Go to the repository folder and execute:

`git config http.sslVerify false`


## CLONING REMOTE REPO
To cloning a remote repository in local

`# git clone https://server`

Check the status of your files:

`# git status`

Tracking new files:

`# git add README`

 
