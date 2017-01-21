# TA-winhostmon-service for Splunk

This CIM compliant TA can be used with Splunk Enterprise Security and provides
field extractions, aliases and tags for WinHostMon://Service logging from a
Splunk Universal Forwarder on Windows.

## Installation

Install this TA on your:

* Splunk (Enterprise Security) search head(s)
* Splunk indexer(s)

Make sure to name it TA-winhostmon-service otherwise ES won't eat it. 

## Configuration

None. This TA expects WinHostMon events to be sourcetyped "WinHostMon" which is the default.
