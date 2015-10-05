# user-anonimize

Overrides Contributors widget to show User ID instead of Full Name.

Contributors summary widget is no longer a link to the user profile.

No configuration is needed. If this plugin is deployed, contributors are anonimized.


#Synopsis

This plugin makes the colaborators widgets show only the User ID, so no name or surname are shown to other users.

Also, contributors are no longer a link to the user profile.

#Installation

You just have to compile the pom.xml using Maven and deploy the plugin in. To do this, you must use the following script:

	cd user-anonimize-master
	mvn clean install
	cp target/Download_Log-*.jar $NUXEO_HOME/nxserver/plugins

And then, restart your nuxeo server and enjoy.