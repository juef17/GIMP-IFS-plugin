# GIMP-IFS-plugin
Iterated Function System (IFS) plugin for GIMP, helping create fractal-like images from your images

This plugin processes images through an IFS. Example:

This:

![Original](https://i.imgur.com/uzk9fHQ.png)

can become this:

![Processed](https://i.imgur.com/SEFOpMn.png)

It has a few predefined IFSs, and a couple of simple features, including some bugs! But hey, it can do things.

To compile under Linux, just run `gimptool-2.0 --build IFS.c`.  

To compile under Windows, please follow this guide and replace a plugin's source code with this one's: http://www.gimpusers.com/system/attachments/1040/original/instr-windows-msys2.txt?1541099274. Unfortunately, it's broken at the moment as some functions have been deprecated since I initially wrote this in 2010, which is also a time when I had little programming experience, so please forgive the coding style / mistakes / unoptimized stuff / etc.

I would gladly welcome pull requests towards improving this plugin!

Thanks for reading!
