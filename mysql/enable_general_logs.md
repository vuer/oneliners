Set path:
```sql
SET GLOBAL general_log_file='/var/log/mysql/general.log';
```

Set format:
```sql
SET GLOBAL log_output = 'FILE';
```

Enable general log:
```sql
SET GLOBAL general_log = 'ON';
```

Show general log settings:
```sql
SHOW VARIABLES LIKE "general_log%";
```
