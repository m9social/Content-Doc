Vendor: Zeek
============
### Product: [Zeek Network Security Monitor](../ds_zeek_zeek_network_security_monitor.md)
### Use-Case: [Executive Account Abuse](../../../../UseCases/uc_executive_account_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   2   |   1    |     2      |     24      |   24    |

| Event Type     | Rules                                                                                                                              | Models                                 |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| kerberos-logon | <b>T1078 - Valid Accounts</b><br> ↳ <b>AL-HT-EXEC-new</b>: New user logon to executive asset                                       |  • <b>AL-HT-EXEC</b>: Executive Assets |
| ntlm-logon     | <b>T1078 - Valid Accounts</b><br> ↳ <b>AL-HT-EXEC-new</b>: New user logon to executive asset                                       |  • <b>AL-HT-EXEC</b>: Executive Assets |
| remote-access  | <b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset |  • <b>AL-HT-EXEC</b>: Executive Assets |
| remote-logon   | <b>T1078 - Valid Accounts</b><br> ↳ <b>AL-HT-EXEC-new</b>: New user logon to executive asset                                       |  • <b>AL-HT-EXEC</b>: Executive Assets |