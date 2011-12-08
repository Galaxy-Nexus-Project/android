Galaxy Nexus Project
========================

Getting Started
---------------

To install, initialize and configure Rep, follow these steps:

* Make sure have a bin/ directory in your home directory and that it is included in your path:
    $ mkdir ~/bin
    $ PATH=~/bin:$PATH

* Download the Repo script and ensure it is executable
    $ curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo
    $ chmod a+x ~/bin/repo

* Create an empty directory to hold your working files.  If you're using MacOS, this has to be on a case-sensitive filesystem.  Give it any name you like:
    $ repo init -u git://github.com/Galaxy-Nexus-Project/android.git

* Get the files
    $ repo sync
