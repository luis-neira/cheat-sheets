pg_restore is a utility for restoring a PostgreSQL database from an archive created by [pg_dump](https://www.postgresql.org/docs/current/app-pgdump.html "pg_dump") in one of the non-plain-text formats. It will issue the commands necessary to reconstruct the database to the state it was in at the time it was saved. The archive files also allow pg_restore to be selective about what is restored, or even to reorder the items prior to being restored. The archive files are designed to be portable across architectures.

pg_restore can operate in two modes. If a database name is specified, pg_restore connects to that database and restores archive contents directly into the database. Otherwise, a script containing the SQL commands necessary to rebuild the database is created and written to a file or standard output. This script output is equivalent to the plain text output format of pg_dump. Some of the options controlling the output are therefore analogous to pg_dump options.

Obviously, pg_restore cannot restore information that is not present in the archive file. For instance, if the archive was made using the “dump data as `INSERT` commands” option, pg_restore will not be able to load the data using `COPY` statements.

## Restore Local Database Command

```bash
pg_restore -h localhost -U fastlane -d fastlane --verbose db.tar
```

## Options
FLAG | DESCRIPTION
---|---
`-h` **`host`** | Specifies the host name of the machine on which the server is running. If the value begins with a slash, it is used as the directory for the Unix domain socket. The default is taken from the `PGHOST` environment variable, if set, else a Unix domain socket connection is attempted.
`-U` **`username`** | User name to connect as.
`-d` **`dbname`** | Connect to database _`dbname`_ and restore directly into the database. The _`dbname`_ can be a [connection string](https://www.postgresql.org/docs/current/libpq-connect.html#LIBPQ-CONNSTRING "34.1.1. Connection Strings"). If so, connection string parameters will override any conflicting command line options.
`-v` `--verbose` | Specifies verbose mode. This will cause pg_restore to output detailed object comments and start/stop times to the output file, and progress messages to standard error. Repeating the option causes additional debug-level messages to appear on standard error.

