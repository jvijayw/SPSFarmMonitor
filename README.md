# SPSFarmMonitor

## About
SPSFarmMonitor is a PowerShell-scripted tool to display Performance Counter Metrics of a group of servers. We wrote and tested this predominannty for servers in a SharePoint farm. This tool is a contribution from the engineers of the SharePoint and Project Server support teams at Microsoft.

## Purpose
At Microsoft Support, we come across numerous customers opening support cases raising issues with overall farm performance. While the scope of Performance is broad and includes multiple aspects, vital data isn't available for data analysis. The purpose of this tool is to enable administrators observe live Performance data collated from all servers in one unified HTML dashboard.

![Sample Screenshot](url)

## Usage
SPSFarmMonitor is available for download from https://github.com/jvijayw/SPSFarmMonitor/releases. You can download the contents in a ZIP file and extract it to a location on your desktop PC. You will need to edit the SPSFM.ps1 script to include server names you want to capture performance data. Running SPSFM.ps1 should commence data capture and open the HTML dashboard for viewing.

## Pre-requisites
SPSFarmMonitor can be run from any Windows 10 computer on the network. The preferred HTML5 compliant browser is Microsoft's Chromium Edge. The tool has been tested in Chromium Edge and so we know it works well in Edge.
