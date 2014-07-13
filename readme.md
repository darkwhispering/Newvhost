NEWVHOST SCRIPT
====================

Simple script to help you create new Apache virtual hosts quickly and pain free. With the optional step to also create a mysql database and user for your new virtual host.

Installation
---------------------

1. Download the files and upload to any location on your server.
2. Edit the first section of *newvhost* after your need.
3. Give the *installer* script execution permission with `chmod +x installer`
4. Run the installer with `./installer`
5. Use the now available *newvhost* command to create your first virtual host.

Uninstallation
---------------------

1. Give the *uninstaller* script execution permission with `chmod +x uninstaller`
2. Run the uninstaller with `./uninstaller`
3. Done

Configuration
---------------------

**tSERVERUSER** | *Default: root* | User to user for permissions

**tLOCATION** | *Default: /root/vhosts* | Location to host all virtual hosts (recommended is the home folder of the user specified above)

**tLOCATIONSAFE** | *Default: \/root\/vhosts* | Safe ocation path, must be same as tLOCATION!

**tDBPW** | *Default: null* | MySQL root password. If left empty, the script will ask for the password

Tested environment
---------------------

This script have been tested succefully on a clean machines running

- Ubuntu 14.04 LTS with Apache2 and MySQL Server 5.5
- Debian 7.5 with Apache 2 and MySQL Server 5.5


Special thanks
---------------------

Special thanks to my friend Tzunamii for the original script and code.

By me a beer
---------------------

Like and use any of my pluings and scripts? Me too!

[By me a beer](http://darkwhispering.com/by-me-a-beer)

Changelog
---------------------

### v1.0.0 (2014-07-13)
- First release
