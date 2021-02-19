Vendor: Microsoft
=================
Product: Exchange
-----------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  92   |   15   |     4      |      7      |    7    |

|                Use-Case                | Activity Types                                                                                                                                                                                                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | MITRE TTP                                                                                                                         | Content                                                                                               |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-activity<br> ↳ [s-exchange-app-activity](Parsers/parserContent_s-exchange-app-activity.md)<br><br> app-activity-failed<br> ↳ [s-exchange-app-activity](Parsers/parserContent_s-exchange-app-activity.md)<br><br> dlp-email-alert-in<br> ↳ [exchange-dlp-email-internal](Parsers/parserContent_exchange-dlp-email-internal.md)<br> ↳ [exchange-dlp-email-in-1](Parsers/parserContent_exchange-dlp-email-in-1.md)<br> ↳ [exchange-dlp-email-in-2](Parsers/parserContent_exchange-dlp-email-in-2.md)<br> ↳ [q-exchange-dlp-email-in-1](Parsers/parserContent_q-exchange-dlp-email-in-1.md)<br> ↳ [cef-dlp-email-in](Parsers/parserContent_cef-dlp-email-in.md)<br> ↳ [exchange-dlp-email-in](Parsers/parserContent_exchange-dlp-email-in.md)<br> ↳ [json-exchange-dlp-email-in](Parsers/parserContent_json-exchange-dlp-email-in.md)<br> ↳ [q-exchange-dlp-email-in](Parsers/parserContent_q-exchange-dlp-email-in.md)<br> ↳ [exchange-dlp-email-in-sd](Parsers/parserContent_exchange-dlp-email-in-sd.md)<br><br> dlp-email-alert-in-failed<br> ↳ [cef-dlp-email-in](Parsers/parserContent_cef-dlp-email-in.md)<br> ↳ [exchange-dlp-email-in](Parsers/parserContent_exchange-dlp-email-in.md)<br> ↳ [json-exchange-dlp-email-in](Parsers/parserContent_json-exchange-dlp-email-in.md)<br> ↳ [exchange-dlp-email-in-failed](Parsers/parserContent_exchange-dlp-email-in-failed.md)<br> ↳ [q-exchange-dlp-email-in](Parsers/parserContent_q-exchange-dlp-email-in.md)<br> ↳ [q-exchange-dlp-email-in-1](Parsers/parserContent_q-exchange-dlp-email-in-1.md)<br><br> dlp-email-alert-out<br> ↳ [json-exchange-dlp-email-out](Parsers/parserContent_json-exchange-dlp-email-out.md)<br> ↳ [cef-dlp-email-out](Parsers/parserContent_cef-dlp-email-out.md)<br> ↳ [exchange-dlp-email-out](Parsers/parserContent_exchange-dlp-email-out.md)<br> ↳ [q-exchange-dlp-email-out](Parsers/parserContent_q-exchange-dlp-email-out.md)<br> ↳ [exchange-dlp-email-out-1](Parsers/parserContent_exchange-dlp-email-out-1.md)<br> ↳ [exchange-dlp-email-internal](Parsers/parserContent_exchange-dlp-email-internal.md)<br> ↳ [q-exchange-dlp-email-out-1](Parsers/parserContent_q-exchange-dlp-email-out-1.md)<br> ↳ [exchange-dlp-email-out-sd](Parsers/parserContent_exchange-dlp-email-out-sd.md)<br><br> dlp-email-alert-out-failed<br> ↳ [json-exchange-dlp-email-out](Parsers/parserContent_json-exchange-dlp-email-out.md)<br> ↳ [cef-dlp-email-out](Parsers/parserContent_cef-dlp-email-out.md)<br> ↳ [exchange-dlp-email-out](Parsers/parserContent_exchange-dlp-email-out.md)<br> ↳ [exchange-dlp-email-out-failed](Parsers/parserContent_exchange-dlp-email-out-failed.md)<br> ↳ [q-exchange-dlp-email-out](Parsers/parserContent_q-exchange-dlp-email-out.md)<br> ↳ [q-exchange-dlp-email-out-1](Parsers/parserContent_q-exchange-dlp-email-out-1.md)<br><br> failed-app-login<br> ↳ [q-failed-app-login](Parsers/parserContent_q-failed-app-login.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br> | [<ul><li>92 Rules</li></ul><ul><li>15 Models</li></ul>](Rules_Models/r_m_microsoft_exchange_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |