SplunkWinLogon
==============

Example app on how to measure Windows logon performance

App Installation
================

Copy SplunkWinLogon to $SPLUNK_HOME/etc/apps on your Splunk server.

Addon (TA) Installation
=======================

1. Install the Splunk Universal Forwarder on the systems you want to monitor.
2. Copy $SPLUNK_HOME/etc/apps/SplunkWinLogon/appserver/addons/TA-WinLogon to $SPLUNK_HOME/etc/apps/TA-WinLogon

The final folder structre should look like this:

    C:\

        Program Files\

            SplunkUniversalForwarder\
            
                etc\
                
                    apps\
                    
                        TA-WinLogon