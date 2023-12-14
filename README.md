# NIM-Conn-System-REST-PowerSchool-SIS
NIM Connector for PowerSchool SIS

## API Setup
- Click System Settings. The System Settings page appears.
- Click Plugin Management Configuration. The Plugin Management Dashboard page appears.
- Click Install. The Plugin Install page appears.
- For the Plugin Installation File, see  [Tools4ever_plugin.zip](Assets/Tools4ever_plugin.zip)
- Click Install. A confirmation message appears. The plugin appears in the Installed Plugins section on the Plugin Management Dashboard page.
- Retrieve Client ID and Secret

# Known Issues
- Fees Data does not load properly

# Database Access
In case you need additional data not available via the API you can leverage a direct database connection. See https://github.com/Tools4ever-NIM/NIM-System-PowerShell-Oracle-SQL

## Recommended Data Tables
- PS_PREFS
- PS_PSSIS_PERSON_EMAIL
- PS_PSSIS_PERSON_PHONE
- PS_PSSIS_STU_CONTACT_ACT_CUST
- PS_PS_ENROLLMENT_ALL
- PS_SCHOOLS
- PS_STUDENTCOREFIELDS
- PS_STUDENTS
- PS_S_ID_STU_X
- PS_U_STU_FORMS
- PS_U_STU_GENERAL
- PS_EMAILADDRESS
- PS_PERSONEMAILADDRESSASSOC
- PS_S_ID_SCH_X

# NIM Docs
The official NIM documentation can be found at: https://docs.nimsuite.com
