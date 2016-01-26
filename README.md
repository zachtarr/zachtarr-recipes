# zachtarr-recipes
My first attempt at creating some AutoPkg recipes.

The Plain Clip recipe was created using [Recipe Robot](http://https://github.com/homebysix/recipe-robot)

The FontAgent Pro 6 recipe also installs the companion application Smasher. Uninstalling the package with Munki only removes FontAgent Pro, so I added a post-uninstall script that triggers the Smasher uninstaller.
