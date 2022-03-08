# Apparmor-Microsoft-teams

Existing profile match for Microsoft Teams version 1.4

To let your Apparmor profile work for Microsoft Teams, please add below line to /etc/ld.so.conf, after that run 'ldconfig' :

/home/daniel/data/apparmor.d/usr.share.teams.teams
