# XWiki native packages for Archlinux.

This project provides native packages for Archlinux :

- xwiki-enterprise : install xwiki-enterprise on tomcat and hsqldb
- xwiki-enterprise-mysql : install mysql drivers for xwiki

## How to install

This packages are available from AUR and can be installed using yaourt. 
They are based on official tomcat7 package which comes as a dependency.

### Xwiki Enterprise

Open a terminal and enter : 

    yaourt -S xwiki-enterprise

### Xwiki Enterprise with mysql/mariadb

Open a terminal and enter :

    yaourt -S xwiki-enterprise-mysql
    
Edit /etc/xwiki-enterprise/hibernate.cfg.xml according to your configuration
- Comment out hsql part
- Uncoment and modify MySQL configuration
