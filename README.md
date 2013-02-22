ApacheWordPressDev
==================

Apache Config module settings for WordPress local development environment

These are the instructions I use for modifying my XAMPP Apache httpd.conf file. These instructions are Mac-orientated.

1. Edit Applications/XAMPP/etc/httpd.conf (Mac location)
2. Locate the block that starts with the first "LoadModule" line; select to the last "LoadModule" line
3. Replace that block with the block here (in the file LoadModule_Settings)
4. Under User/Group, add User = <your account name>, and Group = apache
5. You will have to create an apache group for your system. Open System Settings > Users and Groups; create a new user "apache" of special type Group
4. Under "# Virtual hosts", un-comment the line for httpd-vhosts.conf

Save that file.
