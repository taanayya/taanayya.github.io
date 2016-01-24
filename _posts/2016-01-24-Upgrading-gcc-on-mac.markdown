---
layout: post
title:  "Upgrading gcc on mac"
date:   2016-01-24 22:12:44 -0800
categories: status post
---

This post contains easiest way of upgrading gcc to latest on apple computer. I have a apple laptop which is given to me
by my employer. It comes with a very old version of gcc (4.2). It does not suppport latest and greatest of c++. I
realised this when I wanted to try some code but it did not compiled.

So here are the bare minimum step you would like to do if you are in same situation as I was.

Check if you mac port installed? If it is not there, install it from [here](http://www.macports.org/install.php).
It will be also great if if you do self update post installation.You may need to update the PATH variable, it goes to
/opt/local/bin.


Next step is to run gcc5 installer. If you have some specific version in mind this is the command you need to
change.Check [Macport](https://www.macports.org/ports.php) or [gcc](https://gcc.gnu.org/) to check which version to
settle on.

When this is done.. you need to update port selection to select newly installed port.

And last step is to update enviornment variables if needed. You are done!!

Here are commands, all the best

{% highlight bash %}
sudo port -v selfupdate
export PATH=/opt/local/bin:/opt/local/sbin:$PATH
export MANPATH=/opt/local/share/man:$MANPATH
sudo port install gcc5
sudo port select gcc mp-gcc5
hash gcc
{%endhighlight%}

for questions/correction email me vikrant.subscribe at gmail.
