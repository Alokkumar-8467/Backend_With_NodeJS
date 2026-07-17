# 1. Introduction to Terminal and Shell

# 2. Basic Shell Commands (echo, pwd, whoami) 

ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal
$ echo

// echo same as console.log()

### Print anyThing in Bash user "echo"
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal
$ echo kola
kola
```


### Declare Variable in Bash
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal
$ num=12
```

```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal
$ echo $num
12
```

<!-- We can use .sh file so some task which take more than one line. -->

```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ ./test.sh
10
End
```


### To Check Current Directory use "pwd"
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ pwd
/d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
```

### To Know Current user "whoami"
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ whoami
ALOK
```


# 3. Navigating the File System(cd)
#### We navigate in D drive so we reached up to ```/d``` means root directory
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
· $ cd .. /

ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal
.$ cd .. /

ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS
.$ cd .. /

ALOK@DESKTOP-D41A0U8 MINGW64 /d
. $ cd .. /
```

Now see ```/``` is our root directory

#### But in this we navigate in ```/c``` directory that why we get ```~``` means Home Directory and ```/``` means Root Directory. 

```
ALOK@DESKTOP-D41A0U8 MINGW64 ~
$ git -v
git version 2.54.0.windows.1

ALOK@DESKTOP-D41A0U8 MINGW64 ~
$ cd ../

ALOK@DESKTOP-D41A0U8 MINGW64 /c/Users
$ cd ../

ALOK@DESKTOP-D41A0U8 MINGW64 /c
$ cd ../

ALOK@DESKTOP-D41A0U8 MINGW64 /
$ cd ../

ALOK@DESKTOP-D41A0U8 MINGW64 /
$

```

# 4. Listing Directory Contents(ls)

```
ALOK@DESKTOP-D41A0U8 MINGW64 /
$ ls
bin/  etc/           LICENSE.txt  ReleaseNotes.html  unins001.exe*
cmd/  git-bash.exe*  mingw64/     tmp/               unins001.msg
dev/  git-cmd.exe*   proc/        unins001.dat       usr/

ALOK@DESKTOP-D41A0U8 MINGW64 /
$ 
```

#### Symbolic link appear when we type ls command in bash terminal represented by (@).
We Learn Symbolic Links in details in Operating System.

### We represent hidden by writing .env as we now.
So to view all files such as hidden files we need to use ``` ls -a ``` 

```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ ls -a
./  ../  .env  image.png  readme.MD  test.sh
```

## We also have one more command ``` ls -la ```

```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$  ls -la
total 42
drwxr-xr-x 1 ALOK 197609     0 Jun 25 22:26 ./
drwxr-xr-x 1 ALOK 197609     0 Jun 17 22:55 ../
-rw-r--r-- 1 ALOK 197609    27 Jun 25 22:26 .env
-rw-r--r-- 1 ALOK 197609 36645 Jun 17 23:31 image.png
-rw-r--r-- 1 ALOK 197609  2972 Jun 25 22:30 readme.MD
-rw-r--r-- 1 ALOK 197609    44 Jun 17 23:06 test.sh
```


# 5. Creating, Copying, Moving, Deleting and Renaming Files and Directories (touch, mkdir, cp, mv, rm, rmdir)

## 1. Creating Files by using ``` touch file_name ```
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ touch style.css
```
### Creating mutiple file in one time ``` touch file_name file_name file_name file_name ```

```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ touch scripy.js page.tsx page.jsx
```
#### We can't create a directory (Folder) by using ``` touch ``` command

## 2. Create Directory we need to use ``` mkdir ``` Command
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ mkdir src
```

## Creating mutiple directory (folder) in one time use ``` mkdir folder_name folder_name folder_name folder_name ```
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ mkdir src_1 src_2 src_3 src_4
```
## 3. copying file from one directory (folder) to another directory
```
ALOK@DESKTOP-D41A0U8 MINGW64 /d/Complete_Backend_With_NodeJS/002_Basics_Of_Terminal/01_Introduction_To_Terminal
$ cp .env src
```
**cp means copy path** 



