Vendor: IBM
===========
Product: Lotus Mobile Connect
-----------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  15   |   5    |     3      |      3      |    3    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                             | MITRE TTP                                                        | Content                                                                                                                      |
|:--------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  authentication-failed<br> ↳ [cef-ibm-auth-failed](Parsers/parserContent_cef-ibm-auth-failed.md)<br><br> authentication-successful<br> ↳ [cef-ibm-auth-successful](Parsers/parserContent_cef-ibm-auth-successful.md)<br><br> failed-vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br><br> vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | [<ul><li>12 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_ibm_lotus_mobile_connect_Compromised_Credentials.md) |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  authentication-failed<br> ↳ [cef-ibm-auth-failed](Parsers/parserContent_cef-ibm-auth-failed.md)<br><br> authentication-successful<br> ↳ [cef-ibm-auth-successful](Parsers/parserContent_cef-ibm-auth-successful.md)<br><br> failed-vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br><br> vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_ibm_lotus_mobile_connect_Lateral_Movement.md)         |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  authentication-failed<br> ↳ [cef-ibm-auth-failed](Parsers/parserContent_cef-ibm-auth-failed.md)<br><br> authentication-successful<br> ↳ [cef-ibm-auth-successful](Parsers/parserContent_cef-ibm-auth-successful.md)<br><br> failed-vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br><br> vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_ibm_lotus_mobile_connect_Malware_Detection.md)                                  |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  authentication-failed<br> ↳ [cef-ibm-auth-failed](Parsers/parserContent_cef-ibm-auth-failed.md)<br><br> authentication-successful<br> ↳ [cef-ibm-auth-successful](Parsers/parserContent_cef-ibm-auth-successful.md)<br><br> failed-vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br><br> vpn-login<br> ↳ [lmc-vpn-login](Parsers/parserContent_lmc-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_ibm_lotus_mobile_connect_Ransomware_Detection.md)                               |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |