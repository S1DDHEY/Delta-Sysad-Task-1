## How to use ##
1. Clone this repo
2. ```sudo apt install acl adduser```
3. Make sure that all the files mentioned are in ```/home``` (not inside any other directory as the file path mentioned in the scripts is ```/home```)
4. ```sudo cat /home/custom_bashrc >> /etc/bash.bashrc```
5. ```source /etc/bash.bashrc```
6. Execute the scripts


## Uses for alias ##
1. ```userGen``` creates a core account (asks for passwd) and makes all the required directories and the user accounts as well.
2. ```domainPref <user> <roll no> <domain1> <domain2> <domain3>``` adds the users domain preference to the domain_pref file inside core's home dir.
