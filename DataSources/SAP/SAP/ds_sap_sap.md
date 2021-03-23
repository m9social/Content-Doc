Vendor: SAP
===========
Product: SAP
------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  107  |   53   |     16     |      9      |    9    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | MITRE TTP                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Content                                                                                                      |
|:--------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>T1136.001 - Create Account: Create: Local Account<br>T1550 - Use Alternate Authentication Material<br>T1550.002 - Use Alternate Authentication Material: Pass the Hash<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br> | [<ul><li>68 Rules</li></ul><ul><li>32 Models</li></ul>](Rules_Models/r_m_sap_sap_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1114.003 - Email Collection: Email Forwarding Rule<br>                                                                                                                                                                                                                                                                                                                                  | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_sap_sap_Data_Exfiltration.md)         |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                                                        | [<ul><li>13 Rules</li></ul><ul><li>9 Models</li></ul>](Rules_Models/r_m_sap_sap_Internal_Fraud.md)           |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1018 - Remote System Discovery<br>T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1078.003 - Valid Accounts: Local Accounts<br>T1133 - External Remote Services<br>T1136.001 - Create Account: Create: Local Account<br>T1550 - Use Alternate Authentication Material<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br>                                                                                                                    | [<ul><li>30 Rules</li></ul><ul><li>19 Models</li></ul>](Rules_Models/r_m_sap_sap_Lateral_Movement.md)        |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>                                                                                                                                                                                                                                                                                                                                                                        | [<ul><li>10 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_sap_sap_Malware_Detection.md)        |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1136.001 - Create Account: Create: Local Account<br>                                                                                                                                                                                                                         | [<ul><li>12 Rules</li></ul><ul><li>8 Models</li></ul>](Rules_Models/r_m_sap_sap_Privileged_Activity.md)      |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  account-creation<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-deleted<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-lockout<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> account-unlocked<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> app-activity<br> ↳ [cef-sap-app-activity-2](Parsers/parserContent_cef-sap-app-activity-2.md)<br><br> authentication-failed<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> authentication-successful<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br><br> file-download<br> ↳ [cef-sap-app-activity-3](Parsers/parserContent_cef-sap-app-activity-3.md)<br><br> remote-logon<br> ↳ [cef-sap-app-activity-1](Parsers/parserContent_cef-sap-app-activity-1.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>                                                                                                                                                                                                                                                                                                                                                                        | [<ul><li>10 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_sap_sap_Ransomware_Detection.md)     |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                                                                                                                   | Credential Access                                                                                                                                                                                                                                           | Discovery                                                                    | Lateral Movement                                                                                                                                               | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Create Account](https://attack.mitre.org/techniques/T1136)<br><br>[External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Create Account: Create: Local Account](https://attack.mitre.org/techniques/T1136/001)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Use Alternate Authentication Material: Pass the Hash](https://attack.mitre.org/techniques/T1550/002)<br><br>[Valid Accounts: Local Accounts](https://attack.mitre.org/techniques/T1078/003)<br><br> | [Brute Force](https://attack.mitre.org/techniques/T1110)<br><br>[Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br>[Steal or Forge Kerberos Tickets: Kerberoasting](https://attack.mitre.org/techniques/T1558/003)<br><br> | [Remote System Discovery](https://attack.mitre.org/techniques/T1018)<br><br> | [Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |