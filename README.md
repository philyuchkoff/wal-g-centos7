# WAL-G binary for PostgreSQL/CentOS 7
WAL-G is an archival restoration tool for PostgreSQL, MySQL/MariaDB, and MS SQL Server (beta for MongoDB and Redis).

## Latest [WAL-G](https://github.com/wal-g/wal-g) binary for CentOS 7

Here is a compiled binary latest version of WAL-G (2.0.1) for those databases:

* PostgreSQL (`wal-g-pg`)
* MySQL/MariaDB (`wal-g-mysql`)
* MongoDB (`wal-g-mongo`)
* Redis (`wal-g-redis`)
* Greenplum (`wal-g-gp`)

## Installation
Just put the downloaded binary in `/usr/local/bin`:

````mv wal-g-DBNAME /usr/local/bin/wal-g````

for example: ````mv wal-g-redis /usr/local/bin/wal-g````

## Read:
- [WAL-G Docs](https://github.com/wal-g/wal-g/tree/master/docs)
- [About WAL-G and tests](https://medium.com/@philyuchkoff/wal-g-953490c74b98)
