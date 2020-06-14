---
unique-page-id: 11382829
description: Marketo Outlook Plugin Uninstall by IT - Marketo Docs - Product Documentation
title: Marketo Outlook Plugin Uninstall by IT
---

# Marketo Outlook Plugin Uninstall by IT {#marketo-outlook-plugin-uninstall-by-it}

Marketo Outlook Plugin Uninstall by IT - Marketo Docs - Product Documentation

Here's how IT can uninstall the Marketo Outlook Plugin remotely.

Run the following command line as the as as ‘System’ or an Administrative user account with the /x switch to uninstall.
`<pre>msiexec.exe /x [File Name] /qn&nbsp;</pre>`  

>[!NOTE]
>
>**Example**
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn&nbsp;</pre>`

For troubleshooting you can enable logging to create an output log file.  `<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`  

>[!NOTE]
>
>**Example**
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

To specify a location of the log files, you can specify the file path in the command line.  `<pre>msiexec.exe /x&nbsp;[File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`  

>[!NOTE]
>
>**Example**
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>Uninstalling the plugin remotely will forcefully close Outlook on the user’s machine.

Please refer [Microsoft’s complete list of switches](https://support.microsoft.com/en-us/kb/227091) if you would like to try different logging levels or user interface levels. 