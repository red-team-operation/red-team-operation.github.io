---
layout: page
title: Commands
---

"Disable" "Accounts: Limit local account use of blank passwords to console logon only" 

The policy referenced configures the following registry value:

Registry Hive: HKEY_LOCAL_MACHINE
Registry Path: \System\CurrentControlSet\Control\Lsa

Value Name: LimitBlankPasswordUse

Value Type: REG_DWORD
Value: 0

```
reg.exe add "HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Lsa" /v LimitBlankPasswordUse /t REG_DWORD /d 1
```