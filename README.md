# Backup Encrypted Password Files
## Scenario

ABC International Inc. currently suffers from a huge bottleneck: every day, interns must laboriously access encrypted password files on central servers and back up all files that have been updated in the last 24 hours. This process introduces human error, reduces security and requires an inordinate amount of work.

On this occasion a script called backup.sh has been commissioned to be created that runs every day and automatically backs up the encrypted password files that have been updated in the last 24 hours.

## Additional Information
- ``targetDirectory``: Directory containing all password files.
- ``destinationDirectory``: Directory containing the archiving backup file.
- 
Finally, we schedule the Bash script backup.sh to run every day at 00:00 with cron.

![Crontab](https://github.com/MssLune/Backup_encrypted_password_files/blob/main/crontab.png?raw=true)
