# Basic WOL in go official lib no private lib
code come from https://github.com/sabhiram/go-wol(Thanks Sabhiram)  
just removed other features and only use official lib.

## Usage
 wol MAC_ADDRESS [BROADCAST_IP]  
 wol 18-18-18-18-18-18 192.168.1.255  
 wol 18-18-18-18-18-18  

#### Note: BROADCAST_IP default is 255.255.255.255