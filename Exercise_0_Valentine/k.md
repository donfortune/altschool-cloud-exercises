vagrant@ubuntu-focal:~$ useradd -s /sbin/nologin first_user
useradd: Permission denied.
useradd: cannot lock /etc/passwd; try again later.
vagrant@ubuntu-focal:~$ sudo useradd -s /sbin/nologin first_user
vagrant@ubuntu-focal:~$ cat /etc/passwd | grep first_user
first_user:x:1005:1006::/home/first_user:/sbin/nologin
vagrant@ubuntu-focal:~$ 