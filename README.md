# Linux Cheatsheet

## Basic Linux Commands

**Q1. How to read linux documentation in terminal for any command?**
```bash
    man <command>
```
For example: 

```bash
    man man         
    # man: manual reference system
```

**Q2. How to `run as administrator` in linux?**
```bash
    sudo <command>
```

For example: 

```bash
    sudo su
    # lets you run as administator in linux terminal.
```

**Q3. How to clean you terminal?**
```bash
    clear
```

**Q4. How to display the current working directory?**
```bash
    pwd
```

**Q5. How to list all files & directories in the current directory?**
```bash
    ls
```

**Q6. How to change directories?**
```bash
    cd
```

For example: 

```bash
    cd ../
    # this will take you to the parent directory of the current directory.
```


**Q7. How to create a directory in linux?**
```bash
    mkdir <directory-name>
```

For example: 

```bash
    mkdir notes
    # this will create a directory named "notes".
```

**Q8. How to delete a directory in linux?**
```bash
    rmdir <directory-name>
```

For example: 

```bash
    rmdir notes
    # this will delete a directory named "notes".
```

**Q9. How to create a file?**
```bash
    touch <file-name-with-extension>
```
For example: 

```bash
    touch index.html
    # this will create a file named index.html.
```

**Q10. How to remove a file?**
```bash
    rm <file-name>
```

**Q11. How can we find files on our Linux system?**
```bash
    locate <file-name>
```

**Q12. How to move a file or directory?**
```bash
    mv <current-location> <destination-location>
```
For example: 
```bash
    mv Downloads/notes Documents/notes
    # this will move the notes to documents from downloads.
```

**Q13. How to print `Hello World` in terminal?**
```bash
    echo "Hello world"
```

**Q14. How to read a file?**
```bash
    cat <file-name>
```

**Q15. How to display the history of commands?**
```bash
    history
```

**Q16. Need to change your password?**
```bash
    passwd
```

**Q16. How to display the details of a file (*like permissions*)?**
```bash
    ls -al
    # show the details of all file including hidden.
```

**Q16. To close a ongoing process in terminal?**

Press `ctrl / cmd + C ` to cancel a ongoing process you wish to stop.

**Q16. How to display the details of a file (*like permissions*)?**
```bash
    ls -al
    # show the details of all file including hidden.
```

## Managing your Linux (ubuntu 20.04)

**Q17. How to update your packages?**
```bash
    sudo apt-get update
```

**Q18. How to install packages?**
There are multiple ways of doing it, most preferred are
- Using package managers (like apt, yum)
```bash
    sudo apt install <package-name>
```

- Snaps are app packages for desktop, cloud and IoT that are easy to install, secure, cross‐platform and dependency‐free.
```bash
    sudo snap install <package-name>
```

**Q19. How to uninstall packages using apt package manager?**

```bash
    sudo apt remove <package-name>
```

**Q20. How to list the installed packages?**

```bash
    sudo apt list --installed
```

## Linux Filesystem

Few of the directories explained:

- `/bin`: short for binary, the bin folder is where our binaries that your system needs, executables and tools will mostly be found here.

- `/boot`: contains the files your system needs to boot up. How to boot up, and what drive to boot from.

- `/dev`: you can find device information here, this is where you will find pointers to your disk drives sda will be your main OS disk.

- `/etc`: Likely the most important folder on your Linux system, this is where the majority of your configuration files.

- `/home`: This is where you will find your user folders and files. We have our user folder.

- `/lib`: We mentioned that `/bin` is where our binaries and executables live, `/lib` is where you will find the shared libraries for those.

- `/media`: This is where we will find removable devices.

- `/home`: This is where you will find your user folders and files. We have our user folder.

