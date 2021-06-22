# Azure Sentinel Information Model (ASIM) Process parsers 

This template deploys all ASIM Process parsers. The template is part of the Azure Sentinel Information Mode (ASIM).

The Azure Sentinel Information Mode (ASIM) enables you to use and create source-agnostic content, simplifying your analysis of the data in your Azure Sentinel workspace.

For more information, see:

- [Normalization and the Azure Sentinel Information Model (ASIM)](https://aka.ms/AzSentinelNormalization)
- [Azure Sentinel process events normalization schema reference](https://aka.ms/AzSentinelProcessEventsDoc)



<br>

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://aka.ms/AzSentinelProcessEventsARM)

<br>

This template deploys the following:
* vimProcessEmpty - Empty ASim Process table
* imProcess - Process Events from all normalized process events sources
* imProcessCreate - Process creation Events from all normalized process events sources
* imProcessTerminate - Process termination Events from all normalized process events sources
* vimProcessEventsMicrosft365D - Process events from Microsoft 365 Defender for Endpoints
* vimProcessCreateMicrosftSysmon - Process Creation Events from Sysmon
* vimProcessTermianteMicrosftSysmon - Process Termination Events from Sysmon
* vimProcessCreateMicrosftSecurityEvents - Process Creation Events from Security Events
* vimProcessTerminateMicrosftSecurityEvents - Process Terination Events from Security Events

<br>






