Vendor: Microsoft
=================
### Product: [Microsoft Windows](../ds_microsoft_microsoft_windows.md)
### Use-Case: [Abnormal Directory Services Activity](../../../../UseCases/uc_abnormal_directory_services_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  10   |   7    |     3      |     57      |   57    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ds-access       | <b>T1098 - Account Manipulation</b><br> ↳ <b>DS-OU-F</b>: First directory service event for user in the organization<br> ↳ <b>DS-GH-A</b>: Abnormal directory service activity on host for peer group<br> ↳ <b>DS-UH-F</b>: First directory service activity on host for user<br> ↳ <b>DS-OSZ-F</b>: First directory service activity from source zone for organization<br> ↳ <b>DS-GSZ-A</b>: Abnormal directory service activity from source zone for peer group<br> ↳ <b>DS-USZ-F</b>: First directory service activity from source zone for user<br> ↳ <b>DS-USZ-A</b>: Abnormal directory service activity from source zone for user<br> ↳ <b>DS-USH-F</b>: First directory service activity on source host for user |  • <b>DS-USH</b>: Source hosts with directory service activity for user<br> • <b>DS-USZ</b>: Source network zones with directory service activity for the user<br> • <b>DS-GSZ</b>: Source network zones with directory service activity in the peer group<br> • <b>DS-OSZ</b>: Source network zones with directory service activity in the organization<br> • <b>DS-UH</b>: Hosts with directory service activity in the user<br> • <b>DS-GH</b>: Hosts with directory service activity in the peer group<br> • <b>DS-OU</b>: Users with directory service activity in the organization |
| process-created | <b>T1175 - T1175</b><br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable.<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>A-AD-Diagnostic-Tool</b>: Invocation of Active Directory Diagnostic Tool (ntdsutil.exe) on this asset                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |