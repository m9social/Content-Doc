Vendor: Palo Alto Networks
==========================
### Product: [NGFW](../ds_palo_alto_networks_ngfw.md)
### Use-Case: [Abnormal VPN Access](../../../../UseCases/uc_abnormal_vpn_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   2   |   1    |     1      |     12      |   12    |

| Event Type       | Rules                                                                                                           | Models                                              |
| ---------------- | --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| failed-vpn-login | <b>T1133 - External Remote Services</b><br> ↳ <b>SEQ-UH-15</b>: Failed VPN login                                |                                                     |
| vpn-login        | <b>T1133 - External Remote Services</b><br> ↳ <b>VPN-GsH-F</b>: First VPN connection from device for peer group |  • <b>VPN-GsH</b>: VPN endpoints in this peer group |