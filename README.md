--- 
# Scripts to create the default local Joomla! development files and folder skeleton from several git repositories
--- 
```
SET git_username=pierre-pvln
md MY_NEW_EXTENSION
cd MY_NEW_EXTENSION
git clone git@github.com:%git_username%/structure_joomla.git struc
cd struc
_create-it-all.cmd
```
