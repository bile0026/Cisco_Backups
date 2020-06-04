# Cisco_Backups
Performs switch/router backups on cisco gear. Compares configurations with prior day (if a backup exists), and will then email the diff file as an HTML docuement to defined email addresses.

Saves the configs in backup location defined in ```dirpath``` (default is /ansible_backups/cisco/<date>)

Need to update your credentials in cisco_vars.yml, or use key auth.