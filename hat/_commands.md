# TABLE OF CONTENTS

---


- [[#Unix|Unix]]
- [[#Network|Network]]
- [[#`iwconfig`|`iwconfig`]]
- [[#`ifconfig`|`ifconfig`]]
	- [[#`ifconfig`#`ip a`|`ip a`]]
- [[#`arp -a`|`arp -a`]]
	- [[#`arp -a`#`ip  n`|`ip  n`]]
- [[#`Route`|`Route`]]
	- [[#`Route`#`ip r`|`ip r`]]
- [[#`ping`|`ping`]]



%%[ExplainShell](https://explainshell.com/)%%

---
#### Unix
---

#### `sudo service apache2 start/stop`
hosts a website (port 80) in /var/www/ directory
![[Pasted image 20250209115312.png]]

---

##### `python3 -m http.server 80`
hosts a website on current directory [Most of the times better]. m -  module
![[Pasted image 20250209115517.png]]

---
#### `sudo systemctl start/disable [service]`
![[Pasted image 20250209115807.png]]

---
%% For Kali %%
#### `sudo apt update && apt upgrade`
Updates system. [Root] needed. But looks like using git/[pimpmykali](https://github.com/Dewalt-arch/pimpmykali.git) is better overall.

---
#### `grep "[string]"`
it grabs a line from given output. Example: cat ip.txt | grep "64 bytes"
![[Pasted image 20250209123818.png]]

---

#### `cut`
cuts out of text
![[Pasted image 20250209124342.png]]
%%
-d delimiter [" "] I want to cut on a space
-f field [4] I want to count up to 4 to grab that data
%%

---

#### `tr`
Translate, squeeze, and/or delete characters from standard input, writing to standard output.
![[Pasted image 20250209124750.png]]
%%
-d delete [":"] I want to delete ":"
%%



































---
#### Network
---
####  `iwconfig`
wireless network configurations [WIRELESS]

---

#### `ifconfig`
network configurations [WIRED]
![[Pasted image 20250208132529.png]]

---

##### `ip a`
newer version of ifconfig (sometimes more useful)
![[Pasted image 20250208154855.png]]

---

#### `arp -a`
Address Resolution Protocol (Shows neighbors)
![[Pasted image 20250208155530.png]]

---
##### `ip  n`
fancier version  of [[_commands#`arp -a` - Shows neighbors|arp  -a]] 
![[Pasted image 20250208155749.png]]

---
#### `Route`
Let's us know where traffic is routing
![[Pasted image 20250208160139.png]]

---

##### `ip r`
fancier version of [[_commands#`Route`|Route]]
![[Pasted image 20250208160301.png]]

---
#### `ping`
does a [[_notations#`Three Way Handshake`|Three Way Handshake]] and gathers packet info
![[Pasted image 20250208160829.png]]
%%
Not all machines allow [icmp] traffic, so they may not respond but could still be online
%%

---












































