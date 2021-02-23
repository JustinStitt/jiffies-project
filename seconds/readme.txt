run:
$ make
then:
$ sudo insmod seconds.ko
next:
$ cat /proc/seconds
sample output:
Jiffies: 13

to remove:
sudo rmmod seconds

(will remove proc path)