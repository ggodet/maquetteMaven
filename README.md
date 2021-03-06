voir http://fr.wikipedia.org/wiki/Markdown

Grails
===

[Grails][Grails] is a framework used to build web applications with the [Groovy][Groovy] programming language. The core framework is very extensible and there are numerous [plugins][plugins] available that provide easy integration of add-on features.
[Grails]: http://grails.org/
[Groovy]: http://groovy.codehaus.org/
[plugins]: http://grails.org/plugins/

Getting Started
---

You need a Java Development Kit (JDK) installed, but it is not necessary to install Groovy because it's bundled with the Grails distribution.
You also need a Maven distribution with version > 2.0.9 (plugins were not tested with versions anterior to this).
Where grailsVersion is your grails distribution version, in your terminal/console : 
	
	mvn archetype:generate -DarchetypeGroupId=org.grails -DarchetypeArtifactId=grails-maven-archetype -DarchetypeVersion=${grailsVersion} -DgroupId=example -DartifactId=my-app -DarchetypeRepository=http://repo.grails.org/grails/core/
	mvn initialize

For further usage refer to the Grails documentation on maven : http://grails.org/doc/latest/guide/commandLine.html#antAndMaven

If you want to use a snapshot version of grails-maven-plugin, then you must uncomment the snapshot repositories inside of the generated pom.xml.

License
---

Grails and Groovy are licensed under the terms of the [Apache License, Version 2.0][Apache License, Version 2.0].
[Apache License, Version 2.0]: http://www.apache.org/licenses/LICENSE-2.0.html
