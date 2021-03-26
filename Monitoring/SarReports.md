*** Using sar you can monitor performance of various Linux subsystems (CPU, Memory, I/O..) in real time.

Using sar, you can also collect all performance data on an on-going basis, store them, and do historical analysis to identify bottlenecks.

Sar is part of the sysstat package.

Refer to Man page of SAR [here](http://manpages.ubuntu.com/manpages/xenial/man1/sar.sysstat.1.html). 

To check statistics of 25th Day of the Month(Make sure that the file exists in the location specified)

```
sar -u -f /var/log/sysstat/sa25 
```
