---
layout: post
author: ted
---

# The Advanced Packaging Tool

The Advanded Packaging Tool is the most recent and commonly used tool for managing software packages in Debian based GNU/Linux distributions.

The Debian project created and uses a software packaging format, contained in `*.deb` files, and package management tool for creating, installing, and otherwise manipulating software that is packaged in that format, the `dpkg` program. The `dpkg` program includes other tools such as `dpkg-deb`, `dpkg-query`, and `dpkg-split` that can be used to perform low leval tasks for management of software in a Debian based GNU/Linux distribution as well as development tools such as `dpkg-source`, `dpkg-buildpackage`, and others that can be used to build, package, and distribute software for those distributions.

The `dpkg` tools function at a low level and are often too complex for most common purposes. In order to simplify common package management tasks, the `dselect` was created.

APT is a software tool used to manage software in many GNU/Linux distributions. It was created by the Debian project, 


# APT Repositories

{% highlight shell linenos %}
$ sudo apt update
$ sudo apt upgrade
{% endhighlight %}