php-installer
=============

PHP Installer

##How to use in Linux Debian:

```console
(~) # id
uid=1000(username) gid=1000(usergroup) groups=1000(usergroup),50(staff)
```

You need clone the project to some directory:
```console
(~) # cd /usr/local/share/
(/usr/local/share) # git clone https://github.com/ArtemTeleshev/php-installer.git
```

Create symlink for main script:
```console
(~) # cd /usr/local/bin
(/usr/local/bin) # ln -s ../share/php-installer/php-installer
```
Execute command:
```console
(~) # php-installer
Usage: php-installer {list|show|change|update|install|extension|delete|help}
(~) # php-installer extension
Usage: extension {http|pcntl|help}
(~) # php-installer help
Script for easy installation more one version of PHP.
.....
(~) # php-installer extension help
Script for easy installation of PHP extension.
.....
```
