Vendor: AssetView
=================
Product: AssetView
------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  37   |   12   |     7      |      5      |    5    |

|                Use-Case                | Activity Types                                                                                                                                                                             | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | MITRE TTP                                                                                                                                                                                                                    | Content                                                                                                |
|:--------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Critical System Activity</li><li>Data Loss Prevention</li><li>Endpoint Activity</li><li>Executives</li><li>File Activity</li><li>Process Activity</li><li>Security Alert</li></ul> |  file-download<br> ↳ [assetview-file-download-activity](Parsers/parserContent_assetview-file-download-activity.md)<br><br> file-write<br> ↳ [assetview-file-write](Parsers/parserContent_assetview-file-write.md)<br><br> print-activity<br> ↳ [assetview-print-activity](Parsers/parserContent_assetview-print-activity.md)<br><br> security-alert<br> ↳ [assetview-security-alert](Parsers/parserContent_assetview-security-alert.md)<br><br> usb-insert<br> ↳ [assetview-usb-activity](Parsers/parserContent_assetview-usb-activity.md)<br> | T1052 - Exfiltration Over Physical Medium<br>T1066 - T1066<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1086 - T1086<br>T1204 - User Execution<br> | [<ul><li>37 Rules</li></ul><ul><li>12 Models</li></ul>](Rules_Models/r_m_assetview_assetview_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                                                                                                          | Defense Evasion                                                     | Credential Access | Discovery                                                                         | Lateral Movement | Collection | Command and Control | Exfiltration                                                                           | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ------------------- | -------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            |                     | [Exfiltration Over Physical Medium](https://attack.mitre.org/techniques/T1052)<br><br> |        |