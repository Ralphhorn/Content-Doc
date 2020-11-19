Vendor: Infoblox
================
Product: Infoblox BloxOne
-------------------------
|                              Use-Case                               | Activity Types        | Event Types/Parsers                                                                                                 | MITRE TTP                                                                                | Content        |
|:-------------------------------------------------------------------:| --------------------- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------- |
|    [Malware Detection](../UseCases/usecase_malware_detection.md)    | - Security Operations |  dns-response<br> -- [infoblox-bloxone-dns-response](../Parsers/parserContent_infoblox-bloxone-dns-response.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1071 - Application Layer Protocol<br> |  - 2 Rules<br> |
|             [Phishing](../UseCases/usecase_phishing.md)             | - Security Operations |  dns-response<br> -- [infoblox-bloxone-dns-response](../Parsers/parserContent_infoblox-bloxone-dns-response.md)<br> | T1071 - Application Layer Protocol<br>                                                   |  - 1 Rules<br> |
| [Ransomware Detection](../UseCases/usecase_ransomware_detection.md) | - Security Operations |  dns-response<br> -- [infoblox-bloxone-dns-response](../Parsers/parserContent_infoblox-bloxone-dns-response.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1071 - Application Layer Protocol<br> |  - 2 Rules<br> |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilage escalation | Defense evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                             | Exfiltration                                                                                | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------ |
|                |           |             |                      |                 |                   |           |                  |            | [Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |