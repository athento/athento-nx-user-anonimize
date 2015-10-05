# athento-nx-user-anonimize


#Synopsis

This plugin makes the colaborators widgets show only the User ID, so no name or surname are shown to other users.

Also, contributors are no longer a link to the user profile.

#Installation

You just have to compile the pom.xml using Maven and deploy the plugin in. To do this, you must use the following script:

	cd athento-nx-user-anonimize
	mvn clean install
	cp target/athento-nx-user-anonimize-*.jar $NUXEO_HOME/nxserver/plugins

And then, restart your nuxeo server and enjoy.