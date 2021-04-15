Vendor: HP
==========
### Product: [HP](../ds_hp_hp.md)
### Use-Case: [Abnormal Remote Access](../../../../UseCases/uc_abnormal_remote_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   4    |     2      |      2      |    2    |

| Event Type  | Rules                                                                                                                                                                                                                                                                                                                                                                                                                        | Models                                                                                                                                                                                  |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| local-logon | <b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>AL-HLocU-F</b>: First local user logon to this asset<br> ↳ <b>LL-GH-A-new</b>: Abnormal local logon to asset for group by new user<br> ↳ <b>LL-HU-F-new</b>: Local logon to private asset for new user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>A-AL-DhU-A</b>: Abnormal user per asset<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session |  • <b>LL-HU</b>: Local logon users<br> • <b>LL-GH</b>: Local logon hosts (peer groups)<br> • <b>NKL-HU</b>: Users logging into this host remotely<br> • <b>A-AL-DhU</b>: Users per Host |