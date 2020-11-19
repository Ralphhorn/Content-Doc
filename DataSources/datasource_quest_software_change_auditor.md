Vendor: Quest Software
======================
Product: Change Auditor
-----------------------
|                                 Use-Case                                  | Activity Types                                                                  | Event Types/Parsers                                                                                                                                                                                                     | MITRE TTP                                                                                                                                             | Content                    |
|:-------------------------------------------------------------------------:| ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Asset Logon and Access<br>- Critical System Activity<br>- Privileged Activity |  ds-access<br> -- [s-quest-directory-access](../Parsers/parserContent_s-quest-directory-access.md)<br><br> failed-ds-access<br> -- [q-quest-directory-access](../Parsers/parserContent_q-quest-directory-access.md)<br> | T1003 - OS Credential Dumping<br>T1068 - Exploitation for Privilege Escalation<br>T1098 - Account Manipulation<br>T1207 - Rogue Domain Controller<br> |  - 12 Rules<br> - 8 Models |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | - Asset Logon and Access                                                        |  ds-access<br> -- [s-quest-directory-access](../Parsers/parserContent_s-quest-directory-access.md)<br><br> failed-ds-access<br> -- [q-quest-directory-access](../Parsers/parserContent_q-quest-directory-access.md)<br> | T1207 - Rogue Domain Controller<br>                                                                                                                   |  - 1 Rules<br>             |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | - Asset Logon and Access<br>- Critical System Activity<br>- Privileged Activity |  ds-access<br> -- [s-quest-directory-access](../Parsers/parserContent_s-quest-directory-access.md)<br><br> failed-ds-access<br> -- [q-quest-directory-access](../Parsers/parserContent_q-quest-directory-access.md)<br> | T1003 - OS Credential Dumping<br>T1068 - Exploitation for Privilege Escalation<br>T1098 - Account Manipulation<br>T1207 - Rogue Domain Controller<br> |  - 13 Rules<br> - 8 Models |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence                                                               | Privilage escalation                                                                       | Defense evasion                                                              | Credential Access                                                          | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| -------------- | --------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
|                |           | [Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br> | [Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Rogue Domain Controller](https://attack.mitre.org/techniques/T1207)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> |           |                  |            |                     |              |        |