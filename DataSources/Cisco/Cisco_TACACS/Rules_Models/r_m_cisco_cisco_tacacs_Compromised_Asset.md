Vendor: Cisco
=============
### Product: [Cisco TACACS](../ds_cisco_cisco_tacacs.md)
### Use-Case: [Compromised Asset](../../../../UseCases/uc_compromised_asset.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   2    |     3      |      1      |    1    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Models                                                                                                                                    |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| process-created | <b>T1003.003 - T1003.003</b><br> ↳ <b>PC-Process-Hash-F</b>: First time process path creation with this hash<br> ↳ <b>PC-Process-Hash-A</b>: Abnormal for process path creation with this hash<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>A-Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected on this asset<br> ↳ <b>Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected<br><br><b>T1016 - System Network Configuration Discovery</b><br> ↳ <b>WINCMD-Ipconfig</b>: 'Ipconfig' program used<br> ↳ <b>WINCMD-Route</b>: 'Route' program used<br> ↳ <b>WINCMD-Netsh</b>: 'Netsh' program used |  • <b>PC-Process-Hash</b>: Hashes used to create processes.<br> • <b>A-PC-Process-Hash</b>: Hashes used to create processes on the asset. |