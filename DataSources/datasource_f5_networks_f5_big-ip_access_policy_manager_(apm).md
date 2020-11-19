Vendor: F5 Networks
===================
Product: F5 BIG-IP Access Policy Manager (APM)
----------------------------------------------
|                                 Use-Case                                  | Activity Types                                                                                                                                                                                    | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | MITRE TTP                                                                                                                                                                                | Content                    |
|:-------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Activity Time  and Type<br>- Application Activity<br>- Asset Logon and Access<br>- Credential Switch Activity<br>- Network zones and Location Access<br>- Privileged Activity<br>- VPN Activity |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1003 - OS Credential Dumping<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>T1208 - T1208<br> |  - 22 Rules<br> - 7 Models |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | - Application Activity<br>- Data Loss Prevention<br>- Email Activity                                                                                                                              |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1078 - Valid Accounts<br>                                                                |  - 7 Rules<br>             |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | - Application Activity                                                                                                                                                                            |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                               |  - 1 Rules<br>             |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | - Asset Logon and Access<br>- Network zones and Location Access                                                                                                                                   |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                                           |  - 3 Rules<br> - 1 Models  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Asset Logon and Access<br>- Email Activity                                                                                                                                                      |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1188 - T1188<br>                                                                                                                      |  - 7 Rules<br>             |
|                [Phishing](../UseCases/usecase_phishing.md)                | - Email Activity                                                                                                                                                                                  |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                                                                                                       |  - 1 Rules<br>             |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | - Application Activity<br>- Credential Switch Activity<br>- Privileged Activity                                                                                                                   |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1003 - OS Credential Dumping<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>                                                                             |  - 6 Rules<br> - 1 Models  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Asset Logon and Access<br>- Email Activity                                                                                                                                                      |  <br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br> -- [cef-f5-vpn-user](../Parsers/parserContent_cef-f5-vpn-user.md)<br> -- [f5-vpn-user-agent](../Parsers/parserContent_f5-vpn-user-agent.md)<br> -- [f5-vpn-username](../Parsers/parserContent_f5-vpn-username.md)<br><br> authentication-failed<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> -- [json-f5-auth-attempt](../Parsers/parserContent_json-f5-auth-attempt.md)<br><br> vpn-login<br> -- [cef-f5-vpn-start](../Parsers/parserContent_cef-f5-vpn-start.md)<br><br> vpn-logout<br> -- [cef-f5-vpn-end](../Parsers/parserContent_cef-f5-vpn-end.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1188 - T1188<br>                                                                                                                      |  - 7 Rules<br>             |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilage escalation                                                                                                                                          | Defense evasion                                                     | Credential Access                                                                                                                          | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                      | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ---------------- | ---------- | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br>[Brute Force](https://attack.mitre.org/techniques/T1110)<br><br> |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Physical Medium](https://attack.mitre.org/techniques/T1052)<br><br> |        |