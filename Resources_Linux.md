# What is Linux?
To put it simply, Linux is an operating system that is like Microsoft Windows but with more customisabilily and FREEDOM!!!

The current page is my personal notes adapted/written from my understanding - from multiple websites mentioned here to make it easier for me to remember and follow.

### Webpage Resources
General information on Linux can be found on [What is Linux](https://www.linux.com/what-is-linux/) and [Linux is not window](https://linux.oneandoneis2.org/LNW.htm). 
Additionally, Linux forum can be found [here](https://www.linux.org/forums/getting-started.148/).

More technical free resources can be found on [GeeksforGeeks](https://www.geeksforgeeks.org/linux-unix/linux-tutorial/) or exercises such as [Navigating Files and Directories in Linux](https://arcca.github.io/An-Introduction-to-Linux-with-Command-Line/02-filedir/index.html).

# Some key features about Linux
- The file system sorts its own information on the disk.
- Information is stored in files, which is stored in directories (Folders).
- Directories forms a directory tree 🌳, Like a hierarchy of directories with the top being the root (AKA ```/```).
- The difference between a "relative path" and "absolute path" is the former specifies a location from the current directory and the latter from the root directory.

### Organizing Files
* Before organizing files, there are a few things to keep in mind.
1) The shell organizes in alphabetical (lexicographic) order, so name your files accordingly.

# Simple Starting Commands

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

### Navigating Through Directories

```cd "directory name"```,```cd ..```
> This command lets us go into the directories we want to; by adding ```..``` we then reverse back to the parent (previous) directory.

### An example of a simple sequence (it can be merged into one command seperated by "/".

```
pwd
ls -F
cd Desktop
cd data-shell
cd data

```

### Short cuts 

```~```
> This is shortcut for the current user's home directory.

```cd ..```, ```cd -```
> The former is mentioned above, and the latter, instead of taking you to the previous directories you were in.

```Tab```
> lets your computer fill out the directories name after you initiate the first few letters/numbers.

```⬆️ ⬇️ ```
> Lets you cycle through the commands you previously used.

# Conclusion

The following is my understanding of utlizing simple bash comments to navigate through directories/folders. Additionally, this page also serves as notes and resources for me incase I need a place to refer back to.

