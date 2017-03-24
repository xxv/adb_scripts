Handy adb shell scripts
=======================

This contains a few handy shell scripts to make Android app development easier,
especially if you're testing on a bunch of different devices with a bunch of
different apps/build variants.

adb_grep_packages
-----------------

Search the list of installed packages for a given regular expression.

adb_start_app
-------------

Start the default launcher activity of a given package.

adb_uninstall
-------------

Uninstall all the packages (e.g. testing packages) matching a given regular
expression.

adb_app_login
-------------

CLI tool to make it easier to type login credentials into an app on a connected
device. May need to be modified for your specific login form.

Thanks to Joe Mahon for his contributions to the scripts.
