Calculate Requirement Path

It's not yet possible to access the full Requirement path when generating Document Reports. This utility calculates the short (based on 2 digit numerical position) path and long path (based on Requirement name) and updates the values to 2 user defined fields. These fields can then be used to generate the document report based on your folder structure.

Please note:
- Tool supports up to 99 child items and up to 25 levels
- The structure on each level is sorted alfabetically
- The instruction apply to Excel 2016 and above
- Recommended to run on the main monitor if in a dual monitor setup.
- Ensure Macro and trusted location security does not block any functionality

Required information:
- Server url, shared space id and workspace id
- API Key (client id and secret) with permissions to update requirement data in the workspace
- 2 user defined fields to store the structure

This is how to create the 2 user defined fields to upload the 2 structures:
Go to Settings -> Spaces -> Select the workspace -> Select the “Entities” tab -> Select “Requirement Document” -> Select the “Fields” tab to create 2 new fields:
1. The short structure should be of type “String field”
2. The long folder name structure should be of type “Long String field”
