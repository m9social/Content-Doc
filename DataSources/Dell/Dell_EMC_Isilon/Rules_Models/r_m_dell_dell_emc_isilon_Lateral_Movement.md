Vendor: Dell
============
### Product: [Dell EMC Isilon](../ds_dell_dell_emc_isilon.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  18   |   10   |     5      |      4      |    4    |

| Event Type    | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| remote-access | <b>T1078 - Valid Accounts</b><br> ↳ <b>DC18-new</b>: Account switch by new user<br><br><b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RA-UH-sZ-F</b>: First remote access to asset from first or abnormal zone<br> ↳ <b>RA-UH-sZ-A</b>: Abnormal remote access to asset from first or abnormal zone<br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user<br> ↳ <b>RLA-UsH-dZ-F</b>: First remote access to zone from new asset<br> ↳ <b>RLA-UsH-dZ-A</b>: Abnormal remote access to zone from new asset<br> ↳ <b>RLA-dZsZ-F</b>: First inter-zone communication from destination to source<br> ↳ <b>RLA-sZdZ-F</b>: First inter-zone communication from source to destination<br> ↳ <b>RLA-sZdZ-A</b>: Abnormal inter-zone communication<br> ↳ <b>RA-UH-CS-NC</b>: Remote access  to a critical system for user with no information<br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>KL-USn-A</b>: Abnormal service to obtain TGTs for user<br><br><b>T1018 - Remote System Discovery</b><br> ↳ <b>A-RLRA-AA-A</b>: Abnormal asset-to-asset remote communication<br> ↳ <b>A-RLRA-ZZ-F</b>: First zone-to-zone communication<br> ↳ <b>A-RLRA-ZZ-A</b>: Abnormal zone-to-zone communication |  • <b>AL-HT-EXEC</b>: Executive Assets<br> • <b>RLA-UAPackage</b>: Windows authentication packages used when connecting to remote hosts<br> • <b>KL-USn</b>: Services to obtain TGTs for user<br> • <b>RA-UH</b>: Assets accessed by this user remotely<br> • <b>RLA-sZdZ</b>: Destination zone communication<br> • <b>RLA-dZsZ</b>: Source zone communication<br> • <b>AL-UsH</b>: Source hosts per User<br> • <b>RLA-UsZ</b>: Source zones for user<br> • <b>A-RLRA-ZZ</b>: Zone to zone communication<br> • <b>A-RLRA-AA</b>: Asset to asset communication |