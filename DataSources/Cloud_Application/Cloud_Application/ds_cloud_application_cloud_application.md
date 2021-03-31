Vendor: Cloud Application
=========================
Product: Cloud Application
--------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  33   |   14   |     3      |      3      |    3    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                           | MITRE TTP                                                        | Content                                                                                                                                  |
|:--------------------------------------------------------------------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  account-password-change<br> ↳ [cef-skyformation-password-change](Parsers/parserContent_cef-skyformation-password-change.md)<br><br> app-login<br> ↳ [cef-skyformation-login](Parsers/parserContent_cef-skyformation-login.md)<br> ↳ [cef-skyformation-login-2](Parsers/parserContent_cef-skyformation-login-2.md)<br><br> failed-app-login<br> ↳ [cef-skyformation-failed-login](Parsers/parserContent_cef-skyformation-failed-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | [<ul><li>25 Rules</li></ul><ul><li>12 Models</li></ul>](Rules_Models/r_m_cloud_application_cloud_application_Compromised_Credentials.md) |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          |  account-password-change<br> ↳ [cef-skyformation-password-change](Parsers/parserContent_cef-skyformation-password-change.md)<br><br> app-login<br> ↳ [cef-skyformation-login](Parsers/parserContent_cef-skyformation-login.md)<br> ↳ [cef-skyformation-login-2](Parsers/parserContent_cef-skyformation-login-2.md)<br><br> failed-app-login<br> ↳ [cef-skyformation-failed-login](Parsers/parserContent_cef-skyformation-failed-login.md)<br> | T1078 - Valid Accounts<br>                                       | [<ul><li>4 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_cloud_application_cloud_application_Internal_Fraud.md)            |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  account-password-change<br> ↳ [cef-skyformation-password-change](Parsers/parserContent_cef-skyformation-password-change.md)<br><br> app-login<br> ↳ [cef-skyformation-login](Parsers/parserContent_cef-skyformation-login.md)<br> ↳ [cef-skyformation-login-2](Parsers/parserContent_cef-skyformation-login-2.md)<br><br> failed-app-login<br> ↳ [cef-skyformation-failed-login](Parsers/parserContent_cef-skyformation-failed-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | [<ul><li>4 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_cloud_application_cloud_application_Lateral_Movement.md)          |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  account-password-change<br> ↳ [cef-skyformation-password-change](Parsers/parserContent_cef-skyformation-password-change.md)<br><br> app-login<br> ↳ [cef-skyformation-login](Parsers/parserContent_cef-skyformation-login.md)<br> ↳ [cef-skyformation-login-2](Parsers/parserContent_cef-skyformation-login-2.md)<br><br> failed-app-login<br> ↳ [cef-skyformation-failed-login](Parsers/parserContent_cef-skyformation-failed-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>6 Rules</li></ul>](Rules_Models/r_m_cloud_application_cloud_application_Malware_Detection.md)                                   |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  account-password-change<br> ↳ [cef-skyformation-password-change](Parsers/parserContent_cef-skyformation-password-change.md)<br><br> app-login<br> ↳ [cef-skyformation-login](Parsers/parserContent_cef-skyformation-login.md)<br> ↳ [cef-skyformation-login-2](Parsers/parserContent_cef-skyformation-login-2.md)<br><br> failed-app-login<br> ↳ [cef-skyformation-failed-login](Parsers/parserContent_cef-skyformation-failed-login.md)<br> | T1078 - Valid Accounts<br>                                       | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_cloud_application_cloud_application_Privileged_Activity.md)                                 |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  account-password-change<br> ↳ [cef-skyformation-password-change](Parsers/parserContent_cef-skyformation-password-change.md)<br><br> app-login<br> ↳ [cef-skyformation-login](Parsers/parserContent_cef-skyformation-login.md)<br> ↳ [cef-skyformation-login-2](Parsers/parserContent_cef-skyformation-login-2.md)<br><br> failed-app-login<br> ↳ [cef-skyformation-failed-login](Parsers/parserContent_cef-skyformation-failed-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>6 Rules</li></ul>](Rules_Models/r_m_cloud_application_cloud_application_Ransomware_Detection.md)                                |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |