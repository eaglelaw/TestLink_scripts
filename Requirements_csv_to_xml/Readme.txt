Requirements script

The purpose of this script is to allow you to create an xml file (.txt) that can be imported to TestLink.
The file imported contains all the details to create new requirements items in the Requirements section of TestLink. 

The flow is the following:
* Add a csv file built with the same structure than the example in the same folder than the script
* From a terminal window, launch the script
* Import in TestLink, in the Requirement Specification section, the files. The import should be performed from the level 
above the one you want the requirements to be created.

One output file is created per category identified in the first column. You may then need to import several files from the same
Requirement specification level in TestLink. 

The script is written in Python version 3.

Limitation: TestLink does not seem to support updates on existing Requirement specification and requirements items. 
If a Requirement specification folder already exist, it is not possible using the import of the files generated by this script 
to import new requirements in this Requirement specification folder.