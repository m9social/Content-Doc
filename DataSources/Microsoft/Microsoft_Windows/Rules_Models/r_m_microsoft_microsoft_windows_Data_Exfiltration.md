Vendor: Microsoft
=================
### Product: [Microsoft Windows](../ds_microsoft_microsoft_windows.md)
### Use-Case: [Data Exfiltration](../../../../UseCases/uc_data_exfiltration.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  15   |   6    |     6      |     54      |   54    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Models                                                                                                                                                                   |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| file-delete     | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user                                                                                                                                                                                                                                                                                                                                                                                                                                 |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups |
| file-read       | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user                                                                                                                                                                                                                                                                                                                                                                                                                                 |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups |
| file-write      | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user                                                                                                                                                                                                                                                                                                                                                                                                                                 |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups |
| process-created | <b>T1105 - Ingress Tool Transfer</b><br> ↳ <b>Certutil-Encode</b>: Certutil commands to encode files were used.<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>A-Tap-Installer</b>: TAP software was installed on this asset.<br> ↳ <b>DNS-Exfiltration-Tools-Exec</b>: Well-known DNS Exfiltration tools were executed.<br> ↳ <b>Tap-Installer</b>: TAP software was installed.<br><br><b>T1020 - Automated Exfiltration</b><br> ↳ <b>Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed.<br><br><b>T1175 - T1175</b><br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable. |                                                                                                                                                                          |
| usb-insert      | <b>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB</b><br> ↳ <b>UW-UHD-011</b>: First USB activity event for user. The asset and the USB device (if present) have been seen in other USB events<br> ↳ <b>UW-UHD-110</b>: First USB activity event for USB device. The user and the asset have been seen in other USB events<br> ↳ <b>UW-UH-F</b>: First asset for user in USB event<br> ↳ <b>UW-UH-A</b>: Abnormal asset for user in USB event<br> ↳ <b>UW-UD-A</b>: Abnormal USB device for user<br> ↳ <b>UW-DH-A</b>: Abnormal asset for USB device                                                                                                                            |  • <b>UW-DH</b>: Hosts that were used with USB Device<br> • <b>UW-UD</b>: USB Devices per User<br> • <b>UW-UH</b>: Hosts used with USB Device per User                   |