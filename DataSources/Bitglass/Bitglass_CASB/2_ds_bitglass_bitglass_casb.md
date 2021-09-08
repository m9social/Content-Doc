|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|          [Data Access](../../../UseCases/uc_data_access.md)          |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>11 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Data_Access.md)        |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1204 - User Execution<br>    | [<ul><li>17 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Data_Exfiltration.md)  |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1204 - User Execution<br> | [<ul><li>44 Rules</li></ul><ul><li>23 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Data_Leak.md)          |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_bitglass_bitglass_casb_Evasion.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1003.002 - T1003.002<br>T1027 - Obfuscated Files or Information<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>T1218.011 - Signed Binary Proxy Execution: Rundll32<br>          | [<ul><li>10 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Malware.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>14 Rules</li></ul><ul><li>7 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Phishing.md)    |
|      [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)      |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Privilege_Abuse.md)      |
|  [Privileged Activity](../../../UseCases/uc_privileged_activity.md)  |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_bitglass_bitglass_casb_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_bitglass_bitglass_casb_Ransomware.md)    |
| [Workforce Protection](../../../UseCases/uc_workforce_protection.md) |  app-login<br> ↳[bitglass-app-login](Ps/pC_bitglassapplogin.md)<br><br> dlp-alert<br> ↳[cef-bitglass-dlp-alert](Ps/pC_cefbitglassdlpalert.md)<br><br> dlp-email-alert-out<br> ↳[bitglass-dlp-email-alert-out](Ps/pC_bitglassdlpemailalertout.md)<br><br> failed-app-login<br> ↳[bitglass-app-login-failed](Ps/pC_bitglassapploginfailed.md)<br> ↳[bitglass-failed-login](Ps/pC_bitglassfailedlogin.md)<br><br> file-download<br> ↳[bitglass-file-download-1](Ps/pC_bitglassfiledownload1.md)<br> ↳[bitglass-file-download](Ps/pC_bitglassfiledownload.md)<br><br> file-read<br> ↳[bitglass-file-read](Ps/pC_bitglassfileread.md)<br><br> file-write<br> ↳[bitglass-file-write](Ps/pC_bitglassfilewrite.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_bitglass_bitglass_casb_Workforce_Protection.md) |