# DOSS

DOSS Assignment

### 3) Maintain the log records of accessing to the database and maintain the minimum access privileges to the existing servers and applications. [8pts]

**SELECT group#, member FROM v$logfile ORDER BY group#, member;**

> *To get Redo Log file information from the control file we input this sql command*

**SELECT * FROM V$LOG;**

> *To get information about Redo log groups and members and member status we entered this query*

**SELECT * FROM V$logfile;**

> *To see information about log history we enter this query*

**SELECT * FROM V$log_history;**

<br>\

### 4) Maintain individual login credentials for the people who access the workstation and to perform administrative tasks of the databases [5pts]

