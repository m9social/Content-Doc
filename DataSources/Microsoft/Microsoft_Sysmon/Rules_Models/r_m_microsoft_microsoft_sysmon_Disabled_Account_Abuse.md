Vendor: Microsoft
=================
### Product: [Microsoft Sysmon](../ds_microsoft_microsoft_sysmon.md)
### Use-Case: [Disabled Account Abuse](../../../../UseCases/uc_disabled_account_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   1   |   0    |     1      |      6      |    6    |

| Event Type  | Rules                                                                                                             | Models |
| ----------- | ----------------------------------------------------------------------------------------------------------------- | ------ |
| file-delete | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account |        |
| file-write  | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account |        |