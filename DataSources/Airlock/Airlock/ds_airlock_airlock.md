Vendor: Airlock
===============
Product: Airlock
----------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  14   |   6    |     5      |      3      |    3    |

|                Use-Case                | Activity Types                                                                                                                                                                                   | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | MITRE TTP                                                                                                                                         | Content                                                                                           |
|:--------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Endpoint Activity</li><li>File Activity</li><li>Network zones and Location Access</li></ul> |  app-activity-failed<br> ↳ [airlock-file-upload-failed](Parsers/parserContent_airlock-file-upload-failed.md)<br> ↳ [airlock-file-download-failed](Parsers/parserContent_airlock-file-download-failed.md)<br><br> failed-app-login<br> ↳ [airlock-login-failed](Parsers/parserContent_airlock-login-failed.md)<br><br> file-write<br> ↳ [airlock-create-folder](Parsers/parserContent_airlock-create-folder.md)<br> ↳ [airlock-rename-folder](Parsers/parserContent_airlock-rename-folder.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1204 - User Execution<br> | [<ul><li>14 Rules</li></ul><ul><li>6 Models</li></ul>](Rules_Models/r_m_airlock_airlock_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery                                                                         | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            |                     |              |        |