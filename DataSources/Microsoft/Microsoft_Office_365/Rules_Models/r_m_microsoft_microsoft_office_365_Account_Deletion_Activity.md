Vendor: Microsoft
=================
### Product: [Microsoft Office 365](../ds_microsoft_microsoft_office_365.md)
### Use-Case: [Account Deletion Activity](../../../../UseCases/uc_account_deletion_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   2   |   1    |     2      |     27      |   27    |

| Event Type      | Rules                                                                                                                                                                                                                                                                           | Models                                                               |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| process-created | <b>T1098 - Account Manipulation</b><b>T1531 - Account Access Removal</b><br> ↳ <b>EXE-DELETE-ORG-F</b>: First time net.exe has been used to delete a user account by this user.<br> ↳ <b>EXE-DELETE-ORG-A</b>: Abnormal usage of net.exe to delete a user account by this user. |  • <b>NET-EXE-DELETE-ORG</b>: Using net.exe to delete a user account |