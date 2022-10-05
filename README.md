**Check a User Group in Linux**

*groups <username>*

*id -nG <username>*

**Remove a User from a Group in Linux**

*gpasswd -d <username>	<groupname>*

**Add a User to a Group in Linux**

*usermod -aG <groupname> <username>*

**Edit sudoers file to add normal user to root group**

*visudo -f /etc/sudoers*

**Change group for specific user**

*usermod -a -G <groupname> <username>*
