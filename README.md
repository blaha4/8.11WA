# 8.11WA
WA


2. Vytvořte třídu pro evidenci hráčů ve hře. Hráč bude mít uživatelské jméno, heslo a emailovou adresu. (Přístup k vlastnostem můžete vygenerovat. Není nutné hlídat nesmyslné hodnoty. Nechceme, abyste půlku času na test strávili kontrolou vlastností.)

Do třídy implementujte metody GetHashCode, Equals a CompareTo tak, aby bylo možné hráče vkládat do HashSetu i SortedSetu. Hráč by měl mít unikátní jméno a emailovou adresu. Hráči budou setříděni podle jejich emailové adresy.

3. Vytvořte třídu Chovatel (chovatel zvířat v ZOO), která bude evidovat zvířata, o která se chovatel v ZOO stará. Třída bude obsahovat jako vlastnosti jméno chovatele, a vhodnou kolekci pro uložení všech zvířat. Kolekci volte tak, byste mohli snadno vyhledávat zvířátka na základě jejich druhu. Pro zvířata evidujete jejich hmotnost, druh a pohlaví.

Ve třídě napište:

metodu pro uložení nového zvířete
metodu, která vám vrátí seznam všech zvířat daného druhu, o která se chovatel stará
Bylo by vhodné, abyste pro jednotlivá zvířata vytvořili třídu, která bude obsahovat hmotnost zvířete, jeho pohlaví zvířete a druh (druh může být – enum, string...)

