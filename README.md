# SOAR-EDR-lab
<img width="781" height="797" alt="Screenshot 2026-03-14 001916" src="https://github.com/user-attachments/assets/bdb8c924-a10e-4869-a0b1-25a1e0f749bd" />

## Setup
### Either boot up a Windows VM using Vmware/VirtualBox or use a cloud service
### LimaCharlie- Log in to the site and create a an organization. From here copy the sensor link and use it to download the sensor .exe file and copy the sensor key to run it.
### Install LaZagne - https://github.com/AlessandroZ/LaZagne

### Now in the LimaCharlie Dashboard, Create New Rule.


### For Detect:
<!--
  events:
    - NEW_PROCESS
    - EXISTING_PROCESS
  op: and
  rules:
    - op: is windows
    - op: or
      rules:
        - case sensitive: false
          op: ends with
          path: event/FILE_PATH
          value: lazagne.exe
        - case sensitive: false
          op: ends with
          path: event/COMMAND_LINE
          value: all
        - case sensitive: false
          op: contains
          path: event/COMMAND_LINE
          value: lazagne
        - case sensitive: false
          op: is
          path: event/HASH
          value: "3cc5ee93a9ba1fc57389705283b760c8bd61f35e9398bbfa3210e2becf6d4b05"
-->
### For Respond:
<!--
  - action: report
    metadata:
      author:"ANYNAME"
      description: Detects LaZagne
      falsepositives:
      - Unlikely
      Level: medium
      tags:
      - attack.credential_access
      name: "ANYNAME"
-->
### Now all the detections can be seen in the detections option in the dashboard



























