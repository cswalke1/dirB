# dirB
directory bookmarks on the bash Linux command line.  an implementation of icyfork/dirb

# Original LICENSE

Directory Bookmarks for BASH (c) 2009, Ira Chayut, Version 090927

 DirB and its implementation in this file are the product of, and
 copyrighted by Ira Chayut.  You are granted a non-exclusive, royalty-free
 license to use, reproduce, modify and create derivative works from DirB;
 providing that credit is given to DirB as a source material.

 The lastest version is available from: http://www.dirb.info/bashDirB.
 Ira can be reached at ira@dirb.info.

 Icy forked the source from http://dirb.info/ to customize the script
 for his own purpose. You can modify, redistribute and create derivative
 works from Icy's fork, providing that credit is given to DirB as a
 source material.

# Modified Works

dirB.sh is the product of Craig Walker, a modified version of the original dirb.sh and given the **GNU GENERAL PUBLIC LICENSE  Version 3, 29 June 2007**

# help
```
OPERATIONS
  s       Save a directory bookmark
  g       go to a bookmark or named directory
  p       push a bookmark/directory onto the dir stack
  r       remove saved bookmark
  d       display bookmarked directory path
  sl      print the list of directory bookmarks
EXAMPLES
  s xyz                  current directory is saved as xyz
  s xyz ../../dir0/dir1  save relative directory as xyz
  s xyz dir notes here   save directory with comments
  g xyz                  go to bookmark xyz or to path xyz
  p xyz                  go to bookmark/directory xyz
                         and remember into the directory stack
  p                      swap to two bookmarks
  p +                    push current directory to dir stack
  p -                    pop off a path from top
  p +n                   rotate nth entry from top to top
  p -n                   rotate nth entry from bottom to top
  pd                     same as p except no output (use pl for output)
  pd +                   push current directory to dir stack except no output
  pd -                   pop off a path from top except no output                
  pd +n                  same as p except no output, + is - and n=n-1
  pd -n                  same as p except no output, - is + and n=n-1
  pl                     list of dir stack with line numbers
  r xyz                  remove named bookmark
  d xyz                  display directory name of bookmark xyz
  sl -l                  long list
  sl -p                  path list
  sl "*x"                list all of all bookmarks *x
  sl -l "*x"             long list all of all bookmarks *x

```

