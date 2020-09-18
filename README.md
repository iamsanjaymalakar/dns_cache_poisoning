# DNS cache poisoning
DNS (Domain Name System) is the Internet’s phonebook; it translates hostnames
to IP address and vice-versa. This is done via DNS resolution. DNS attacks
manipulates this resolution process in various ways. One of them is DNS Cache
Poisoning Attack. There are two main ways to perform this attack, local (where
the attacker and victim DNS server are on the same network, where packet
sniffing is possible) and remote (where packet sniffing is not possible). I've
implemented the remote DNS cache poisoning attack. 


## Lab Environment
To demonstrate this attack, I have used three virtual machines, which runs on one
single physical machine.
1. A DNS server
2. Victim user
3. Attacker which also hosts fake DNS server 

## Report
More details about the attack here.
