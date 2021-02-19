Vendor: Symantec
================
Product: Symantec VIP
---------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  55   |   6    |     4      |      4      |    4    |

|                Use-Case                | Activity Types                                                                                                                                                                                                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | MITRE TTP                                                                                                                         | Content                                                                                                 |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-activity<br> ↳ [symantec-app-activity](Parsers/parserContent_symantec-app-activity.md)<br><br> app-activity-failed<br> ↳ [symantec-app-activity](Parsers/parserContent_symantec-app-activity.md)<br><br> authentication-failed<br> ↳ [s-symantec-auth-failed](Parsers/parserContent_s-symantec-auth-failed.md)<br> ↳ [s-symantec-auth-failed-1](Parsers/parserContent_s-symantec-auth-failed-1.md)<br> ↳ [symantec-app-activity](Parsers/parserContent_symantec-app-activity.md)<br><br> authentication-successful<br> ↳ [s-symantec-auth-successful](Parsers/parserContent_s-symantec-auth-successful.md)<br> ↳ [symantec-app-activity](Parsers/parserContent_symantec-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br> | [<ul><li>55 Rules</li></ul><ul><li>6 Models</li></ul>](Rules_Models/r_m_symantec_symantec_vip_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |