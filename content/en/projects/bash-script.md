---
date: 2022-04-26T22:02:30-04:00
descritption:
title: "Bash-Script"
draft: true
---

This script generates a set a boiler plate code and files to structure out a new project. The if statement at the top acts as a safety net by only allowing the shell script to run if the project has a name. (i.e sh shell.sh project name) the mkdir command creates a new directory. bash-script is the main directory so all the other files are located in bash-script. the cd command is allowing us to navigate through and create new files and directories within bash-script. The touch command creates the code file which allows us to use the echo command to communicate the code that we want in the code file. Because there are multiple code files, which file the code is to be sent is signified by double brackets and the file name. It is important to make sure the code matches up with it's file or else it won't run the code.

{{< figure src ="/images/bash.png">}}

[Gist Link](https://gist.github.com/dwellings16/ad6dfc9c08df84f04c0bc1d2ed0cc7a4)
