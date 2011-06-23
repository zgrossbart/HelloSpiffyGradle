[Hello Spiffy Gradle](http://www.spiffyui.org) - GWT Made Simple
==================================================

Hello Spiffy Gradle is a sample application using the [Spiffy UI Framework](http://www.spiffyui.org) which builds a simple REST application with Gradle.


Building and Running Spiffy UI
--------------------------------------

Hello Spiffy Gradle is built with [Gradle](http://www.gradle.org/).  Once you've installed Gradle you must also get and build the [Gradle GWT plugin](https://github.com/markuskobler/gwt-gradle-plugin).  Build this plugin and then change the build.grandle file in the Hello Spiffy Gradle to point to the location of your built files.

After you've built the plugin you can build and run Hello Spiffy Gradle by going to your HelloSpiffyGradle working copy and running these commands:

        <GRADLE HOME>/gradle
        
This will download the project dependencies, build the Hello Spiffy Gradle project, and run it with an embedded Jetty web server.  You can access the running application at:

        http://localhost:8080

License
--------------------------------------

Hello Spiffy Gradle is available under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).


