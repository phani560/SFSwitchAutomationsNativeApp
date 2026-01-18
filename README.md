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






# List of all active and inactive components 

<img width="1495" height="613" alt="image" src="https://github.com/user-attachments/assets/d9205afc-41d7-4283-855c-e9fc34a9d417" />


# Bulk Enabling / Disabling Components Progress 

<img width="1493" height="352" alt="image" src="https://github.com/user-attachments/assets/7af76339-903e-4008-b5bd-f374d8dcc755" />

# Toggle on specific component

<img width="1472" height="686" alt="image" src="https://github.com/user-attachments/assets/a13a3969-705f-4884-a9b5-0606d1964e40" />

# Toggle off specific Component

<img width="1491" height="636" alt="image" src="https://github.com/user-attachments/assets/edb0d9b2-b37a-4eb1-942b-c443db8fbef4" />



