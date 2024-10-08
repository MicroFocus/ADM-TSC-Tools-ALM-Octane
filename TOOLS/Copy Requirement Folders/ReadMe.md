# Copy Requirement Folders

This utility allows you to select a specific requirement folder, and it will recreate the child structure (folders and requirement documents) in another specified folder. Only name and description fields are copied.

The tool will first guide you through extracting the structure of the Requirements module using oData. Once you have this data, it is mandatory to use the "Filter" option to select the folder to be copied. This tool will not work on the "requirement root" level.

Next, you'll need to specify the workspace connection details and the folder id, where you wish the data to be written to. We recommend creating a new blank folder for this purpose.

Please note:
- Tool cannot create more levels than supported by your workspace
- Only name and description fields are copied
- The structure on each level is sorted alfabetically
- The instruction apply to Excel 2016 and above
- Recommended to run on the main monitor if in a dual monitor setup.
- Ensure Macro and trusted location security does not block any functionality

Required information:
- Server url, shared space id and workspace id
- API Key (client id and secret) with permissions to update requirement data in the workspace
- Select folder to copy from and enter folder id to paste to.
