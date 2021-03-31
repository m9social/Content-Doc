Vendor: Arbor
=============
Product: Arbor
--------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  14   |   7    |     4      |      1      |    1    |

|                               Use-Case                               | Event Types/Parsers                                                                                    | MITRE TTP                                                                                                | Content                                                                                                  |
|:--------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
|     [Lateral Movement](../../../UseCases/uc_lateral_movement.md)     |  network-connection-failed<br> ↳ [arbor-network-fail](Parsers/parserContent_arbor-network-fail.md)<br> | T1071 - Application Layer Protocol<br>T1090.002 - Proxy: External Proxy<br>T1571 - Non-Standard Port<br> | [<ul><li>11 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_arbor_arbor_Lateral_Movement.md) |
|    [Malware Detection](../../../UseCases/uc_malware_detection.md)    |  network-connection-failed<br> ↳ [arbor-network-fail](Parsers/parserContent_arbor-network-fail.md)<br> | T1071 - Application Layer Protocol<br>T1496 - Resource Hijacking<br>T1571 - Non-Standard Port<br>        | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_arbor_arbor_Malware_Detection.md) |
|             [Phishing](../../../UseCases/uc_phishing.md)             |  network-connection-failed<br> ↳ [arbor-network-fail](Parsers/parserContent_arbor-network-fail.md)<br> | T1071 - Application Layer Protocol<br>                                                                   | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_arbor_arbor_Phishing.md)                                    |
| [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md) |  network-connection-failed<br> ↳ [arbor-network-fail](Parsers/parserContent_arbor-network-fail.md)<br> | T1071 - Application Layer Protocol<br>T1496 - Resource Hijacking<br>                                     | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_arbor_arbor_Ransomware_Detection.md)                        |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                                                                                                                                                                           | Exfiltration | Impact                                                                  |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------- |
|                |           |             |                      |                 |                   |           |                  |            | [Non-Standard Port](https://attack.mitre.org/techniques/T1571)<br><br>[Proxy: External Proxy](https://attack.mitre.org/techniques/T1090/002)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              | [Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br> |