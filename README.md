islandora_log_config
===================

Rotates the logs created by Islandora, fedora, activemq,  gsearch and tomcat.

Will need to be modified to include mcroservices and batch ingest.
The first user who needs this should submit the patch.

file locations default

/etc/logrotate.d/islandora_logrotate

/usr/local/fedora/tomcat/webapps/fedoragsearch/WEB-INF/classes/log4j.xml

/usr/local/fedora/tomcat/conf/logging.properties

/usr/local/fedora/tomcat/webapps/adore-djatoka/WEB-INF/classes/log4j.properties

/usr/local/fedora/server/config/logback.xml
