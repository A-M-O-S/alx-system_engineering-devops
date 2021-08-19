su is used to switch the current user to another user
id -un is used to print the effectiveusername of the current user
groups is used to print all the groups the current user is part
chown is used to change the owner of a file
touch is used to create a file
chmod u+x is used to make a file executable
chmod u+x,g+x,o+r hello is used to give multiple permissions
chmod a+x / chmod ugo+x are both used to add permissions to the owner, group owner and other users of a file
chmod 007 is used to give all users permissions and no permisssions to the owner and group
chmod 753 is used to user to be the only one to read, write and execute while other can't read, can write and cand execute and the group can read, can't write and can execute
chmod --reference=olleh hello mirrors a file