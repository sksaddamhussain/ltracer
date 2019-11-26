# ltracer (Login Tracer)
Utility is designed to report login related information

It is tricky to handle audit logs for login information especially if you have multiple auditd rules configured and also there are chances that due to intteruption of auditd service you will endup with no sufficent information.

Linux kernel by default keeps track of login information but those logs are binary files.

ltracer utility uses linux kernel utilities to translate binary log files to Human readable format and then extract mostly interested columns out of several columns.

Above data is formatted in simple layout with the option to export the data in csv format for analysis.

* How to use this utility

Download rpm file from 
