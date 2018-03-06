# vim-centos-package

This is a project for building Nightly Vim centos rpm package sources from (<a href="https://github.com/vim/vim">Vim</a>).

Please make sure you have choose the right version
el6 is build for centos 6 and 
el7 is build for centos 7

use <b>rpm -ivh <packagename></b> to install the package

In centos 7, the system will show an error message when install the package like:

<i>file /usr/bin from install of vim-8.0.1573-el7.x86_64 conflicts with file from package filesystem-3.2-21.el7.x86_64</i>

so you can use the command below to install the package

<b>rpm -ivh vim-8.0.1573-el7.x86_64.rpm --force</b>

