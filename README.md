apache_to_lighttpd
==================

moving from apache server to lighttpd server
lighttpd doesnt work with .htaccess files, so you will need to rewrite rules to lighttpd format
below are are links to relevant guides

task is:

1. rewrite the general htaccess rules - look for "THESE NEED TO BE REWRITTEN" in lighttpd.conf - here is guide i found (look for paragraph with headline "Rewriting Rules") https://www.packtpub.com/books/content/migration-apache-lighttpd - more info: http://redmine.lighttpd.net/projects/1/wiki/migratingfromapache

2. I found all htaccess files on my server and we need to "translate them" to lighttpd too. I found this guide - i think its helpfull - http://redmine.lighttpd.net/projects/1/wiki/Docs_ModAccess

