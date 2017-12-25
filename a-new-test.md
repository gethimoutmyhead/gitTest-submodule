I'm trying to find out if you can have a git within a git, and not break everything.

The test
- set up a directory
- set up a folder within this directory
- the subfolder should have a git repository for it
- push that subfolder to github
- then we create a second git repository in the parent directory
- push the parent to github
- if it works, both the contents of the parent directory and subfolder should be in the 2nd repository, and i should also be able to modify the subfolder as required



