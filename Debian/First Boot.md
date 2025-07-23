
- login and switch to root
	- `su -`
- Install Sudo
	- `apt install sudo`
- set user as sudoer
	- `adduser beolson sudo`
- !! User must Logout and log back end to take effect !!

Remove cdrom from sources.list
- `sudo nano /etc/apt/sources.list`
-  Delete the cdrom line and save file

Import ssh keys
- `sudo apt install ssh-import-id`
- `ssh-import-id gh:beolson`


