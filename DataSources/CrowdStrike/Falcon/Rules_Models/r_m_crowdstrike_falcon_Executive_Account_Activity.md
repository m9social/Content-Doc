Vendor: CrowdStrike
===================
### Product: [Falcon](../ds_crowdstrike_falcon.md)
### Use-Case: [Executive Account Activity](../../../../UseCases/uc_executive_account_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   1    |     6      |     27      |   27    |

| Event Type     | Rules                                                                                                                                                                                                                                                   | Models                                 |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| app-activity   | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user                                                                                    |                                        |
| local-logon    | <b>T1078 - Valid Accounts</b><br> ↳ <b>AL-HT-EXEC-new</b>: New user logon to executive asset                                                                                                                                                            |  • <b>AL-HT-EXEC</b>: Executive Assets |
| remote-access  | <b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br><br><b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive |  • <b>AL-HT-EXEC</b>: Executive Assets |
| remote-logon   | <b>T1078 - Valid Accounts</b><br> ↳ <b>AL-HT-EXEC-new</b>: New user logon to executive asset<br><br><b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive                                       |  • <b>AL-HT-EXEC</b>: Executive Assets |
| security-alert | <b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive                                                                                                                                           |                                        |
| task-created   | <b>T1053.005 - Scheduled Task/Job: Scheduled Task</b><b>T1543.003 - Create or Modify System Process: Windows Service</b><br> ↳ <b>WTC-HT-EXEC</b>: Non-Executive user created a scheduled task/service on executive asset                               |  • <b>AL-HT-EXEC</b>: Executive Assets |