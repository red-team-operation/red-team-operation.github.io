---
description: |
  Description here

  Command Reference:

  	Command Reference here

command: | server
  chisel server --port 8000 --reverse

command: | client
  chisel.exe client 10.10.14.7:9999 9999:localhost:443
  chisel client 192.168.119.124:9999 8081:127.0.0.1:80


attack_types:
  - Pivot

references:
  - https://github.com/BloodHoundAD/BloodHound
  - https://github.com/fox-it/BloodHound.py
---
