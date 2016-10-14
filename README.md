# 0.domacazadaca
# JMBAG
0036491132

#Pitanje 1
Stvorile su se dodatne datoteke ekstenzije .dll i .pdb naziva ClassLibrary1. Uklanjanjem datoteke nastavka .dll program javlja gresku jer nasa klasa u kojoj se nalazi metoda main referencira klasu koju smo sami defeiirali, a njena definicija se ne nalazi u istom folderu. Za slanje aplikacije bilo bi potrebno poslati i .exe i .dll datoteke.

#Pitanje 2
Konzolna aplikacija je iskoristila staru verziju class library asemblija jer smo pokrenuli aplikaciju bez prethodnog prevođenja te se datoteke unutar foldera nisu zamijenile novim, ažuriranim verzijama.

#Pitanje 3
Ispisalo se "Pero: Hello World"

#Pitanje 4
U sadržaj foldera se dodala datoteka PeroClassLibary.dll

#Pitanje 5
Brisanjem originalne .dll datoteke program radi kao i build jer je ta .dll datoteka prekopirana u bin/debug folder. References sad trazi tu.dll datoteku u bin/debug folderu.

#Pitanje 6
Build proces se odvijao normalno. Packages direktorij se obnovio s NodaTime direktorijem.
