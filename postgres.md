# PostgresSQL
### Basic Operation
1.  Launch and Stop database
```
pg_ctl -D /usr/local/var/postgres start
pg_ctl -D /usr/local/var/postgres stop
```
2. Create database
```
createdb mydatabasename
dropdb mydatabasename
```
3. Connect to database
```
psql mydatabasename //cmd + d for quit
```
4. others
```
\list - List all of your actual databases.
\c mydatabasename - Connect to another database.
\d - List the relations of your currently connected database.
\d mytablename - Shows information for a specific table.
```

