## Getting Started
This file contains the steps to run and debug this project in a MacOS development environment:

- Download and install dotnet 5 for MacOS.
- Set the environment variable ASPNETCORE_ENVIRONMENT to Development.
- Import the Mock CDR CA cert (Source/CDR.DataRecipient.Web/Certificates/ca.crt) with KeyChain Access from MacOS and set it to Always Trust.
- Update the path for databases and logs in Source/CDR.DataRecipient.Web/appsettings.Development.json (Replace the existint file with Source/CDR.DataRecipient.Web/appsettings.Development.MAC.json).
- Run Source/Start-DataRecipient.sh to start all the sub-projects (you may need to install ttab https://github.com/mklement0/ttab).

