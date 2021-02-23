run:
$ make
then:
$ sudo insmod jiffies.ko
next:
$ cat /proc/jiffies
sample output:
Jiffies: 4938340934

to remove:
sudo rmmod jiffies

(will remove proc path)