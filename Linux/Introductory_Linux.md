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

`/` Is the root directory that contains everything at the top of the filesystem hierarchy.

`pwd` Stands for "prints working directory" that lets you know where you currently are.

`ls` Lets you know the contents of your directories. `-F` can be added to classify the ls output.\
Other options includes `h`, `r`, `l`, each denoting a different execution; options are case sensitive.

`help`,`man ls` are options that provides more information on how to use commands in your bash.

`ls -lh "directory name"` is an command prompt that shows  what is in the designated directory; along with "long list" and "human redability" options.

### Navigating Through Directories

`cd "directory name"`,`cd ..` leads us into the directories we want to, and by adding `..`,  we can reverse back to the parent directory.

### An example of a simple sequence (it can be merged into one command seperated by "/".

```bash
pwd
ls -F
cd Desktop
cd data-shell
cd data
```

### Short cuts 

`~` This stands for the current user's home directory.

`cd ..`, `cd -` The former is mentioned above; the latter takes you to the previous directory you were in.


`Tab` Lets your computer autofill in the rest of your directories name.

⬆️ ⬇️
> Lets you cycle through the commands you previously used.

# 📕 Conclusion
The following is my understanding of utlizing simple bash comments to navigate through directories/folders. Additionally, this page also serves as notes and resources for me incase I need a place to refer back to.

