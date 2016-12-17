# tableau_script_server
Web service that allows for arbitrary script languages in Tableau, publishing of proprietary analytics, etc.

Tableau Desktop can use a remote scripting engine running as a web service to execute python code provided to the service from the application.  While this is a completely awful idea from a security point of view, we can abuse the capability to create new scripting languages (or domain-specific languages) that can manipulate data provided by Tableau Desktop to our web service.  This project aims to create a generic framework for this purpose.
