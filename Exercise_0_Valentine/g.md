$ pwd
/home/altschool/misc
$ ls
fileA  fileC  fileD
$ tar -cf misc.tar misc
tar: misc: Cannot stat: No such file or directory
tar: Exiting with failure status due to previous errors
$ ls
fileA  fileC  fileD  misc.tar
$ cd ..
$ 