Vendor: RSA
===========
Product: RSA
------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  27   |   1    |     5      |      1      |    1    |

|                Use-Case                | Activity Types                                                 | Event Types/Parsers                                                                                     | MITRE TTP                                                                                                                                                      | Content                                                         |
|:--------------------------------------:| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Netflow</li><li>Network</li><li>Web Activity</li></ul> |  netflow-connection<br> ↳ [rsa-netflow-connection](Parsers/parserContent_rsa-netflow-connection.md)<br> | T1043 - T1043<br>T1046 - Network Service Scanning<br>T1048 - Exfiltration Over Alternative Protocol<br>T1065 - T1065<br>T1071 - Application Layer Protocol<br> | [<ul><li>27 Rules</li></ul>](Rules_Models/r_m_rsa_rsa_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery                                                                     | Lateral Movement | Collection | Command and Control                                                             | Exfiltration                                                                                | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | ----------------------------------------------------------------------------- | ---------------- | ---------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------ |
|                |           |             |                      |                 |                   | [Network Service Scanning](https://attack.mitre.org/techniques/T1046)<br><br> |                  |            | [Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |