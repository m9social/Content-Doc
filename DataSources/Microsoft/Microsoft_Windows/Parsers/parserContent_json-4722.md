#### Parser Content
```Java
{
Name = json-4722
  DataType = "windows-account-enabled"
  Conditions = ["""A user account was enabled""", """computer_name""", """event_id\":4722"""]
  Fields = ${WinParserTemplates.json-windows-events-2.Fields}[
    """({event_name}A user account was enabled)""",
    """TargetUserName\\?"+:\\?"({target_user}[^\\]+)\\?"""",
    """TargetDomainName\\?"+:\\?"({target_domain}[^\\]+)\\?"""",
    """"TargetSid\\?"+:\\?"({target_user_sid}[^\\]+)"""
  ]
}
json-windows-events-2 = {
  Vendor = Microsoft
  Product = Microsoft Windows
  Lms = Direct
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """@timestamp\\?"+:\\?"+({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d+Z)""",
    """(?:winlog\.)?computer_name\\?"+:\\?"+({host}[^\\]+)""",
    """SubjectUserName\\?"+:\\?"+(?:-|(?i)(LOCAL SYSTEM|anonymous logon|LOCAL SERVICE|SYSTEM)|({user}[^\\]+))\\?"""",
    """SubjectUserSid\\?"+:\\?"+({user_sid}[^\\]+)\\?"""",
    """SubjectDomainName\\?"+:\\?"+(|-|NT Service|NT AUTHORITY|({domain}[^\\]+))\\?"""",
    """SubjectLogonId\\?"+:\\?"+({logon_id}[^\\]+)\\?"""",
    """event_id\\?"+:({event_code}\d+)""",
    """ProcessName\\?"+:\\?"+(?:|-|({process}({directory}(?:[^";]+)?[\\\/])?({process_name}[^\\\/":;\s]+?)))\\?"""",
    """WorkstationName\\?"+:\\?"+(?:-|({src_host_windows}[^\s\\]+))\\?"""",
    """Status\\?"+:\\?"+({result_code}[^\\]+)\\?"""",
    """ProcessId\\?"+:\\?"+({process_id}[^:\\]+?)\\?"""",
    """LogonProcessName\\?"+:\\?"+({auth_process}[^\s\\]+)\s*\\?"""",
    """AuthenticationPackageName\\?"+:\\?"+({auth_package}[^\s\\]+)\\?""""
  ]

```