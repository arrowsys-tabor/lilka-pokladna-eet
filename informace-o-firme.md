# Informace o firmě

Nastavení nejdůležitějších částí programu jako jsou údaje o provozovně, vložení certifikátu, hesla, EET provozovny, číslování účtenek a mnohé další. Všechna tato nastavení mají vliv na zobrazené informace na vytištěné účtence.

### Informace o firmě

**Název subjektu -** při načtení údajů z registru ARES se načtou informace subjektu tak, jak jsou zapsány v rejstříku firem. Finanční správa požaduje ale v údajích zapsanou adresu provozovny, proto je nutné toto zkontrolovat a zapsat ručně. Tyto údaje je nutné vyplnit bez diakritiky.

**IČO -** IČO subjektu. Standardně má 8 míst a jedná se pouze o číslo. Pokud máte pouze 7 místné , je nutné zapsat i počáteční nulu.

**DIČ -** daňové identifikační číslo. Nyní má každý subjekt svoje DIČ, proto je nutné zkontrolovat jeho správnost na daňovém portálu při generování certifikátu.

**Adresa -** adresa provozovny. Adresa musí být vyplněna bez diakritiky.

**Telefon -** nepovinný údaj, telefon na provozovnu.

**Kontaktní osoba -** nepovinný údaj, jméno kontaktní osoby, nejčastěji osoby zodpovědné za chod prodejny.

**Email -** nepovinný údaj, email na provozovnu, kontaktní email.

**Web -** nepovinný údaj, www adresa provozovny.

**Číslování účtenek -** číselná řada účtenky, do EET musí být zachována logicky posloupná číselná řada. Od tohoto čísla účtenky se bude odvíjet další číslování vytištěných účtenek.

**Poslední číslo -** číslo poslední vytvořené účtenky. Standartně se načítá po vytvoření účtenky +1. Pokud ale potřebujete navázat předchozí číselnou řadu, stačí nastavit číslo poslední účtenky a následně uložit. Pokladna vytvoří následující účtenku se stejným číslem a načte +1.

**Tisknout "SUBJEKT NENÍ PLÁTCEM DPH" -** tiskne na účtenku **"SUBJEKT NENÍ PLÁTCEM DPH".** V záložce **"RYCHLÉ" **nejsou zobrazeny tlačítka sazeb DPH 21%, 15% a 10%. Volba je určena pouze pro neplátce DPH.

### Elektronická evidence tržeb

**Označení provozovny -** obsahuje číslo provozovny, založené na daňovém portálu. Zobrazuje se na účtence a na výpisu tržeb z daňového portálu.

**Označení pokladny -** označení pokladny, číslo, které je jako dodatečný údaj na účtence a následně výpisu tržeb z daňového portálu.

**Pověřující DIČ -** údaj, který se vyplňuje pokud provozujete prodej v pověření \(nejčastěji prodej cigaret na jinou osobu\).

**Heslo EET certifikátu -** tzv. soukromý klíč certifikátu. Nutné pro zobrazení tlačítka načíst certifikát.

**Tlačítko "Načíst certifikát" -** funkce pro načtení certifikátu.

**Mezní doba odezvy \(s\) -** určuje jak dlouho bude aplikace čekat na odezvu z EET pro vytištění FIK na účtence. Při nespojení s EET serverem nebo nefunkčním internetu program po uplynutí limitu vystaví automaticky off-line účtenku s PKP kódem.

### EET Režimy

**EET odesílání -** běžný režim zasílání do EET

**Zjednodušený režim -** režim odesílání do 5-ti dnů. Pro tento režim je nutné získat povolení od místního finančního úřadu.

**Ověřovací mód -** při zaškrtnutí zkontroluje zda je nastavení EET správné a vypíše pouze hlášení na obrazovce. Účtenka není zaslána do EET a není vytištěna.

**Neprodukční prostředí -** režim pouze pro zkušební certifikáty a vývojáře EET softwaru.

### Pokročilé nastavení

Jedná se o placený upgrade, který je možné objednat pouze přes náš eshop [ZDE](https://www.arrowsys.cz/cs/lilka-aktualizace-zmeny-ustavniho-soudu-od-132018). Koupením tohoto upgradu si zajistíte možnost vypnutí změn schválených ústavním soudem, které platí od 1.3.2018

1. **Neodesílat tržby Bitcoinem -** zamezí zasílání tržeb do EET pomocí způsobu úhrady BITCOIN
2. **Neodesílat tržby kreditní kartou -** zamezí zasílání tržeb do EET pomocí způsobu úhrady KARTOU
3. **Netisknout DIČ na účtence -** na účtence zaslané do EET se nezobrazí DIČ

Pokud nemáte zakoupen balíček Změn ústavního soudu, objeví se Vám po stiknutí tlačítka **"POKROČÍLÉ NASTAVENÍ"** upozornění **"TENTO MODUL NENÍ PRO VAŠI LICENCI AKTIVNÍ. KONTAKTUJTE WWW.ARROWSYS.CZ"**.

\*je nutné mít nastavené **správné ičo**, které se vztahuje k licenci, aby bylo možné přejít do **POKROČILÉHO NASTAVENÍ**.

