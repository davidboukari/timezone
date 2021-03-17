# timezone

 timedatectl
 ```
      Local time: mer. 2021-03-17 09:27:43 EDT
  Universal time: mer. 2021-03-17 13:27:43 UTC
        RTC time: mer. 2021-03-17 13:27:43
       Time zone: America/New_York (EDT, -0400)
     NTP enabled: no
NTP synchronized: no
 RTC in local TZ: no
      DST active: yes
 Last DST change: DST began at
                  dim. 2021-03-14 01:59:59 EST
                  dim. 2021-03-14 03:00:00 EDT
 Next DST change: DST ends (the clock jumps one hour backwards) at
                  dim. 2021-11-07 01:59:59 EDT
                  dim. 2021-11-07 01:00:00 EST
```

timedatectl list-timezones | grep -i Paris
```
Europe/Paris
```

timedatectl set-timezone Europe/Paris
 
timedatectl
```
      Local time: mer. 2021-03-17 14:29:36 CET
  Universal time: mer. 2021-03-17 13:29:36 UTC
        RTC time: mer. 2021-03-17 13:29:36
       Time zone: Europe/Paris (CET, +0100)
     NTP enabled: no
NTP synchronized: no
 RTC in local TZ: no
      DST active: no
 Last DST change: DST ended at
                  dim. 2020-10-25 02:59:59 CEST
                  dim. 2020-10-25 02:00:00 CET
 Next DST change: DST begins (the clock jumps one hour forward) at
                  dim. 2021-03-28 01:59:59 CET
                  dim. 2021-03-28 03:00:00 CEST
```

date
```
mer. mars 17 14:29:42 CET 2021
```
