# All Linux Distro's Reverse Shell (ALDRSl13LL)
This is a simple reverse shell with both the attacker's code and the exploit.

to execute, run the attack code on the attackers machine
chmod +x attack && ./attack
then enter the port to listen to.

if the above fails to work, simply run bash attack 

on the victim's machine run
chmod +x exploit && ./exploit
then enter the attacker's ip address and the port that you want to connect on the attacker's machine.

if the above fails, simply run bash exploit.

to create persistence in the victim, ru persistence once
 chmod +x persistence
 ./persistence   altenatively use bash persistence
 
 edit all the required fields ie <attacker's ip address> and <attacker's listenig port>









