## List queries currenty running

```sql
SHOW processlist
```

## Add column

```sql
ALTER TABLE <table> ADD COLUMN <column> <type> <extra parameter>
```

eg :

```sql
ALTER TABLE offer ADD COLUMN is_sent BOOLEAN DEFAULT NULL
```

## Get MySQL version

```sql
SELECT version()
```

## List locked table on MySQL

```sql
SHOW OPEN tables WHERE in_use > 1
```