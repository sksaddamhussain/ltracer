# ltracer (Login Tracer)
Utility is designed to report login related information

It is tricky to handle audit logs for login information especially if you have multiple auditd rules configured and also there are chances that due to intteruption of auditd service you will endup with no sufficent information.

Linux kernel by default keeps track of login information but those logs are binary files.

ltracer utility reports login [attempts via SSH] related information with the support from linux kernel utilities to collect data from kernel files [translate binary log files to Human readable format] and then extract mostly interested columns out of several columns.

Displayed data is formatted in simple layout with the option to export the data in csv format for analysis.

# How to use this utility
Below are the steps that needs to be followed 
1. Download rpm file from https://raw.githubusercontent.com/sksaddamhussain/ltracer/master/ltracer-1.0.0-1.noarch.rpm
2. Install rpm file using below command
  > rpm -ivh tracer-1.0.0-1.noarch.rpm
3. Now, execute 'ltracer' [as root user or with sudo]
  > sudo ltracer
4. It will display welcome screen and prompt for Input form listed options
5. After submitting your choice now it will display requested information in a viewer [to exit from viewer press 'q' button in keyboard]
6. Upon exit from viewer it will prompt "Would you like to save this report [Y/N]"
7. If you choose 'Y' then it will save report on /tmp directory and also displays file location on your terminal for your reference.
8. After above step program gets terminated.

Please give it a try and feedback is highly appreciated.
