# Powershell_Script

This repo contains powershell scripts mainly for creating backup and restore.

Among them is the vcBackup.

vcBackup is a code to create a version controlled backup. It gets a source and destination
and create a copy of source in destination. If you run the code when there is a change in source
it will not create a new grassroot backup, but it will see which fies and folders are changed, then
it will create a timestamped folder to save the changes in that folder and update the backup in destination
So:
- destination has always a copy of most recent source
- any change from previous backup will be saved in a yyyy.mm.dd-hh.mm.ss folder
- a vcfile database will record all changes


**This repo is in progress. Codes will be added later on!**
