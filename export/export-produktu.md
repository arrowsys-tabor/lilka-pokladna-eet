### Export produktů

Pomocí tohoto výstupu lze vygenerovat soubor, který obsahuje seznam všech položek v programu včetně hodnot do nich zapsaných. Tento soubor lze při správném postupu použít jako podklad pro import \(viz. postup pro převod dat výstupu .csv na .xls níže\).

\*návod jak vytvořit import naleznete v sekci **PRÁCE S DATY-&gt;HROMADNÉ VKLÁDÁNÍ DAT \(IMPORT\)** této dokumetace

\*\*důležité sloupce pro **import z exportu** produktů jsou A, B, C, D, E, G. Volitelné pak H, I a K \(sloupce jsou takto řazené po úspěšném převedení na .xls a je nutné správně vložit tyto sloupce do souboru s importem\)

### Postup pro ANDROID

1. Přejděte do záložky **"SPRÁVA-&gt;SPRÁVA DAT"**.
2. Stiskněte tlačítko **"EXPORT PRODUKTŮ"**.
3. Pokud Vám vyskočí okno s dotazem čím otevřít zvolte GMAIL, vyplňte adresu pro zaslání a odešlete na Vámi zvolenou adresu.

\*na verzi ANDROID 6.0 a vyšší je nutné povolit aplikaci LILKA správná oprávnění, aby bylo možné export provést. Musí být povoleno **"ULOŽIŠTĚ, KONTAKTY A FOTOAPARÁT"**. Více informací o povolení oprávnění naleznete v sekci **ČASTÉ OTÁZKY-&gt;OPRÁVNĚNÍ ANDROID 6.0** této dokumentace.

### Postup pro Apple/Windows

Po stistknutí tlačítka bude vytvořen e-mail se spojovacím .csv souborem v příloze. E-mail odešlete na adresu ke které máte přístup i z účetního PC. Soubor z e-mail klienta uložte do PC. Pro funkci odesílání e-mailu z pokladny je zapotřebí mít nastavenou iCloud email aplikaci\(Apple\)/výchozí poštovní klient POŠTA\(Windows\)

Vygenerovaný soubor je možné odeslat standardně přes poštovní aplikaci ve Vašem zařízení.



### Postup pro převod dat výstupu .csv na .xls

-data ve formátu .csv jsou ve své podstatě pouhý text oddělený čárkami. V jejich standartní formě jsou špatně čitelná. Dají se ale převést do čitelného formátu .xls a .xlsx.

### Převod na .xls pomocí [drive.google.com](https://drive.google.com/drive/my-drive)

1/ Spusťte intenetový prohlížeč a přejděte na adresu [https://drive.google.com/drive/my-drive](https://drive.google.com/drive/my-drive)** **

2/ Je nutné se **přihlásit** pomocí Vašeho **GMAIL** účtu a soubor** .csv** nahrát na **GOOGLE DRIVE**

3/ Následně vytvořte nový sešit přímo na **"GOOGLE DRIVE"**. Uděláte tak stisknutím modrého tlačítka **"PŘIDAT"** v levém horním rohu prohlížeče a následným výběrem položky **"TABULKY GOOGLE"**

![](/assets/exportgoogle1.jpg)

4/ V novém sešitě zvolte záložku **"SOUBOR"** a **"IMPORTOVAT"**

5/ Zvolte požadovaný soubor a nakonfigurujte vložení dle obrázku níže

![](/assets/exportgoogle2.JPG)

6/ Stiskněte tlačítko **"IMPORTOVAT"**

7/Výsledný soubor uložte do počítače

### Převod na .xls pomocí Excel

1/ Spusťte Excel a vytvořte prázdný sešit

2/ Přejděte do záložky **"DATA"**, stiskněte tlačítko **"NAČÍST EXTERNÍ DATA"** a zvolte položku **"Z TEXTU"**

![](/assets/Exportexcell1.jpg)

3/ Načtěte soubor.csv a dle obrázků níže nastavte hodnoty.

![](/assets/Exportexcell2.JPG)

![](/assets/Exportexcell3.JPG)

![](/assets/Exportexcell4.JPG)

4/ Pro správnou funkci je nutné nastavit formát **"TEXT"** u sloupců F - DateTime, J - UnitPrice, N - Netto, O - Brutto a P - Tax

5/Stiskněte tlačítko **"DOKONČIT"  **a výsledný soubor uložte do počítače

### Vysvětlení jednotlivých pojmů EXPORTU PRODUKTŮ

ProductName - název položky

Abbreviation - zkratka, lze nastavit pro tisk na účtenku

GroupName - název skupiny

Percentage - procento DPH

UnitPrice - jednotková cena položky

StockRemaining -

Unit - jednotka například množství nebo ceny \(ks, Kč\)

Barcode - čárový kód

Jkpov - kód zboží

BuyPrice -

PLU - mezinárodní kód, dle kterého lze vkládat zboží do účtenky pouze po napsání tohoto kódu a stisku tlačítka PLU

