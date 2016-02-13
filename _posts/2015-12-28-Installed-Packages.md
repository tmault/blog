---
title: How to list installed packages on Raspbian
---

I’ve spent today messing around with a Raspberry Pi. One typical problem that I have is remembering which packages I have installed to make things happen. 

Run the below in a terminal session and your machine will output a list of installed packages to a text file named installed-packages.txt in your home directory.

{% highlight shell-session %}
dpkg —get-selections > installed-packages.txt
{% endhighlight %}