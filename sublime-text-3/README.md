# Sublime Text 3


## Build and Run C/C++ Program ##
[Build Systems - Sublimetext Docs](https://www.sublimetext.com/docs/3/build_systems.html)

I use MinGW for C/C++. I use two MinGW Distro - *[CodeBlock MinGW](http://www.codeblocks.org/)* and *[Customised MinGW](https://nuwen.net/mingw.html)*. But may be both are same.
I prefer to use original [MinGW](https://mingw-w64.org/doku.php) which was in my [CodeBlock IDE](http://www.codeblocks.org/) installed. You can use any of them.

To set up build system for running C/C++ program in *Sublime Text 3* on Windows 10 operating system :

* Go to: Tools>Build System>New Build System
* Copy the file under github's "User/C++CodeBlockMinGW.sublime-build" and paste it and rename it as you wish without modifing "*.sublime-build" , but you have to set the right path of "path to\\MinGW\\bin\\g++.exe" (in my case "C:\\Program Files (x86)\\CodeBlocks\\MinGW\\bin\\g++.exe") and then save it. You can also use castomised MinGW Distro.
* Then write a C/C++ programe and go to Tools>Build System and select your build system. If you want to work with input output file then you have to create two file *inputf.in* and *outputf.in* in your working directory where the C/C++ file and have to build with " *-file-run".


Link I've visited:
* [Sublime Text for Competitive Programming](http://ketangupta.in/blog/competitive/sublimetext/2016/06/28/sublime-text-competitive-programming/)
* [MinGW Distro - nuwen.net](https://nuwen.net/mingw.html)
* [Sublime-Build-System - Github](https://github.com/shikharkunal99/Sublime-Build-System) -input output file
