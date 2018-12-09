Will output the startup and shutdown time for each day in the past and calculate the uptime.
WARNING: Assumes that the computer is always shutdown before 00:00!

Example:
```
> go-worktime-collector.exe 10
searching eventlog for last 10 days... found 16264 entries

09. December 2018
15:43 — 20:41
total: 3.97h

08. December 2018
08:15 — 23:40
total: 15.42h

07. December 2018
18:48 — 22:43
total: 3.92h

05. December 2018
18:20 — 23:56
total: 5.60h

04. December 2018
17:04 — 20:11
total: 3.13h

02. December 2018
16:21 — 21:25
total: 5.08h
```