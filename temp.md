---
layout: page
title: Commands
---

If the value for "Accounts: Limit local account use of blank passwords to console logon only" is not set to "Enabled", this is a finding.

The policy referenced configures the following registry value:

Registry Hive: HKEY_LOCAL_MACHINE
Registry Path: \System\CurrentControlSet\Control\Lsa

Value Name: LimitBlankPasswordUse

Value Type: REG_DWORD
Value: 1