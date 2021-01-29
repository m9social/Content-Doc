Vendor: Epic
============
Product: Epic
-------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  56   |   6    |     4      |      6      |    6    |

|                                 Use-Case                                  | Activity Types                                                                                                                                                                                                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | MITRE TTP                                                                                                        | Content                                              |
|:-------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | <ul><li>42 Rules</li></ul><ul><li>5 Models</li></ul> |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                         |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                               | <ul><li>3 Rules</li></ul>                            |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                                                   |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1078 - Valid Accounts<br>                                                                                       | <ul><li>13 Rules</li></ul><ul><li>1 Models</li></ul> |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Network zones and Location Access</li></ul>                                                                                                                         |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                   | <ul><li>7 Rules</li></ul><ul><li>1 Models</li></ul>  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1188 - T1188<br>                                                                                                | <ul><li>6 Rules</li></ul>                            |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | <ul><li>Application Activity</li><li>Email Activity</li><li>Service Account Activity</li></ul>                                                                                                                                           |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>                                     | <ul><li>5 Rules</li></ul><ul><li>1 Models</li></ul>  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  account-password-change<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> account-password-change-failed<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br><br> app-activity<br> ↳ [cef-epic-app-activity-11](../Parsers/parserContent_cef-epic-app-activity-11.md)<br> ↳ [cef-epic-app-activity-10](../Parsers/parserContent_cef-epic-app-activity-10.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-activity-6](../Parsers/parserContent_cef-epic-app-activity-6.md)<br> ↳ [cef-epic-app-activity-9](../Parsers/parserContent_cef-epic-app-activity-9.md)<br><br> app-login<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-app-login](../Parsers/parserContent_cef-epic-app-login.md)<br><br> authentication-successful<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> ↳ [cef-epic-auth-successful](../Parsers/parserContent_cef-epic-auth-successful.md)<br><br> failed-app-login<br> ↳ [cef-epic-failed-app-login](../Parsers/parserContent_cef-epic-failed-app-login.md)<br> ↳ [leef-epic-app-activity](../Parsers/parserContent_leef-epic-app-activity.md)<br> | T1188 - T1188<br>                                                                                                | <ul><li>6 Rules</li></ul>                            |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |