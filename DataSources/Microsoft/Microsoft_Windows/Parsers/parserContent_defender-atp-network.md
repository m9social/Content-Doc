#### Parser Content
```Java
{
Name = defender-atp-network
  DataType = "network-connection"
  Conditions = [  """"AdvancedHunting-DeviceNetworkEvents"""" , """TimeGenerated""", """TenantId"""]
  Fields = ${MicrosoftParserTemplates.defender-atp-events.Fields}[
]
}
defender-atp-events = {
    Vendor = Microsoft
    Product = Microsoft Defender ATP
    Lms = Splunk
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSZ"
    Fields = [
      """"time":"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d+Z)""",
      """"DeviceName":"({host}[^"]+)""""
      """"LogonType":"({logon_type}[^"]+)"""",
      """"AccountName":"({user}[^"]+)"""",
      """"AccountDomain":"({domain}[^"]+)"""",
      """"InitiatingProcessFileName":"({process_name}[^"]+)"""",
    ]

```