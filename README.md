orzdba
======

 参照网上的orzdba脚本用python实现的mysql 工具
 
 
## Run command

执行以下脚本，如果需要密码需要另外传递

```
 ./orzdba.py -i 3 -mysql
```

```
usage: orzdba.py [-h] [-i INTERVAL] [-t] [-sys] [-l] [-c] [-d DISK] [-n NET]
                 [-s] [-com] [-innodb_rows] [-innodb_pages] [-innodb_data]
                 [-innodb_log] [-innodb_status] [-innodb] [-T] [-B] [-rt]
                 [-hit] [-mysql] [-P PORT] [-S SOCKET] [-p PWD] [-C COUNT]
                 [-L LOGFILE] [-logfile_by_day] [-lazy] [--nocolor]
                 
optional arguments:
  -h, --help            show this help message and exit
  -i INTERVAL, --interval INTERVAL
                        Time(second) Interval.
  -t, --time            Print The Current Time.
  -sys                  print SysInfo (include -l,-c,-s).
  -l, --load            Print Load Info.
  -c, --cpu             Print Cpu Info.
  -d DISK, --disk DISK  Print Disk Info.
  -n NET, --net NET     Print Net Info.Time.
  -s, --swap            Print The Swap Info.
  -com                  print mysql status.
  -innodb_rows          Print Innodb Rows Status.
  -innodb_pages         Print Innodb Buffer Pool Pages Status.
  -innodb_data          Print Innodb Data Status.
  -innodb_log           Print Innodb Log Status.
  -innodb_status        Print Innodb Status from Command: "Show Engine Innodb
                        Status".
  -innodb               Print Innodb Info.
  -T, --threads         Print Threads Status.
  -B, --bytes           Print Bytes Status.
  -rt                   Print MySQL DB RT.
  -hit                  Print Innodb Hit%
  -mysql                print SysInfo (Print MySQLInfo (include
                        -t,-com,-hit,-T,-B).
  -P PORT, --port PORT  Port number to use for mysql connection(default 3306).
  -S SOCKET, --socket SOCKET
                        Socket file to use for mysql connection.
  -p PWD, --pwd PWD     root user password.
  -C COUNT, --count COUNT
                        Times.
  -L LOGFILE, --logfile LOGFILE
                        ath of logfile.
  -logfile_by_day       one day a logfile.
  -lazy                 Print Info (include -t,-l,-c,-s,-m,-hit).
  --nocolor             Print NO color.
```
