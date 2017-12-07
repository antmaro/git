# ANNOTATIONS ABOUT GIT

## Config global parameters (do not use --global option if not necessary)
Config username
`$ git config --global(do not use if not global) user.name "pepito"`

Setup user email:
`$ git config --global user.email "pepito@gmail.com"`

To get help from command line 
`$ git help config`

## Store credentials 
For caching credentials
`$ git config credential.heler store`

Setup up caching expire credentials (by default 15 minutes)
`$ git config --global credential.helper "cache --timeout=3600"`
