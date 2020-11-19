Vendor: ESET
============
Product: ESET Endpoint Security
-------------------------------
|                                 Use-Case                                  | Activity Types                                                                                                                                                                                                             | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | MITRE TTP                                                                                                                                          | Content                    |
|:-------------------------------------------------------------------------:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Activity Time  and Type<br>- Application Activity<br>- Asset Logon and Access<br>- Critical System Activity<br>- Email Activity<br>- Network zones and Location Access<br>- Security Alert<br>- Service Account Activity |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1066 - T1066<br>T1078 - Valid Accounts<br>T1086 - T1086<br>T1133 - External Remote Services<br> |  - 58 Rules<br> - 9 Models |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | - Email Activity                                                                                                                                                                                                           |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                                                                 |  - 3 Rules<br>             |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | - Application Activity                                                                                                                                                                                                     |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1078 - Valid Accounts<br>                                                                                                                         |  - 13 Rules<br> - 1 Models |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | - Activity Time  and Type<br>- Application Activity<br>- Network zones and Location Access                                                                                                                                 |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                     |  - 7 Rules<br> - 1 Models  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Asset Logon and Access<br>- Endpoint Activity<br>- Process Activity<br>- Security Alert                                                                                                                                  |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1066 - T1066<br>T1078 - Valid Accounts<br>T1086 - T1086<br>T1188 - T1188<br>T1204 - User Execution<br>                                            |  - 16 Rules<br> - 3 Models |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | - Application Activity<br>- Email Activity<br>- Executives<br>- Service Account Activity                                                                                                                                   |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>                      |  - 6 Rules<br> - 1 Models  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Asset Logon and Access<br>- Endpoint Activity<br>- Process Activity<br>- Security Alert                                                                                                                                  |  app-activity<br> -- [eset-scan-activity](../Parsers/parserContent_eset-scan-activity.md)<br><br> authentication-failed<br> -- [eset-domain-user-failed-login](../Parsers/parserContent_eset-domain-user-failed-login.md)<br><br> authentication-successful<br> -- [eset-domain-user-login](../Parsers/parserContent_eset-domain-user-login.md)<br><br> security-alert<br> -- [eset-alert](../Parsers/parserContent_eset-alert.md)<br> -- [leef-eset-security-alert](../Parsers/parserContent_leef-eset-security-alert.md)<br> | T1066 - T1066<br>T1078 - Valid Accounts<br>T1086 - T1086<br>T1188 - T1188<br>T1204 - User Execution<br>                                            |  - 16 Rules<br> - 3 Models |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilage escalation                                                                                                                                          | Defense evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |