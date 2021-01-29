Vendor: CCURE
=============
Product: CCURE
--------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  51   |   6    |     4      |      3      |    3    |

|                                 Use-Case                                  | Activity Types                                                                                                                                                                                                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | MITRE TTP                                                                                                        | Content                                              |
|:-------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | <ul><li>39 Rules</li></ul><ul><li>5 Models</li></ul> |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                         |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                               | <ul><li>3 Rules</li></ul>                            |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                                                   |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1078 - Valid Accounts<br>                                                                                       | <ul><li>13 Rules</li></ul><ul><li>1 Models</li></ul> |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Badge Access</li><li>Network zones and Location Access</li></ul>                                                                                                    |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                   | <ul><li>7 Rules</li></ul><ul><li>1 Models</li></ul>  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1188 - T1188<br>                                                                                                | <ul><li>3 Rules</li></ul>                            |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | <ul><li>Application Activity</li><li>Email Activity</li><li>Service Account Activity</li></ul>                                                                                                                                           |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>                                     | <ul><li>5 Rules</li></ul><ul><li>1 Models</li></ul>  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  app-activity<br> ↳ [ccure-app-activity](../Parsers/parserContent_ccure-app-activity.md)<br><br> app-login<br> ↳ [ccure-app-login](../Parsers/parserContent_ccure-app-login.md)<br> ↳ [ccure-app-login-1](../Parsers/parserContent_ccure-app-login-1.md)<br><br> failed-physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br><br> physical-access<br> ↳ [q-ccure-badge-access](../Parsers/parserContent_q-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-1](../Parsers/parserContent_cef-ccure-badge-access-1.md)<br> ↳ [ccure-badge-access-3](../Parsers/parserContent_ccure-badge-access-3.md)<br> ↳ [cef-ccure-badge-access](../Parsers/parserContent_cef-ccure-badge-access.md)<br> ↳ [cef-ccure-badge-access-2](../Parsers/parserContent_cef-ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-2](../Parsers/parserContent_ccure-badge-access-2.md)<br> ↳ [ccure-badge-access-1](../Parsers/parserContent_ccure-badge-access-1.md)<br> ↳ [s-ccure-badge-access](../Parsers/parserContent_s-ccure-badge-access.md)<br> ↳ [ccure-badge-access](../Parsers/parserContent_ccure-badge-access.md)<br> | T1188 - T1188<br>                                                                                                | <ul><li>3 Rules</li></ul>                            |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |