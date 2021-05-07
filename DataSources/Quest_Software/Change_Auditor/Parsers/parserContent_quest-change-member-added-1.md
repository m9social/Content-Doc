#### Parser Content
```Java
{
Name = quest-change-member-added-1
     DataType = "member-added"
     Conditions = [ """CEF:""", """Quest Software""", """|Change Auditor|""", """|Active Directory|""", """Member added to group""" ]
     Fields = ${QuestParserTemplates.quest-change-auditor-events.Fields}[
       """msg=[^\\]+\\*({account_id}[^(]+)[^=]+?was added to group\s[^\\]+\\*({group_name}\S+)\s"""
]
}
quest-change-auditor-events = {
    Vendor = Quest Software
    Product = Change Auditor
    Lms = Splunk
    TimeFormat = "MMM dd yyyy HH:mm:ss"
    Fields = [
      """start=({time}\w+\s\d\d\s\d\d\d\d\s\d\d:\d\d:\d\d)""",
      """dvchost=({host}[\w\-.]+)""",
      """domain=({domain}\S+)""",
      """categoryOutcome=({outcome}\S+)""",
      """src=({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})""",
      """userMail=({user_email}[^@=]+@[^\.]+[^\s]+)""",
      """suid=({user_sid}\S+)""",
      """suser=(({domain}[^\\]+)\\*)?({user}[^=]+?)\s\w+=""",
      """event=({event_name}[^=]+?)\s\w+=""",
      """msg=({additional_info}[^=]+?)\s*\w+="""
    ]

```