# jiffies-project
Cpsc-351 Project #1 

Justin Stitt

## Usage
```
> $ make
> !~~ Use appropriate 'Makefile' for each of the two included modules
> $ sudo insmod 'jiffies'/'seconds'.ko
> !~~ Two modules included, insert either 'jiffies' or 'seconds'
```
## Sample Output

```
> $ cat /proc/jiffies
```

![](/media/jiffies_sample_out.png)

```
> $ cat /proc/seconds
```

![](/media/seconds_sample_out.png)

## Proc Cleanup

Removal of procedure path upon module removal.

```
> $ sudo rmmod 'jiffies'/'seocnds'
```

![](/media/cleanup_img.png)
