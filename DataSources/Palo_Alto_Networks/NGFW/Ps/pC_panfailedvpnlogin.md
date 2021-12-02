#### Parser Content
```Java
{
Name = pan-failed-vpn-login
  DataType = "failed-vpn-login"
  Conditions = [ """"LogType":"GLOBALPROTECT"""", """"DeviceSN":"""", """"EventStatus":"failure"""" ]

paloalto-vpn = {
  Vendor = Palo Alto Networks
  Product = NGFW
  Lms = Direct
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSZ"
  Fields = [
    """"TimeGenerated":"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{1,9}Z)""",
    """"host":"({host}[^"]{1,2000})"""",
    """"DeviceName":"({host}[^"\s]{1,2000})"""",
    """"PrivateIPv(4|6)":"({src_ip}[a-fA-F\d:.]{1,2000})""",
    """"PublicIPv(4|6)":"({dest_ip}[a-fA-F\d.:]{1,2000})""",
    """"SourceAddress":"({src_ip}[a-fA-F\d:.]{1,2000})""",
    """"DestinationAddress":"({dest_ip}[a-fA-F\d:.]{1,2000})""",
    """"(Source)?User(Name)?":"((na|NA|({domain}[^"\\]{1,2000}))\\{1,20})?({user}[^"]{1,2000})"""",
    """"SourcePort":({src_port}\d{1,100})""",
    """"DestinationPort":({dest_port}\d{1,100})""",
    """"Protocol":"({protocol}[^"]{1,2000})"""",
  
}
```