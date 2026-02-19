# What is Linux?
To put it simply, Linux is an operating system that is like Microsoft Windows but with more customisabilily and FREEDOM!!!

The current page is my personal noted adapted from [Navigating Files and Directories in Linux](https://arcca.github.io/An-Introduction-to-Linux-with-Command-Line/02-filedir/index.html)
to make it easier for me to remember and follow.

## Webpage Resources
Information on the concepts of Linux can be found on [What is Linux](https://www.linux.com/what-is-linux/) and [Linux is not window](https://linux.oneandoneis2.org/LNW.htm). 
Additionally, forums on Linux can be found [here](https://www.linux.org/forums/getting-started.148/).

## Video Resources
[video](https://www.youtube.com/watch?v=ISJ44S5sZu8) explains the file structure of the linux systems in simple terms and provide a brief explanation of what each file is and their use in the system.

## Simple Starting Commands

```/```
> is the "root directory" or "slash character" , that holds everything (top of the hierarchy).

```pwd```
> "print working directory" which lets you know where you currently are.

```ls```
> Lets us know the contents of our directories. we can add "-F" option (also known as slash/flag) behind to classify the "ls" output.\
Options are case sensitive. Other options includes "h", "r", "l", each denoting a different execution.

```help```,```man ls```
> These are options that displays more information on how to use commands in your environment.

```ls -lh "directory name"```
>  An Example of showing what is in the designated directories; Commands to print all files and directories in current directory and in long list format with human readability.

## Navigating Through Directories

```cd "directory name"```,```cd ..```
> This command lets us go into the directories we want to and By adding ```..``` we then reverse back to the parent directory.

## An example of a small sequence (it can be merged into one seperated by "/".
```
pwd
ls -F
cd Desktop
cd data-shell
cd data
```


