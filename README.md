# SFSwitchAutomationsNativeApp
Inbuilt Salesforce App to enable / disable Flows, Process Builders, Validation Rules and Workflow Rules from single LWC component by using tooling api


Installation Steps:-

1. Deploy SFSWitchLatest.zip by using workbench or VS Code.

2. Create a NAMED Credentials in your salesforce org in the below order (this is required to access tooling api in LWC components)

     a. External Client App Manager
     
     b. External Auth Identity Provider
     
     c. External Credentials
     
     d. Named Credentials
     
3. Mention that Named Credentials Label Name in "Tooling_API_Named_Credentials" Custom label that was deployed as a part of this package.

4. Activate "Automation_Manager" lightning page to access LWC and then start using this tool.
