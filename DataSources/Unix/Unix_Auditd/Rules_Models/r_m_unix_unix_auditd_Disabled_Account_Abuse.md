Vendor: Unix
============
### Product: [Unix Auditd](../ds_unix_unix_auditd.md)
### Use-Case: [Disabled Account Abuse](../../../../UseCases/uc_disabled_account_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   2   |   0    |     1      |     16      |   16    |

| Event Type          | Rules                                                                                                             | Models |
| ------------------- | ----------------------------------------------------------------------------------------------------------------- | ------ |
| app-activity-failed | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account     |        |
| file-read           | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account |        |
| file-write          | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account |        |