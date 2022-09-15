# ProjectAtoll_Automation
To automate the process of Nominal generation from Survey report, Site ID request, archive the site and Transmitter details on Atoll and processing the Nominal through TIBCO work Flow.
#### By **Tonny Olaru and Clement Hawa**
## Description.
The Project has 5 workflows.
    1. The Nominal Survey Report(PowerApps/Sharepoint and Power Automate).
    2. Outlook Readmail Automation Process and SiteDB Details process
    3. Outtlook Attachment Automation
    4. Computation for the GSM TransmitterDT from siteDB.
The Automation Starts by Processing the powerApp form, PowerAutomate is used to process the form and send Outlook mail. Use the Outlook mails to get the contents of the form into
the site and Transmitter Databases. Theen Atoll is launched and both site and Transmiiters are archived. Loginto Tibco and fetch the site details from the Atoll.
find the assests and resource on https://github.com/Ochieng-28/ProjectAtoll_Automation.git
## Known Bugs
The project has no know bugs but inherent system Delays due to variation on Atoll and Tibco responses. These, are taken careoff using the check app state.
Again the system has not been stabilized to incooporate the variation of inputs.
## Technologies Used
For this exercise, one needs the understanding of the following;
    1. Uipath Studio
    2. PowerApp/PowerAutomate/Sharepoint lists
    3. Desktop Atoll forsk 3.4.1. 
    4. Tibco OpenSpace.
    5. Outlook for Desktop 2016.
    
## Support and contact details
This page is purely for Learning Purposes atleast for now. I invite any improvement and corrections through my contacts toniolaru@gmail.com; klemoh@gmail.com.
### License
*Determine the license under which this application can be used.  See below for more details on licensing.*
Copyright (c) 2022 **Moringaschool RPA class**

