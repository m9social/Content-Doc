Vendor: Arbor
=============
Product: Arbor
--------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  12   |   1    |     2      |      1      |    1    |

|                Use-Case                | Activity Types                                 | Event Types/Parsers                                                                                    | MITRE TTP                                               | Content                                                             |
|:--------------------------------------:| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Network</li><li>Web Activity</li></ul> |  network-connection-failed<br> ↳ [arbor-network-fail](Parsers/parserContent_arbor-network-fail.md)<br> | T1065 - T1065<br>T1071 - Application Layer Protocol<br> | [<ul><li>12 Rules</li></ul>](Rules_Models/r_m_arbor_arbor_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                             | Exfiltration | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------------------------------------------------------------------- | ------------ | ------ |
|                |           |             |                      |                 |                   |           |                  |            | [Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> |              |        |