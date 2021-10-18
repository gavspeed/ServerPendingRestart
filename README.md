# System Center Operation Manager - SCOM - Server Pending Restart Monitoring Management Pack.



# Background
This management pack was inspired from an existing, and very popular, management pack from David Allen – 'SCOM Pending Reboot Management Pack'. This provides alerting when certain conditions on the monitored server are detected and requires the server to be restarted.
We wanted to build on this idea, but at same time, introduce an enhanced level of monitoring. 

# Overview
A number of scenarios are evaluated to determine whether the target computer is pending a restart. Additionally, each of the scenarios can be overridden to tailor to your monitoring needs. For example, if your only requirement is to determine whether the monitored computer is pending a restart as a result of Windows Update automatic updates, then you simply enable this condition detection via override. 
By default, all condition detections are disabled. You simply enable the condition detections as required using Operations Manager overrides.
