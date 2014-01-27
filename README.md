<img src="http://neustarpc.github.com/neustar-clouds/images/logo.png"><br>

This is a profile of the [XDI2](http://github.com/projectdanube/xdi2) server, configured to use [MongoDB](http://github.com/projectdanube/xdi2-mongodb)
as a backend for graph storage, and to instantiate XDI graphs for Neustar-hosted XDI2 Personal Clouds.

### How to build

First, you need to build the main [XDI2](http://github.com/projectdanube/xdi2) project.

Then build the two connectors
	
    xdi2_mongodb
    xdi2_connector_facebook
    
...both found in [ProjectDanube](https://github.com/projectdanube) project.

Note: That all 3 of these builds will get dropped in your .m2 local repository. The connectors generate .war files.

    
After that, just run

    mvn clean install

To build all components.

### How to run

    mvn jetty:run

Then the XDI2 status page is available at

	http://localhost:14440/
