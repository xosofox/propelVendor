Propel Vendor Clone
===================

https://github.com/Xosofox/propelVendor is a compilation of the different dependencies that are currently only available via svn.
It consitst of copies of the 1.5 and 1.6 propel versions from the official SVN repos as well as phing 2.3.3, commited into branches

The intention of these repos is to use them as a git submodule in your project, so you do not need svn.


To use the sfPropel15Plugin only with code cloned from github, follow these steps
(modification to the documentation by fzaninotto)

    > cd plugins/
    > git clone git://github.com/fzaninotto/sfPropel15Plugin.git
    > cd sfPropel15Plugin/
    > git checkout -b 1.6 remotes/origin/1.6
    > cd lib/
    > git clone git://github.com/Xosofox/propelVendor vendor
    > cd vendor/
    > git checkout -b 1.6 remotes/origin/1.6
    > cd ../../..


