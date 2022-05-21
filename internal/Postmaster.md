###  PostmasterMain
1. https://www.postgresql.jp/sites/default/files/2016-12/20040418232148.ikubo_postmaster_040419.pdf
2. https://wiki.moritetu.xyz/?PostgreSQL/%E8%A7%A3%E6%9E%90/Postmaster%E3%83%97%E3%83%AD%E3%82%BB%E3%82%B9


* https://stackoverflow.com/questions/26005359/core-function-in-postgres
```
For the postmaster, it's PostmasterMain in src/backend/postmaster/postmaster.c (postmaster startup) then ServerLoop in the same file.

For regular worker backends it's PostgresMain in src/backend/tcop/postgres.c.
```


### GUC
1. https://doxygen.postgresql.org/guc_8c_source.html
2. https://github.com/postgres/postgres/blob/master/src/backend/utils/misc/guc.c
