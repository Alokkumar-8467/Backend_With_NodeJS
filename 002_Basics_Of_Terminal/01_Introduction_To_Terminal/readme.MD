# Basic Shell Commands (echo, pwd, whoami)

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


# Navigating the File System(cd)
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

## Symbolic link when we type ls command in bash terminal.
