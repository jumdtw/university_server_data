# cisco id pass
 
- WLC302(YamahaAP)
    - id:nimda pass:admin
    - GIP: 153.143.228.211
    

- RTX1210
    - 192.168.1.1 (Local onley)
    - id:nimda pass:password

# networklist
## B570
RTX1210 

## detection

use file
- convert-mal-cap.py
- convert-mal-cap2.py
- convert-normal-cap.py
- dataset/conn-cat.sh

### interfaces
- enp2s0: 192.168.100.111 vlan1
- eno1: 102.105 vlan2
- enp1s0f0: 100.139 vlan1
- enp1s0f1: null 