#### Parser Content
```Java
{
Name = microsoft-nps-6274
  Vendor = Microsoft
  Product = Microsoft NPS
  Lms = Direct
  DataType = "windows-nac-failed-logon"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """<EventID>6274</EventID>""", """<Message>Network Policy Server discarded the request for a user.""" ]
  Fields = [
    """SystemTime='({time}\d\d\d\d\-\d\d\-\d\dT\d\d:\d\d:\d\d)""",
    """exabeam_host=([^=]+@\s*)?({host}[\w\-.]+)""",
    """<Computer>({host}[\w\-.]+)""",
    """({event_code}6274)""",
    """'SubjectUserName'>(?:({user_type}host)/)?(({domain}[^\\]+)\\+)?({user}[^<]+)""",
    """'SubjectDomainName'>(?:-|({domain}[^\s\<]+))""",
    """'FullyQualifiedSubjectUserName'>(({domain}[^\\]+)\\+)?(?:-|({user}[^\s\\\<]+))""",
    """'NASIdentifier'>(?:-|({location}[\w\-.]+))""",
    """'AuthenticationProvider'>(?:-|({auth_server}[^\<]+))""",
    """'FullyQualifiedSubjectMachineName'>(?:-|({user_type}.+?))(\/[^\/\s]+)?<""",
    """'NASIPv6Address'>({dest_ip}[a-fA-F:\d.]+)""",
    """'NASIPv4Address'>({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})""",
    """'Reason'>({reason}[^<]+)"""
  ]
}
```