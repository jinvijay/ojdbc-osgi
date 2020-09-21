# ojdbc-osgi
Project to convert ojdbc jar to osgi bundle

This project specifically osgi-fies the ojdbc7 (available in the local repository) for Oracle v12.1.0.2. osgi bundle is created using the spring roo framework. 

Maven Command to add ojdbc to local repository
mvn install:install-file -Dfile=ojdbc7.jar -DgroupId=com.oracle -DartifactId=ojdbc57 -Dversion=12.1.0.2 -Dpackaging=jar

Roo Command
addon create wrapper --topLevelPackage com.oracle.convert.osgi --groupId com.oracle --artifactId ojdbc7 --version 12.1.0.2 --vendorName Oracle --licenseUrl http://www.oracle.com
