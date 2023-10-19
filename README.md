# backup_postgresql
=======

```commandline
[postgres@bddzbx backup]$ crontab -l
00 20 * * * /data/backup/pg_backup_rotated.sh >> /data/backup/logs/`date +\%Y-\%m-\%d`.log 2>&1
```
