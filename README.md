# Bakaláři API
Dokumentace mobilního API bakalářů

# URL
Vše se odehrává na adrese institutu (školy). Pro zjednodušení budu používat doménu www.example.com. Veškeré API dotazy směřují na `/login.aspx` a to i v případě, že adresa používá nové webové rozhraní next (např. `https://www.example.com/login.aspx`)

# Dotazy
Každý dotaz (vyjma získání tokenu) se skládá z [tokenu](vypocitani_tokenu.md) (`hx`) a názvu modulu (`pm`), případně dalších parametrů jako například data. Příklad: `https://www.example.com/login.aspx?hx=m_1dM0sdoUC3bKRkMdiyjc9IaOkOPyNvpq66zuwIu2eHUtYvkLwrUtHHPR6iNe1KOtA2HgSZtuoBWdido79VjQ==&pm=rozvrh`. Vrací XML, které je popsáno v následující sekci

# Moduly
* [absence](moduly/absence.md)
* [akce](moduly/akce.md)
* [login](moduly/login.md)
* [pololetni](moduly/pololetni.md)
* [predmety](moduly/predmety.md)
* [predvidac](moduly/predvidac.md)
* [rozvrh](moduly/rozvrh.md)
* [suplovani](moduly/suplovani.md)
* [ukoly](moduly/ukoly.md)
* [vyuka](moduly/vyuka.md)
* [wlogin](moduly/wlogin.md)
* [znamky](moduly/znamky.md)
* all
* classification
* classificationMarks
* home
* interfaces
* komdel
* komenslisty
* komsend
* nastenka
* odeslane
* prijate
* priloha
* rozvrhakt
* rozvrhnext
* rozvrhperm
* setok
* setread
* timeline
* tkday
* tkedit
* tksave
* tksaveabsent
* ucitelakce
* ucitelall
* ucitelpredmety
* ucitelrozvrh
* ucitelrozvrhakt
* ucitelrozvrhnext
* ucitelrozvrhperm
* ucitelsuplovani