README
------

This repository should be used to store the following:
- All xForms that are used as part of the ODK-Liberia application
- The ROLES.xml file that defines which user types are able to access which forms
- The CASES.xml and SUMMARY.xml documents used to define "cases" and "summary statistics" as a part of a ODK-L 4.0 deployment

Notes:
- XML documents produced using the CommCare Vellum editor should be saved and stored here *before* the find-and-replace operation is done to make it work with ODK-L
- The GitHub release mechanism should be used to structure releases into the field
- Eventually, we will use the Grunt scripting tool to automate the find-and-replace operation and the compilation of the LMU file