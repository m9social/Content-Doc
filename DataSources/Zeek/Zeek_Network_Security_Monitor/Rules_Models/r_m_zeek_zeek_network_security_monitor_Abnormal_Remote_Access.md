Vendor: Zeek
============
### Product: [Zeek Network Security Monitor](../ds_zeek_zeek_network_security_monitor.md)
### Use-Case: [Abnormal Remote Access](../../../../UseCases/uc_abnormal_remote_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  36   |   19   |     8      |     24      |   24    |

| Event Type     | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| failed-logon   | <b>T1021.001 - Remote Services: Remote Desktop Protocol</b><b>T1110 - Brute Force</b><br> ↳ <b>FL-MULTI-USERS-L</b>: Multiple users failed to login (L)<br> ↳ <b>FL-MULTI-USERS-M</b>: Multiple users failed to login (M)<br> ↳ <b>A-FL-MULTI-DEST</b>: Failed logins to multiple destinations from host<br> ↳ <b>FL-MULTI-DEST-M</b>: Failed logins to multiple destinations from host (M)<br> ↳ <b>RDP-Brute-Force</b>: Abnormal number of RDP failed logons for this user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| kerberos-logon | <b>T1078 - Valid Accounts</b><br> ↳ <b>A-AL-DhU-A</b>: Abnormal user per asset<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  • <b>A-AL-DhU</b>: Users per Host                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ntlm-logon     | <b>T1078 - Valid Accounts</b><br> ↳ <b>A-AL-DhU-A</b>: Abnormal user per asset<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br><br><b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>AL-HLocU-F</b>: First local user logon to this asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |  • <b>NKL-HU</b>: Users logging into this host remotely<br> • <b>A-AL-DhU</b>: Users per Host                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| remote-access  | <b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RA-UH-sZ-F</b>: First remote access to asset from first or abnormal zone<br> ↳ <b>RA-UH-sZ-A</b>: Abnormal remote access to asset from first or abnormal zone<br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user<br> ↳ <b>RLA-UsH-dZ-F</b>: First remote access to zone from new asset<br> ↳ <b>RLA-UsH-dZ-A</b>: Abnormal remote access to zone from new asset<br> ↳ <b>RLA-dZsZ-F</b>: First inter-zone communication from destination to source<br> ↳ <b>RLA-sZdZ-F</b>: First inter-zone communication from source to destination<br> ↳ <b>RLA-sZdZ-A</b>: Abnormal inter-zone communication<br> ↳ <b>RA-UH-CS-NC</b>: Remote access  to a critical system for user with no information<br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1018 - Remote System Discovery</b><br> ↳ <b>A-RLRA-AA-A</b>: Abnormal asset-to-asset remote communication<br> ↳ <b>A-RLRA-ZZ-F</b>: First zone-to-zone communication<br> ↳ <b>A-RLRA-ZZ-A</b>: Abnormal zone-to-zone communication                                                                                                                                                                         |  • <b>AL-HT-EXEC</b>: Executive Assets<br> • <b>RLA-UAPackage</b>: Windows authentication packages used when connecting to remote hosts<br> • <b>RA-UH</b>: Assets accessed by this user remotely<br> • <b>RLA-sZdZ</b>: Destination zone communication<br> • <b>RLA-dZsZ</b>: Source zone communication<br> • <b>AL-UsH</b>: Source hosts per User<br> • <b>RLA-UsZ</b>: Source zones for user<br> • <b>A-RLRA-ZZ</b>: Zone to zone communication<br> • <b>A-RLRA-AA</b>: Asset to asset communication                                                                       |
| remote-logon   | <b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>A-AL-DhU-A</b>: Abnormal user per asset<br> ↳ <b>RL-UH-sZ-F</b>: First remote logon to asset from new or abnormal source network zone<br> ↳ <b>RL-UH-sZ-A</b>: Abnormal remote logon to asset from new or abnormal source network zone<br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user<br> ↳ <b>RLA-UsH-dZ-F</b>: First remote access to zone from new asset<br> ↳ <b>RLA-UsH-dZ-A</b>: Abnormal remote access to zone from new asset<br> ↳ <b>RLA-dZsZ-F</b>: First inter-zone communication from destination to source<br> ↳ <b>RLA-sZdZ-F</b>: First inter-zone communication from source to destination<br> ↳ <b>RLA-sZdZ-A</b>: Abnormal inter-zone communication<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>RL-HU-F-new</b>: Remote logon to private asset for new user<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>AL-HLocU-F</b>: First local user logon to this asset<br><br><b>T1018 - Remote System Discovery</b><br> ↳ <b>A-RLRA-AA-A</b>: Abnormal asset-to-asset remote communication<br> ↳ <b>A-RLRA-ZZ-F</b>: First zone-to-zone communication<br> ↳ <b>A-RLRA-ZZ-A</b>: Abnormal zone-to-zone communication |  • <b>RL-HU</b>: Remote logon users<br> • <b>RLA-UAPackage</b>: Windows authentication packages used when connecting to remote hosts<br> • <b>RLA-sZdZ</b>: Destination zone communication<br> • <b>RLA-dZsZ</b>: Source zone communication<br> • <b>AL-UsH</b>: Source hosts per User<br> • <b>RLA-UsZ</b>: Source zones for user<br> • <b>RL-UH</b>: Remote logons<br> • <b>NKL-HU</b>: Users logging into this host remotely<br> • <b>A-RLRA-ZZ</b>: Zone to zone communication<br> • <b>A-RLRA-AA</b>: Asset to asset communication<br> • <b>A-AL-DhU</b>: Users per Host |
| share-access   | <b>T1021.002 - Remote Services: SMB/Windows Admin Shares</b><br> ↳ <b>A-SA-OU-F</b>: First admin share access to asset for this user in the organization<br> ↳ <b>A-SA-ZH-A</b>: Abnormal admin share on asset for zone<br> ↳ <b>A-SA-AsU-F</b>: First access of admin share on asset<br> ↳ <b>SA-OU-F</b>: First admin share access for user in the organization<br> ↳ <b>SA-OU-A</b>: Abnormal admin share access for user in the organization<br> ↳ <b>SA-OH-F</b>: First admin share on this host<br> ↳ <b>SA-OH-A</b>: Abnormal admin share on this host<br> ↳ <b>SA-AsU-F</b>: First access of admin share on this host<br> ↳ <b>SA-AsU-A</b>: Abnormal access of admin share on this host                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |  • <b>SA-AsU</b>: Users accessing this Admin share<br> • <b>SA-OH</b>: Assets on which admin share is accessed in organization<br> • <b>SA-OU</b>: Users accessing admin share in the organization<br> • <b>A-SA-AsU</b>: Users per Admin share<br> • <b>A-SA-ZH</b>: Dest zones on which admin shares are accessed<br> • <b>A-SA-OU</b>: Admin Share users in organization                                                                                                                                                                                                   |