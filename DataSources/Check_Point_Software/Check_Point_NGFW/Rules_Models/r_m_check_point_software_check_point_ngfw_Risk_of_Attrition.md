Vendor: Check Point Software
============================
### Product: [Check Point NGFW](../ds_check_point_software_check_point_ngfw.md)
### Use-Case: [Risk of Attrition](../../../../UseCases/uc_risk_of_attrition.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   2    |     2      |     10      |   10    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                                            | Models                                                                                                                                           |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| dlp-email-alert-out  | <b>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</b><br> ↳ <b>EM-Competition</b>: Email to competition<br> ↳ <b>EM-Personal-Job</b>: Email with job seeking keywords in subject is sent to personal email address from company email address      |                                                                                                                                                  |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-OU-JS-F</b>: First job search activity for user in the organization<br> ↳ <b>WEB-OU-JS-A</b>: Abnormal job search activity for user in the organization<br> ↳ <b>WEB-OG-JS-F</b>: First job search activity for user in the peer group |  • <b>WEB-OG-JS</b>: Job search activities of users in the peer group<br> • <b>WEB-OU-JS</b>: Job search activities of users in the organization |