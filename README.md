# SOAR-EDR-lab
<img width="781" height="797" alt="Screenshot 2026-03-14 001916" src="https://github.com/user-attachments/assets/bdb8c924-a10e-4869-a0b1-25a1e0f749bd" />

## Setup
### Either boot up a Windows VM using Vmware/VirtualBox or use a cloud service
### LimaCharlie- Log in to the site and create a an organization. From here copy the sensor link and use it to download the sensor .exe file and copy the sensor key to run it.
### Install LaZagne - https://github.com/AlessandroZ/LaZagne

### Now in the LimaCharlie Dashboard, Create New Rule.


### For Detect:
https://github.com/tarun1847/SOAR-EDR-lab/blob/main/Detect
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



























