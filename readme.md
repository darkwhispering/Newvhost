NEWVHOST SCRIPT
====================

Simple script to help you create new Apache virtual hosts quickly and pain free. With the optional step to also create a mysql database and user for your new virtual host.

Requirements
---------------------
- Apache 2.4+
- MySQL 5+
- User with sudo access

Installation
---------------------

1. Download the files and upload to any location on your server.
2. Edit the first section of *newvhost* after your needs.
3. Give the *installer* script execution permission with `chmod +x installer`
4. Run the installer with `sudo ./installer`
5. Use the now available `sudo newvhost` command to create your first virtual host.

When finished the installation you can safely delete the files you downloaded.

Uninstallation
---------------------

1. Give the *uninstaller* script execution permission with `chmod +x uninstaller`
2. Run the uninstaller with `sudo ./uninstaller`
3. Done

Configuration
---------------------

| Variable      | Default value | Description                                                                                     |
|---------------|---------------|-------------------------------------------------------------------------------------------------|
| tSERVERUSER   | root          | User to user for permissions                                                                    |
| tLOCATION     | /var/www      | Location to host all virtual hosts (recommended is the home folder of the user specified above) |
| tLOCATIONSAFE | \/var\/www    | Safe ocation path, must be same as tLOCATION!                                                   |
| tDBPW         | null          |                                                                                                 |

Tested environment
---------------------

The script have been tested succefully on a clean machines running

- Ubuntu 14.04 LTS with Apache 2.4 and MySQL Server 5.5
- Debian 7.5 with Apache 2.4 and MySQL Server 5.5


Special thanks
---------------------

Special thanks to my friend Tzunamii for the original script and code.

By me a beer
---------------------

Like and use any of my pluings and scripts? Me too!

[By me a beer](http://darkwhispering.com/by-me-a-beer)

Changelog
---------------------

### v1.1.0 (2015-02-18)
- Updated vhost templet for Apache 2.4+
- Added some more comments to newvhost script
- Added required section to readme
- Smaller changes to readme

### v1.0.0 (2014-07-13)
- First release
