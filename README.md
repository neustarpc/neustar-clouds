<img src="http://projectdanube.github.com/xdi2/images/logo64.png"><br>

This is a profile of the [XDI2](http://github.com/projectdanube/xdi2) server, configured to use [Zephyr](http://github.com/airships/zephyr) as a backend for 
graph storage, and to instantiate XDI graphs for every authority in the xri.net Global Registry.

### How to build

First, you need to build the main [XDI2](http://github.com/projectdanube/xdi2) project.

After that, just run

    mvn clean install

To build all components.

### How to run

    mvn jetty:run

Then the XDI dictionary service is available at

	http://localhost:14440/

### Example XRI request and response

... TODO ...

### Community

Google Group: http://groups.google.com/group/xdi2
