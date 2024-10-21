# PostgreSQL Cheat Sheet
    psql -U postgres
## Show all databases
    \l
## Show current database
    \c <database>
## Show all tables
    \dt
## Show all columns in a table
    \d <table>
## 备份全部数据库
    pg_dumpall -U username > output.sql
    docker exec -t <container_id> pg_dumpall  -U postgres > ~/backup.sql
