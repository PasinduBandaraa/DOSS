# DOSS

DOSS Assignment

### 3) Maintain the log records of accessing to the database and maintain the minimum access privileges to the existing servers and applications. [8pts]

_SELECT group#, member FROM v$logfile ORDER BY group#, member;_

> *To get Redo Log file information from the control file we input this sql command*

_SELECT * FROM V$LOG;_

> *To get information about Redo log groups and members and member status we entered this query*

_SELECT * FROM V$logfile;_

> *To see information about log history we enter this query*

_SELECT * FROM V$log_history;_

<br>
