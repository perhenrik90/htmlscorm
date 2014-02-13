# HTML -> SCORM
This will be a small program that wraps a html project into SCORM e-learning format.
It generates a imsmanifest file for SCORM 1.2.

## Terminal syntax
It will be posible to execute the "htmlscorm" command from the root of the html project. 
The imsmanifest.xml file is then saved in the project folder.

- htmlscorm <projectname> <projecttitle>

The command includes all files stored in the project directory

## Things to be done

- recursive file traversal
- auto ziping of the scorm package
