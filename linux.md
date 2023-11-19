# Linux Commands

Basic Linux commands that you will commonly use:

---

## mkdir
Creates a new directory (aka folder) in your current working directory

- To create a new directory:
```
$ mkdir {insert the name of your new directory}
```

## rmdir
Deletes an empty directory

- To delete a directory:
```
$ rmdir {insert name of directory}
```

- If you want to remove a directory that has contents inside, use this command:
```
$ rm -r {insert name of the directory}
```

## cd
Changes your current working directory

- To change directory:
```
$ cd {insert the name of the directory}
```

- To navigate backwards, use '..':
```
$ cd ..
```
- To navigate through multiple directories, use '/':
```
$ cd {insert name}/{insert name}/{insert name}
```

## ls
Lists all of the files and directories in your current working directory

- To list all files and directories:
```
$ ls
```

## g++
Used to compile a single or multiple set of cpp files

- To create an executable file called "a.out":
```
$ g++ {insert name(s) of cpp file(s) you want to compile}
```

- To run the executable file:
```
$ ./a.out
```

- To have a custom executable name:
```
$ g++ -o {insert executable name} {insert cpp files(s)}
```

### For Linprog
Linprog runs a C++ compiler in version 11. Because of this, if you were to create an executable outside of Linprog and try to run it in Linprog,
you might get an error. To compensate for this, we can compile our C++ file(s) in version 11.

- To compile in C++ version 11:
```
$ g++ -std=c++11 {insert name(s) of cpp file(s)}
```

## Final g++ Command
We can combine all of this information into one singular g++ command. You'll probably use this command hundreds of times.

```
$ g++ -std=c++11 -o {insert custom name of executable} {insert cpp file(s)}
```
