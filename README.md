JSPWiki Tika Search provider
------------------------

Example of the Tika Search provider integration in JSPWiki. 


Prerequisites
-------------
* at least Java 8
* latest snapshot (>= 2.11.0.M4-git-13)

Demoing
-------
* download / git clone this repo and `mvn clean install` all the modules
* go inside jspwiki-markdown-war and run `mvn org.codehaus.cargo:cargo-maven2-plugin:run`
* Markdown powered available at http://localhost:8080/jspwiki-tika-searchprovider-war after a few moments
* jspwiki-markdown-pages contains a couple of sample wikipages
