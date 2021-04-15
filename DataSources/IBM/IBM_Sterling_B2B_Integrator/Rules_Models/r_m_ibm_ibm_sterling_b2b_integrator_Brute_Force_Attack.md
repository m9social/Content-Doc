Vendor: IBM
===========
### Product: [IBM Sterling B2B Integrator](../ds_ibm_ibm_sterling_b2b_integrator.md)
### Use-Case: [Brute Force Attack](../../../../UseCases/uc_brute_force_attack.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   1    |     3      |      2      |    2    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Models                                                |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| failed-logon | <b>T1021.001 - Remote Services: Remote Desktop Protocol</b><b>T1110 - Brute Force</b><br> ↳ <b>FL-MULTI-USERS-L</b>: Multiple users failed to login (L)<br> ↳ <b>FL-MULTI-USERS-M</b>: Multiple users failed to login (M)<br> ↳ <b>A-FL-MULTI-DEST</b>: Failed logins to multiple destinations from host<br> ↳ <b>FL-MULTI-DEST-M</b>: Failed logins to multiple destinations from host (M)<br> ↳ <b>RDP-Brute-Force</b>: Abnormal number of RDP failed logons for this user |                                                       |
| remote-logon | <b>T1078 - Valid Accounts</b><br> ↳ <b>AS-PV-UHWoPC</b>: Access to Password Vault managed asset with no password checkout for user                                                                                                                                                                                                                                                                                                                                           |  • <b>AS-PV-OA</b>: Password retrieval based accounts |