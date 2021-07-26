Vendor: Akamai
==============
### Product: [Cloud Akamai](../ds_akamai_cloud_akamai.md)
### Use-Case: [Abnormal Authentication & Access](../../../../UseCases/uc_abnormal_authentication_&_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   4    |     1      |      2      |    2    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Models                                                                                                                                                                                                                                                                                                                                                    |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-UUa-MobileBrowser-F</b>: First activity using this mobile web browser/app for this user to a new domain<br> ↳ <b>WEB-OsUa-MobileBrowser-F</b>: First activity using this mobile web browser for this mobile operating system<br> ↳ <b>WEB-UT-TOW-A</b>: Abnormal day for this user to access the web via the organization<br> ↳ <b>WEB-UZ-F</b>: First web activity for this user in this zone |  • <b>WEB-UZ</b>: Network zones where a user performs web activity from<br> • <b>WEB-UT-TOW</b>: Web activity activity time for user<br> • <b>WEB-OsUa-MobileBrowser-New</b>: Top mobile apps/web browsers being used in the organization for this type of device<br> • <b>WEB-UUa-MobileBrowser-New</b>: Top mobile apps/web browsers being used by user |
| web-activity-denied  | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-UT-TOW-A</b>: Abnormal day for this user to access the web via the organization<br> ↳ <b>WEB-UZ-F</b>: First web activity for this user in this zone                                                                                                                                                                                                                                           |  • <b>WEB-UZ</b>: Network zones where a user performs web activity from<br> • <b>WEB-UT-TOW</b>: Web activity activity time for user                                                                                                                                                                                                                      |