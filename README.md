# Apparmor-Microsoft-teams

Existing configuration match for Microsoft Teams version 1.4

To let your Apparmor configuration work for Microsoft Teams, please add below line to /etc/ld.so.conf, after that run 'ldconfig' :

/home/daniel/data/apparmor.d/usr.share.teams.teams
