# Pickle Rick Notes 

Save the IP for easy use in terminal `export IP=10.10.10.10` so that you could just like `nmap -A $IP -T4`.

Use `nikto` to scan common web vulnerabilites, ex. `nikto -host http://10.10.167.2`.

Use `Gobuster` to list all possible directories, ex. `gobuster dir -u http://10.10.167.2 -w /usr/share/dirbuster/wordlists/directory-list-2.3-medium.txt -x php,txt,sh,cgi,html,js,css,py -t 100`

Other way to RCE read file: `grep -R .` for all files under the same directory or `grep . filename` for a specific file

Easy base64decode in terminal, `echo blablablabla | base64 -d | base64 -d | base64 -d`

Search for (python) reverse shell: go pentestmonkey.net or PayloadsAllTheThings

use `sudo -v` to check if we have permission to run sudo.

use `sudo -l` to find out what you're allowed to run with different privileges.

`cat *` can list all contents of the files in the same directory.
