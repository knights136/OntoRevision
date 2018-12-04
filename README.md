# OntoRevision
OntoRevision is distributed under the terms of the GNU Lesser General Public License as published by 
the Free Software Foundation, either version 3 of the License, or (at your option) any later version. 
ontorevision.jar contains a file named COPYING for details of GNU GENERAL PUBLIC LICENSE Version 3,29 June 2007 and 
the COPYING.LESSER file has details about the GNU LESSER GENERAL PUBLIC LICENSE Version 3, 29 June 2007.


## Requirements notes:

* Java SE Runtime Environment 1.6.0
* Protege version 1.4.0 Build 239

Notes:
If protege doesn't start when using the run.bat in the protege directory then it 
maybe because the computer is configured to using a different version of java at the command line. 
If java at the command line is not version 1.6 then instead of java ... used at the command line use 
<Path to java.exe for version 1.6> ...

## Install notes:

Simply copy ontorevision.jar into the protege plugins directory.

## Source code notes:

The source code for OntoRevision is located within the ontorevision.jar file.
    

### Plug-in Dependencies:

* org.protege.editor.owl.jar;min bundle-version="4.1.0"
* org.semanticweb.owl.owlapi.jar;min bundle-version="3.1.0"
* org.protege.common.jar;min bundle-version="4.1.0"
* org.protege.editor.core.application.jar;min bundle-version="4.1.0"

