Hacklib 3rd module using, easy coding for humans!

Hacklib -basicly- is a module that helping you with coding hack tools-including brute force attack, sniffing network, dorkmaking, wordlist making-. 
Features:
� Brute Force Attack
� Sniffer
� Dork Maker
� Wordlist Creator

Commands:

hack.BFAttack().run(site.txt, password.txt):
Starts a brute force attack on wordpress sites.

hack.WordList().make(**args)
Creates a wordlist with infos (max 7 args)

hack.Sniff().run()
Sniffing network

hack.DorkMake().run(num_of_the_dorks)
Creates wordpress dorks.


Using

>>> import hack
>>> h = hack.BFAttack()
>>> h.run("a.txt", "b.txt")

>>> h = hack.WordList()
>>> h.make("a", "d")
[+] Over.

>>> import hack
>>> h = hack.Sniff()
>>> h.run()
Protocol: TCP 192.168.0.30 -> 83.66.162.128
Protocol: TCP 83.66.162.128 -> 192.168.0.30
Protocol: TCP 192.168.0.30 -> 192.229.233.25
Protocol: TCP 192.168.0.30 -> 192.229.233.25
Protocol: TCP 192.168.0.30 -> 188.165.145.89


etc.








Hacklib hack tool yazma k�t�phanesi:

Yap�labilecekler:

Sniffer
DorkMaker
Wordlist olu�turucu
Brute force atak

Kullan�m:
hack.BFAttack().run(site.txt, password.txt):
Belirtilen wordpress sitelere belirtilen �ifrelerle sald�r�r (username = admin)

hack.WordList().make(**args)
Verilen bilgilerle bir wordlist olu�turur

hack.Sniff().run()
A�� dinler

hack.DorkMake().run(num_of_the_dorks)
Wordpress dork olu�turur

>>> import hack
>>> h = hack.BFAttack()
>>> h.run("a.txt", "b.txt")

>>> h = hack.WordList()
>>> h.make("a", "d")
[+] Over.

>>> import hack
>>> h = hack.Sniff()
>>> h.run()
Protocol: TCP 192.168.0.30 -> 83.66.162.128
Protocol: TCP 83.66.162.128 -> 192.168.0.30
Protocol: TCP 192.168.0.30 -> 192.229.233.25
Protocol: TCP 192.168.0.30 -> 192.229.233.25
Protocol: TCP 192.168.0.30 -> 188.165.145.89
