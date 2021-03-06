#set( $symbol_pound = '#' )
#set( $symbol_dollar = '$' )
#set( $symbol_escape = '\' )
${camunda-plugin-name}
=========================

${camunda-plugin-description}

This project has been generated by the Maven archetype
[${archetype-artifactId}-${archetype-version}](http://docs.camunda.org/latest/guides/user-guide/#process-applications-maven-project-templates-archetypes).


Show me the important parts!
----------------------------

![Screenshot](screenshot.png)


How does it work?
-----------------


How to use it?
--------------

You can use `ant` to build and install the plugin to an existing Cockpit
inside an application server.
For that to work you need to copy the file `build.properties.example` to `build.properties`
and configure the path to your application server inside it.
Alternatively, you can also copy it to `${symbol_dollar}{user.home}/.camunda/build.properties`
to have a central configuration that works with all projects generated by the
[Camunda BPM Maven Archetypes](http://docs.camunda.org/latest/guides/user-guide/#process-applications-maven-project-templates-archetypes).

Once you installed the plugin it should appear in
[Camunda Cockpit](http://docs.camunda.org/latest/guides/user-guide/#cockpit).


More information
----------------

[How to install a Cockpit plugin](http://docs.camunda.org/latest/real-life/how-to/#cockpit-how-to-develop-a-cockpit-plugin-integration-into-cockpit)

[How to develop a Cockpit plugin](http://docs.camunda.org/latest/real-life/how-to/#cockpit-how-to-develop-a-cockpit-plugin)

Discover more Cockpit plugins in the
[Camunda Plugin Store](http://camunda.org/plugins/)


Environment Restrictions
------------------------

Built and tested against Camunda BPM version ${camunda-version}.


Known Limitations
-----------------


Improvements Backlog
--------------------


License
-------

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
