# MSSQLDump
This Toolkit help you export all databases to csv file

```
.#######.
.###----^     @
.##v1l--^    (*) BETA MSSQLDump v1.0 Export SQL Server Data From Table To a CSV File!
.##-CORP--^ /---\       Author: github.com/Udyz
.#######.

usage: MSSQLDump [-h] [-s SERVER] [-u USER] [-p PASSWORD] [-db DATABASE] [-n] [key ...]

This Toolkit help you export SQL Server Data from table to csv file

positional arguments:
  key                   O_o Where is the key? Have you found it?

options:
  -h, --help            show this help message and exit
  -s SERVER, --server SERVER
  -u USER, --user USER
  -p PASSWORD, --password PASSWORD
  -db DATABASE, --database DATABASE
                        OPTIONAL: when db default is master, this tool will auto grab db name then export it
  -n, --no-user         Login as trusted connection
```
![image](https://cehvietnam.files.wordpress.com/2021/03/nmap.jpg?w=10&key=lulzalx)

# Support
+ MSSQLDump cannot be used on Windows xp/2008 or earlier
+ CPU > 4 core 4 threads, RAM > 2 GB  

# Requirement
+ msodbcsql (ODBC Driver for SQL Server)
+ MsSqlCmdLnUtils (sqlcmd Utility)
