Vendor: F5
==========
### Product: [F5 Advanced Web Application Firewall (WAF)](../ds_f5_f5_advanced_web_application_firewall_(waf).md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   0    |     3      |      6      |    6    |

| Event Type                 | Rules                                                                                                                                                                                                                                                                                                                                        | Models |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| dlp-email-alert-in-failed  | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account                                                                                                                                                                                                                                |        |
| dlp-email-alert-out        | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account                                                                                                                                                                                                                                |        |
| dlp-email-alert-out-failed | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account                                                                                                                                                                                                                                |        |
| process-created            | <b>T1482 - Domain Trust Discovery</b><br> ↳ <b>A-Trickbot-Recon</b>: Trickbot malware domain recon activity on this asset<br> ↳ <b>Trickbot-Recon</b>: Trickbot malware domain recon activity<br><br><b>T1059.003 - T1059.003</b><br> ↳ <b>EPA-OH-CS</b>: First execution of critical windows command on a Domain Controller/Critical System |        |