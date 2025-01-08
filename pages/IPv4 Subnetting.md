- Beim Standartmäßigen Subnetting von IPv4 muss man erst die gegebene Netzmaske anschauen und überprüfen ob das Subnetting möglich ist aus einem /24 Netzwerk kannst du kein /23 machen du kannst die Netzmaske nur erweitern.
- Als nächstes guckst du dir an in wieviel Host du dein Netzwerk teilen sollst, gehen wir von 50 host aus die du in 6 Subs unterteilen willst, dann musst du dir die Anzahl an Bits angucken die du mindestens brauch um 50 host darzustellen das ist in dem fall  2^6 = 64 also machst du aus einem /24 Netzwerk ein /26 Netzwerk
- Beispielrechnung: 
  Basis: 192.192.69.44/24
  Subs: 6
  Hosts 20
	- Netzmaske: /27
		- Subnetz 1:
		  192.192.69.0
		  192.192.69.31
		- Subnet2: 
		  192.192.69.32
		  192.192.69.63
		- Subnet 3:
		  192.192.69.64
		  192.192.69.95
		- Subnet 4:
		  192.192.69.96
		  192.192.69.127
		- Subnet 5:
		  192.192.69.128
		  192.192.69.159
		- Subnet 6:
		  192.192.69.160
		  192.192.69.191
		- Subnet 7:
		  192.192.69.192
		  192.192.69.223
		- Subnet 8:
		  192.192.69.224
		  192.192.69.255