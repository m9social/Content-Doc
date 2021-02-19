Vendor: Sophos
==============
### Product: [Sophos Endpoint Protection](../ds_sophos_sophos_endpoint_protection.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   1    |     4      |     10      |   10    |

| Event Type     | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Models                                                              |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| security-alert | <b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                     |
| vpn-logout     | <b>T1078 - Valid Accounts</b><br> ↳ <b>WPA-UACount</b>: Abnormal number of privilege access events for user<br> ↳ <b>APP-UOb-Number</b>: Abnormal number of application objects accessed for user<br><br><b>T1098 - Account Manipulation</b><br> ↳ <b>FDS-UCount</b>: Abnormal number of failed directory service events in the user<br> ↳ <b>DS-Count</b>: Abnormal number of directory service events in the organization<br> ↳ <b>DS-UCount</b>: Abnormal number of directory service events in the user<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>AS-PV-USCOUNT-A</b>: Abnormal number of password safes used by user |  • <b>AS-PV-USCOUNT</b>: Count of safe values accessed in a session |