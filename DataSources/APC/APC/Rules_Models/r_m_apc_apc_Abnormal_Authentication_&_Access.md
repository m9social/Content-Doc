Vendor: APC
===========
### Product: [APC](../ds_apc_apc.md)
### Use-Case: [Abnormal Authentication & Access](../../../../UseCases/uc_abnormal_authentication_&_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  18   |   11   |     4      |      2      |    2    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| remote-logon | <b>T1078 - Valid Accounts</b><br> ↳ <b>A-AL-DhU-A</b>: Abnormal user per asset<br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>NEW-USER-F</b>: User with no event history<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-A</b>: Abnormal activity from country for user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RL-UH-sZ-F</b>: First remote logon to asset from new or abnormal source network zone<br> ↳ <b>RL-UH-sZ-A</b>: Abnormal remote logon to asset from new or abnormal source network zone<br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user<br> ↳ <b>RLA-dZsZ-F</b>: First inter-zone communication from destination to source<br> ↳ <b>RLA-sZdZ-F</b>: First inter-zone communication from source to destination<br> ↳ <b>RLA-sZdZ-A</b>: Abnormal inter-zone communication<br> ↳ <b>RL-HU-F-new</b>: Remote logon to private asset for new user<br><br><b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-GC-F</b>: First activity from country for group<br> ↳ <b>UA-OC-F</b>: First activity from country for organization<br><br><b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>AL-HLocU-F</b>: First local user logon to this asset |  • <b>RL-HU</b>: Remote logon users<br> • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer group<br> • <b>UA-UC</b>: Countries for user<br> • <b>AE-UA</b>: All activity for users<br> • <b>RLA-sZdZ</b>: Destination zone communication<br> • <b>RLA-dZsZ</b>: Source zone communication<br> • <b>RLA-UsZ</b>: Source zones for user<br> • <b>RL-UH</b>: Remote logons<br> • <b>NKL-HU</b>: Users logging into this host remotely<br> • <b>A-AL-DhU</b>: Users per Host |