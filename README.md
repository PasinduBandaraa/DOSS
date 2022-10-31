<style>
red { color: red }
yellow { color: yellow }
</style>

# DOSS

DOSS Assignment

### 3) Maintain the log records of accessing to the database and maintain the minimum access privileges to the existing servers and applications. <red>[8pts]</red>

**SELECT group#, member FROM v$logfile ORDER BY group#, member;**

> *To get Redo Log file information from the control file we input this sql command*

**SELECT * FROM V$LOG;**

> *To get information about Redo log groups and members and member status we entered this query*

**SELECT * FROM V$logfile;**

> *To see information about log history we enter this query*

**SELECT * FROM V$log_history;**



### 4) Maintain individual login credentials for the people who access the workstation and to perform administrative tasks of the databases [5pts]

| User | Password | Role |
| --- | --- | --- |
| Pasindu | pasindu123 | System_Manager |
| Methmi | methmi123 | System_Developer |
| Sanduni | sanduni123 | System_Developer |
| Hansa | hansa123 | System_Operator |
| Amali | amali123 | System_Operator |
| Kasun | kasun123 | Accountant |

| Role | Privileges |
| --- | --- |
| System_Manager | Create Table, Create View |
| System_Developer | Create Any Table, Alter Any Table |
| System_Operator | Create Any Table |
| Accountant | Create Any Table, Delete Any Table |


