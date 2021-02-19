Vendor: Symantec
================
Product: Symantec Endpoint Protection
-------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  38   |   13   |     5      |      3      |    3    |

|                Use-Case                | Activity Types                                                                                                               | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | MITRE TTP                                                                                                                               | Content                                                                                                                  |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Endpoint Activity</li><li>Executives</li><li>Network Alert</li><li>Process Activity</li><li>Security Alert</li></ul> |  network-alert<br> ↳ [cef-symantec-network-alert](Parsers/parserContent_cef-symantec-network-alert.md)<br> ↳ [symantec-epp-network-alert-2](Parsers/parserContent_symantec-epp-network-alert-2.md)<br> ↳ [symantec-epp-network-alert-1](Parsers/parserContent_symantec-epp-network-alert-1.md)<br> ↳ [symantec-epp-network-alert](Parsers/parserContent_symantec-epp-network-alert.md)<br> ↳ [symantec-epp-network-alert-3](Parsers/parserContent_symantec-epp-network-alert-3.md)<br><br> process-alert<br> ↳ [symantec-security-alert-2](Parsers/parserContent_symantec-security-alert-2.md)<br><br> security-alert<br> ↳ [n-forwarded-cef-symantec-epp-alert](Parsers/parserContent_n-forwarded-cef-symantec-epp-alert.md)<br> ↳ [cef-symantec-sep-alert](Parsers/parserContent_cef-symantec-sep-alert.md)<br> ↳ [symantec-security-alert-3](Parsers/parserContent_symantec-security-alert-3.md)<br> ↳ [symantec-epp-alert](Parsers/parserContent_symantec-epp-alert.md)<br> ↳ [s-symantec-epp-alert](Parsers/parserContent_s-symantec-epp-alert.md)<br> ↳ [symantec-epp-ntp-alert-chinese](Parsers/parserContent_symantec-epp-ntp-alert-chinese.md)<br> ↳ [symantec-epp-ntp-alert](Parsers/parserContent_symantec-epp-ntp-alert.md)<br> ↳ [symantec-epp-alert-chinese](Parsers/parserContent_symantec-epp-alert-chinese.md)<br> ↳ [cef-symantec-sep-alert-1](Parsers/parserContent_cef-symantec-sep-alert-1.md)<br> ↳ [symantec-epp-alert-japanese](Parsers/parserContent_symantec-epp-alert-japanese.md)<br> ↳ [symantec-epp-cef-alert](Parsers/parserContent_symantec-epp-cef-alert.md)<br> ↳ [s-symantec-epp-alert](Parsers/parserContent_s-symantec-epp-alert.md)<br> | T1066 - T1066<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>T1086 - T1086<br>T1204 - User Execution<br> | [<ul><li>38 Rules</li></ul><ul><li>13 Models</li></ul>](Rules_Models/r_m_symantec_symantec_endpoint_protection_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                                                                                                          | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |