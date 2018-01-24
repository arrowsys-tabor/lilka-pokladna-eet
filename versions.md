# Verze a změny

### 2.2.8

* Přidání sloupce PLU do exportu produktů
* Možnost tisku poznámky na objednávku\(SPRÁVA-PROSTŘEDÍ\)

### 2.2.7

* Opraven export textu při exportu produktů do souboru
* Oprava Cloud tisku pro Windows 10 verze 1709 a 1703
* Upravení požadavků Blockcypher
* Přidána měna Kanadský dolar
* Zaokrouhlování pouze pro měnu Kč
* Do nastavení přidána možnost "Zakázat storno"
* Do nastavení přidána možnost "Řadit účtenky vzestupně"
* Seznam tiskáren se nyní skryje, pokud se nastaví WiFi tiskárna
* Oprava chyby se zobrazením množství na účtence v konkrétních situacích
* Po přepnutí tiskárny nyní není třeba program vypnout a znovu spustit, aby se nastavení provedlo
* Filtr účtenek si nyní pamatuje nastavení po dobu 10 minut od poslední změny
* Přidána funkce pro odesílání v režimu cestovních služeb; pro odeslání v tomto režimu je třeba vybrat DPH s označením CEST \(je nutné doplnit tuto sazbu DPH ručně\)
* V záložce Produkt ošetřeno zadávání nečíselných znaků do variabliní ceny
* Oprava nastavení sekundární BT tiskárny
* Přidány další varianty propojení hlavní a objednávkové tiskárny a to následující:
* * BT hlavní + WiFi obejdnávková
* * oranžové V1 hlavní + WiFi objednávková
* * oranžové V1 hlavní + BT objednávková

### 2.1.4

* Oprava blikání na terminálech V1

### 2.1.3

* Úprava logování ČSOB IP terminálu

### 2.1.2

* Úprava pro certifikaci mPOS

### 2.1.1

* Oprava přidávání položky na účtenku, kdy v některých situacích nebyla položka korektně přidána na účtenku

* Omezení počtu číslic na kalkulačce na 12

### 2.1.0

* Oprava tisku PKP kódu na Q80i - tiskárna nemohla vytisknout řetězec delší než 150 znaků. \(iOS\)

### 2.0.6

* Opravení chyby které nevypisovalo položky na E-mail a Cloud účtence

* Oprava textu při potvrzení storna účtenky

* Oprava - nemožnost stornovat na Apple z důvodu špatného popisu tlačítka

* Přidána možnost filtrování účtenek dle data

* Přidána možnost zobrazit pouze stornované účtenky

### 2.0.5

* Opravena chyba odesílání do EET v pověřujícím režimu

### 2.0.4

* Základní podpora mobilního platebního terminálu mPOS
* Opravena chyba, která neukládala účtenku na fakturu
* Možnost ruční aktualizace DB \(podpora\).
* Oprava platby Bitcoinem
* Oprava částky -0.00 do EET
* Oprava výběru pokladního na hlavní obrazovce
* Možnost dotisknout účtenky emailem a Cloud tiskem
* Odstraněna chyba, která při platbě bez EET + karta způsobovala, že se účtenka neukončila

### 2.0.3

* Nastavení emailu pro zálohu a exporty
* Export produktů do skladů/v importovatelném formátu do LILKY
* Oprava chyby, která způsobila nedopsání účtenky do pohybu kasy
* Oprava chyby, která na účtence tiskla zbytečné nuly např. 35.0000001

### 2.0.2

* Korektura německého překladu

### 2.0.1

* Opravena chyba která nulovala zůstatek v pokladně - problém s uzávěrkou
* Po obnově dat se aktualizuje zůstatek kasy
* Zálohování na iOS
* Při každém startu se duplikovaly skryté položky kalkulačky, aktualizace nepoužité smaže.
* Ošetřena chyba při které bylo možné zvýšit číslo účtenky překliknutím na metodu platby.
* Úplná podpora bankovního terminálu ČSOB
* Záloha na Android se nyní tvoří do složky /LILKA-data/backup

### 2.0.0

* Stabilita BT pro Windows

### 1.9.8

* Zlepšení UI při platbě bitcoinem
* Ochranné prvky při zápisu do pokladny, kontrola návaznosti zůstatku
* Upozornění při vypnutém BT.
* Zálohování konfiguračního souboru \(Android\)
* Podpora ČSOB terminálu
* Kontrola DIČ certifikátu

### 1.9.7

* Podpora WiFi tiskáren

### 1.9.6

* Upraven tisk pro V1

### 1.9.5

* Upraven počet zobrazovaných položek pro větší displeje \(nyní až 44\)
* Opravena chyba duplicitních účtenek při špatném spojení s tiskárnou
* Opravena chyba která při zápisu účtenky zapsala do označení pokladny označení provozovny
* Opraveno špatné řazené účtenek ve Správa - Účtenky

### 1.9.4

* Opravena chyba odesílání v pověření
* Přidána podpora Aclas Aow tisku
* Možnost tisknout diakritiku - Nastavení tisku

### 1.9.3

* Oprava chyby neodesílaných účtenek z archivu

### 1.9.2

* Změna tisku jednotkové ceny 2 L x 25.00
* Oprava slévání množství a ceny na účtence při funkci tisku názvu položky na nový řádek a znakového tisku
* Možnost netisknout jednotkovou cenu
* Možnost tisknout jednotkovou cenu u korunových položek
* Výpis tržeb celkem za stravenky na uzávěrku
* Opraveno zadávání desetinných míst Rychlé kalkulačky \(100,05 a10,05\)
* Vylepšení podpory BT tisku na Windows 10
* Doplněno tlačítko pro vzdálenou pomoc na SUNMI V1 - TW V1 Doplněk
* Lze zadat variabilní množství na 3 desetinná místa
* Jednotkové množství produktu může být na 3 desetinná místa
* Export obsahuje 3 desetinná místa
* Vylepšené generování exportu na některých zařízeních

### 1.9.1

* Úprava načítání QR Faktur
* Úpravy pro tisk na P2000
* Opravena chyba nenačítání údajů o položce ve formuláři položky
* Podpora tisku Zebra tiskáren
* Přidána univerzální funkce pro tisk "Znakový tisk"
* Podpora Zebra Line Print módu
* Odstraněna chyba, která navyšovala kasu při platbě kartou
* Odstraněna chyba, která způsobovala zdvojování číselné řady

### 1.9.0

* Podpora tisku na all in one zařízení P2000

### 1.8.9

* Oprava  zadávání nuly za desetinnou částkou
* Oprava načítání produktu
* Lze načíst produkt z čárového kódu kamery v záložce Rychlé
* Opraven přepočet jednotkové ceny na účtence
* Kompatibilita s QR Platba + F

### 1.8.8

* Do pokladny se vkládají částka po zaokrouhlení
* Oprava null a undefined na účtence
* Oprava rozepisování jednotkových cen na účtence
* Export CSV rozšířen o EET kódy a poznámku účtenky
* Možnost vypnout výpis tržeb po položkách Správa - Prostředí - Tržby nevypisovat položky
* Podpora prodeje použitého zboží
* PDF a e-mail účtenky doplněny o jednotkové množství
* Zablokováno mazání položek, které už jsou na účtenkách
* Podpora čtečky čárových kódu na obrazovce Účtenka a Rychlé
* Podpora VIetnamštiny
* Když je překročen součet dělené platby, přebytek se přiřadí do vratky

### 1.8.7

* Oprava chyby konečného zůstatku
* Oprava Bitcoinpay API

### 1.8.6

* QR faktura
* Možnost skrýt platbu fakturou
* Nastavení výchozí metody platby Hotovost - rychlejší platba
* Oprava tlačítka ZPĚT při PINu
* Oprava výběru desetinné částky z kasy

### 1.8.5 \(pouze Windows\)

* Oprava zarovnání PKP na cloud a PDF účtence
* Zarovnání označení provozovny a pokladny na BT účtence

### 1.8.4 \(pouze Windows\)

* Oprava tisku

### 1.8.3 "Alcatel"

* Oprava výpadků spojení s BT tiskárnou pro XP58 s Alcatel, Blowtab, Prestigio tablety
* Položky vyplňují obrazovku prodeje na maximum
* Zpřehlednění aktivované verze
* Oprava pusuvných šipek položek na Windows 10 Mobile

### 1.8.2 "Vzhledové úpravy 2"

* Pro neplátce DPH se rozpis DPH netiskne na účtence
* Opravena chyba nepřístupnosti záložky Správa

### 1.8.1 "Vzhledové úpravy"

* Zrychlení vystavení účtenky v Pověření. Ve Správa - Firma, musí být uvedeno DIČ, při platbě stačí zaškrtnout, že se jedná o prodej v Pověření. 
* Rychlejší načítání Účtenek a Pohybů pokladny z archivu
* Rychlejší pořizování v záložce Rychlé. Nyní lze nastavit, aby se po tisku účtenky pokladna vrátila zpět na záložku Rychlé. Správa - Prostředí
* Položky aktuální účtenky se v záložce zobrazují nalevo od kalkulačky. 
* * Při horizontálním rozdělení vyšším než 750px, tablety 7p a vyšší
* Dělená platba - část lze platit hotově, kartou a stravenkami
* Tisk kopií účtenky \(Správa - Prostředí - Účtenka\)
* Tisk poznámky na účtenku \(Správa - Prostředí - Účtenka\)

##### Drobné úpravy a opravy chyb

* Oprava chyby kdy účtenka nebyla v přílozee-mailu na Windows 10 PC
* Přímý odkaz na vzdálenou správu ve Správa - Podpora
* Při výběru položek k rozdělené platbě se mezišoučet v horním panelu aktualizuje podle vybraných položek
* Důkladnější kontrola nastavení EET, přesnější upozornění špatného nastavení.
* Nastavení Mezní doby odezvy EET
* DPH 21, 15 a 10 v záložce Rychlé jsou pro neplátce skryta
* Ověřovací režim přejmenován na Ověřovací mód
* Pokud se změnily záložky, pokladní nezůstal vybraný
* Po smazání produktu z účtenky se součet neprojevil na horním panelu Rychlé a Účtenka
* Po smazání dat nastavení Hotovostního zůstatku na 0
* Odstraněna chyba kdy nešel nastavit PIN

### 1.8.0 "Ostré EET"

* Přidána platba fakturou - neodesílá se do EET
* Odesílání do Produkčního \(Ostrého\) EET prostředí
* Správa neodeslaných účtenek
* * Správa - Neodeslané účtenky
* * Neodeslané účtenky lze hromadně odeslat tlačítkem **Znovu odeslat vše**
* Zrychlené vytváření účtenek. Pokud se přidává položka a není vybrána účtenka, vytvoří se nová účtenka s přidávanou položkou.
* Volba tisku zkratky na účtenku
* * Správa - Prostředí - Tisknout zkratku položky
* Volba tisku položek na samostatný řádek
* Správa - Prostředí - Tisknout položku na nový řádek
* Zálohování a Obnova \(prozatím pouze Android\)

##### Drobné úpravy a opravy chyb

* Šuplík se otevírá pouze při tisku účtenky
* Tisk do kuchyně přejmenován na Tisk objednávky
* Nové ikony plateb
* Větší prostor pro sumu částky účtenky, odebráno Kč
* Úpravy zobrazení pro Citaq V1
  ### 1.7.0 "EET"
* Podpora odesílání do Neprodukčního prostředí EET



