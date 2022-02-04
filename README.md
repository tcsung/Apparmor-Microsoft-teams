# Apparmor-Microsoft-teams
To let your Apparmor configuration work for Microsoft Teams, please add below line to /etc/ld.so.conf, after that run 'ldconfig' :

/home/daniel/data/apparmor.d/usr.share.teams.teams
