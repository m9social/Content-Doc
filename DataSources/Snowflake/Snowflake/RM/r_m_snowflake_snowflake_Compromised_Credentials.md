Vendor: Snowflake
=================
### Product: [Snowflake](../ds_snowflake_snowflake.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  11   |   7    |     2      |      3      |    3    |

| Event Type | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| file-write | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-UA-UI-F</b>: First file activity from ISP<br> ↳ <b>FA-UA-UC-A</b>: Abnormal file activity from country for user<br> ↳ <b>FA-UA-GC-F</b>: First file activity from country for group<br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1003.003 - T1003.003</b><br> ↳ <b>A-NTDS-Access-F</b>: The NTDS database was accessed from a new location on this asset.<br> ↳ <b>A-NTDS-Access-A</b>: The NTDS database was accessed from a non default location on this asset.<br> ↳ <b>A-NTDS-Access</b>: The NTDS database was accessed from a non default location without 'ntds.dit' in the file path on this asset.<br> ↳ <b>A-NTDS-Shadow-Copy1</b>: The NTDS database changed location to a shadowcopy using 'ntds.dit' and 'harddiskvolumeshadowcopy' in the file path on this asset.<br> ↳ <b>A-NTDS-Shadow-Copy2</b>: The NTDS database changed location to a shadowcopy using 'harddiskvolumeshadowcopy' in the file path on this asset. |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups<br> • <b>FA-UA-GC</b>: Countries for peer groups file activities<br> • <b>FA-UA-UC</b>: Countries for user file activity<br> • <b>FA-UA-UI-new</b>: ISP of users during file activity<br> • <b>A-NTDS-Access</b>: Models the amount of accesses to paths that are related to NTDS |