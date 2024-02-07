$ ls
fileA  fileC  fileD  misc.tar
$  gzip misc.tar
$ ls
fileA  fileC  fileD  misc.tar.gz
$ exit
vagrant@ubuntu-focal:~$ sudo useradd -m test_user
vagrant@ubuntu-focal:~$ su - test_user
Password: 
su: Authentication failure
vagrant@ubuntu-focal:~$ sudo su - test_user
$ pwd
/home/test_user
$ cd ..
$ exit
vagrant@ubuntu-focal:~$ chage -d 0 test_user
chage: Permission denied.
vagrant@ubuntu-focal:~$ sudo chage -d 0 test_user
vagrant@ubuntu-focal:~$ sudo su - test_user
You are required to change your password immediately (administrator enforced)
Changing password for test_user.
Current password: 
vagrant@ubuntu-focal:~$ sudo su - test_user
You are required to change your password immediately (administrator enforced)
Changing password for test_user.
Current password: 
vagrant@ubuntu-focal:~$ 