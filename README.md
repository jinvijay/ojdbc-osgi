# ojdbc-osgi
Project to convert ojdbc jar to osgi bundle

This project specifically osgi-fies the ojdbc7 for Oracle v12.1.0.2. osgi bundle is created using the spring roo framework. 

Command
addon create wrapper --topLevelPackage com.oracle.convert.osgi --groupId com.oracle --artifactId ojdbc7 --version 12.1.0.2 --vendorName Oracle --licenseUrl http://www.oracle.com
