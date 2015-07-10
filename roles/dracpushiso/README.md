# DRAC push iso
In order to get Ansible to push a ISO I had to work around a bug in the iDRAC. It has a issue if you drop your connection to quickly before the transfer starts. Which is why there is a sleep 5 statement in the expect script.

