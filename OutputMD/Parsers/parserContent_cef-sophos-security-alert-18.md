#### Parser Content
```Java
{
Name = cef-sophos-security-alert-18
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::WebControlViolation""" ]
  Fields=${SophosParserTemplates.cef-sophos-security-alert-1.Fields}[
    """"name"*:\s*"*'({malware_url}[^"\'\s]+)'\s+blocked due to""",
    """"name"*:"*'({alert_name}[^"]+)\s"""
  ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-20
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::UserAutoCreated""" ]
   Fields=${SophosParserTemplates.cef-sophos-security-alert-1.Fields}[
    """"name"*:"*({alert_name}[^":]+)"""
  ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-21
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::UpdateSuccess""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-22
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::UpdateFailure""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-23
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::ServiceRestored""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-24
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::ServiceNotRunning""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-25
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::SavEnabled""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-26
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::SavDisabled""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-27
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::Device::AlertedOnly""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-28
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::Denc::EncryptionSuspendedEvent""" ]
}
${SophosParserTemplates.cef-sophos-security-alert-1} {
  Name = cef-sophos-security-alert-29
  Conditions = [ """CEF:""", """ext_type=Event::Endpoint::Application::Detected""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-dlp-alert-1
  Conditions = [ """CEF:""", """"Event::Endpoint::WindowsFirewall::Blocked"""", """"group":"ENDPOINT_FIREWALL"""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-security-alert-32
  DataType = "alert"
  Conditions = [ """CEF:""", """"Event::Endpoint::CorePua""", """"group":"PUA"""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-dlp-alert-8
  Conditions = [ """CEF:""", """"Event::Endpoint::Core""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-dlp-alert-9
  Conditions = [ """CEF:""", """"Event::Endpoint::Enc::""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-dlp-alert-10
  Conditions = [ """CEF:""", """"Event::Endpoint::HmpaCryptoGuard""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-dlp-alert-11
  Conditions = [ """CEF:""", """"Event::Endpoint::Registered""" ]
}

${SophosParserTemplates.cef-sophos-dlp-alert-1}{
  Name = cef-sophos-dlp-alert-12
  Conditions = [ """CEF:""", """"Event::Endpoint::Reprotected""" ]
}

{
  Name = cef-sophos-dlp-alert-13
  Vendor = Sophos
  Product = Sophos Endpoint Protection
  Lms = ArcSight
  DataType = "dlp-alert"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Conditions = [  """CEF:""", """Event::Endpoint::DataLossPreventionAutomaticallyAllowed""", """group=DATA_LOSS_PREVENTION""" ]
  Fields = [
    """exabeam_host=([^=]+@\s*)?({host}[^\s]+)""",
    """"location":"({host}[\w\-.]+)"""",
    """({host}[\w\-.]+)\s+Skyformation""",
    """"when":"({time}\d\d\d\d\-\d\d\-\d\dT\d\d:\d\d:\d\d\.\d\d\dZ)""",
    """"type":"({alert_type}Event[^"]+)""",
    """"severity":"({alert_severity}[^"]+)""",
    """"id":"({alert_id}[^"]+)""",
    """"location":"({src_host}[^"]+)""",
    """"name":\s*"({alert_name}.+?)\s+(\w+:)"""
    """"name":\s*"({additional_info}[^"]+)"""
    """"name".+?Username:\s*(({domain}[^\\]+)\\+)?({user}[^\s\\]+)\s""",
    """"name".+?Rule names:\s*′({rule}[^′]+)""",
    """"name".+?User action:\s*({activity}.+?)\s+(\w+\s+\w+:)""",
    """"name".+?Application Name:\s+({app}.+?)\s+Data Control action:""",
    """"name".+?Data Control action:\s*({outcome}[^\s]+)\s""",
    """"name".+?File type:\s*({file_type}.+?)\s+File size:\s*({bytes}\d+)\s""",
    """"name".+?Source path:\s*({target}.+?)\s*(\w+\s+\w+:|")"""
  ]
}

{
  Name = cef-sophos-usb-insert-1
  Vendor = Sophos
  Product = Sophos Endpoint Protection
  Lms = ArcSight
  DataType = "usb-insert"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Conditions = [ """CEF:""", """"Event::Endpoint::Device::AlertedOnly"""", """"Peripheral allowed:""" ]
  Fields = [
    """exabeam_host=([^=]+@\s*)?({host}[^\s]+)""",
    """"location":"({host}[\w\-.]+)"""",
    """"when":"({time}\d\d\d\d\-\d\d\-\d\dT\d\d:\d\d:\d\d\.\d\d\dZ)""",
    """"type":"({additional_info}[^"]+)""",
    """"name":"({activity_details}({activity}Peripheral allowed):\s*({device_type}[^"]+))""",
    """"source":"(n\/a|({user_fullname}[^"\\\(\),]+))"""",
    """"source":"(n\/a|({user_lastname}[^",\s]+),\s*({user_firstname}[^,"\s]+))""",
    """"source":"(n\/a|(([^\\\s"]*\s+[^\\"]*|({domain}[^\\"]+))\\+)?({user}[^\\\s"]+))"""",
  ]
}
```