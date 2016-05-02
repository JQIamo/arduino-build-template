# Arduino build template

To clone as a new project:

`git clone https://github.com/JQIamo/arduino-build-template.git <PROJECT NAME>`

Then, make sure you init submodules and remove the upstream tracking:

`git branch --unset-upstream && git remote rename origin template`
`git submodule update --init --recursive`

Then, develop at will! Push to a new remote repository by:

`git remote add origin <REMOTE URL>`

`git push -u origin master`

etc., etc.

To pull in new changes, do:

`git fetch template` followed by `git merge template/master`
