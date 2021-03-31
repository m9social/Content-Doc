Vendor: Fortinet
================
Product: Fortinet Enterprise Firewall
-------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  99   |   45   |     12     |      6      |    6    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | MITRE TTP                                                                                                                                                                                                                                                                                                           | Content                                                                                                                                    |
|:--------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1133 - External Remote Services<br>                                                                                                                                                                             | [<ul><li>39 Rules</li></ul><ul><li>21 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1071.002 - Application Layer Protocol: File Transfer Protocols<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1114.003 - Email Collection: Email Forwarding Rule<br> | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Data_Exfiltration.md)         |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                          | [<ul><li>13 Rules</li></ul><ul><li>9 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Internal_Fraud.md)           |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1043 - T1043<br>T1046 - Network Service Scanning<br>T1071 - Application Layer Protocol<br>T1078 - Valid Accounts<br>T1090.002 - Proxy: External Proxy<br>T1133 - External Remote Services<br>T1571 - Non-Standard Port<br>                                                                                         | [<ul><li>46 Rules</li></ul><ul><li>24 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Lateral_Movement.md)        |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1071 - Application Layer Protocol<br>T1078 - Valid Accounts<br>T1090.002 - Proxy: External Proxy<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1496 - Resource Hijacking<br>T1571 - Non-Standard Port<br>                                                                                                              | [<ul><li>28 Rules</li></ul><ul><li>12 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Malware_Detection.md)       |
|                [Phishing](../../../UseCases/uc_phishing.md)                |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1071 - Application Layer Protocol<br>                                                                                                                                                                                                                                                                              | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Phishing.md)                                            |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                                                                                                                                                                                                 | [<ul><li>5 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Privileged_Activity.md)       |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  app-activity<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> app-activity-failed<br> ↳ [cef-fortinet-app-activity](Parsers/parserContent_cef-fortinet-app-activity.md)<br><br> computer-logon<br> ↳ [s-fortinet-dhcp](Parsers/parserContent_s-fortinet-dhcp.md)<br><br> netflow-connection<br> ↳ [fortinet-netflow](Parsers/parserContent_fortinet-netflow.md)<br><br> network-connection-failed<br> ↳ [fortios-network-connection-failed](Parsers/parserContent_fortios-network-connection-failed.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br><br> network-connection-successful<br> ↳ [fortios-network-connection-successful](Parsers/parserContent_fortios-network-connection-successful.md)<br> ↳ [fortios-network-connection-1](Parsers/parserContent_fortios-network-connection-1.md)<br> ↳ [cef-fortinet-network-connection](Parsers/parserContent_cef-fortinet-network-connection.md)<br> ↳ [fortinet-network-connection](Parsers/parserContent_fortinet-network-connection.md)<br> | T1071 - Application Layer Protocol<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1496 - Resource Hijacking<br>                                                                                                                                                                                | [<ul><li>11 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_fortinet_fortinet_enterprise_firewall_Ransomware_Detection.md)     |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery                                                                     | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Exfiltration                                                                                                                                                                                                                                         | Impact                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | ----------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [Network Service Scanning](https://attack.mitre.org/techniques/T1046)<br><br> |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Non-Standard Port](https://attack.mitre.org/techniques/T1571)<br><br>[Application Layer Protocol: File Transfer Protocols](https://attack.mitre.org/techniques/T1071/002)<br><br>[Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy: External Proxy](https://attack.mitre.org/techniques/T1090/002)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br> | [Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br> |