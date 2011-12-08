Galaxy Nexus Project
========================

Getting Started
---------------

To install, initialize and configure Rep, follow these steps:

* Make sure have a bin/ directory in your home directory and that it is included in your path:
<pre><code>$ mkdir ~/bin
$ PATH=~/bin:$PATH
</code></pre>

* Download the Repo script and ensure it is executable
<pre><code>$ curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
</code></pre>

* Create an empty directory to hold your working files.  If you're using MacOS, this has to be on a case-sensitive filesystem.  Give it any name you like:
<pre><code>$ repo init -u git://github.com/Galaxy-Nexus-Project/android.git</code></pre>

* Get the files
<pre><code>$ repo sync</code></pre>
