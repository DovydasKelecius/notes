
---



---
### DATA GATHER
---
#### IP
---
##### ipsweep.sh
```sh
#!/bin/bash

if [ $1 == ""]
then
echo "You forgot an IP address!"
echo "Syntax: ./ipsweep.sh 192.168.88"

else
for ip in `seq 1 254`; do
ping -c 1 $1.$ip | grep "64 bytes" | cut -d " " -f 4 | tr -d ":" &
done
fi  
```
%%
Pings all IPs in selected network and filters down to only an IP address
%%
You can output all of the IPs in ips.txt file
If you want to look for ports with it, run this command:
![[Pasted image 20250209131505.png]]

---
