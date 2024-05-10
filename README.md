
# Description  

This vulnerability occurs when users in the web-admin group enter commands on the crontab by selecting the root shell. 
As a result of exploiting the vulnerability,authenticated web-admin users can run commands with root privileges and receive reverse shell connections. 
It can also be used in privilege escalation attacks on local systems.

# Options

| Option              | Description                              |
|---------------------|------------------------------------------|
| -h, --help          | Show this help message and exit          |
| -U IP, --ip IP      | Victim Ip Address                        |
| -u USERNAME, --username USERNAME | Username For Web Admin         |
| -p PASSWORD, --password PASSWORD | Password For Web Admin         |
| -L LHOST, --lhost LHOST | Listener IP Address For Reverse Shell   |
| -P LPORT, --lport LPORT | Listener Port For Reverse Shell        |


# POC 



https://github.com/GTxNoMercy00/REP/assets/169443064/f91b6911-09e9-4753-aee9-8836e58aea71

