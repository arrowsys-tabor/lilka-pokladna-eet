# Export dat

Slouží jako podklad pro **odpis z programu "ZÁSOBY"**. Obsahuje seznam prodaného zboží za zvolené období dle jednotlivých účtenek.

**ZÁSOBY -** program, který lze zakoupit zvlášť a použít pro sledování skladů, inventury a odpis zboží z vedeného skladu. Pro bližší informace nás neváhejte kontaktovat na **zasoby@arrowsys.cz**

### Postup pro ANDROID

1. Přejděte do záložky **"SPRÁVA-&gt;SPRÁVA DAT"**.
2. Vyberte datum od kdy do kdy se má export vygenerovat.
3. Stiskněte tlačítko **"EXPORT do CSV"**.
4. Pokud Vám vyskočí okno s dotazem čím otevřít zvolte GMAIL, vyplňte adresu pro zaslání a odešlete

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

### Vysvětlení jednotlivých pojmů EXPORTu

Export lze převést pomocí tabulek GOOGLE na srozumitelnější data. K tomuto musíte mít založený účet na GMAILu. Následně lze rozlišovat dle sloupců. Standartně jsou data v jednom řádku oddělena čárkou.

A - RecieptID - interní číslo účtenky

B - InternalNo - číslo účtenky, která byla odeslána do EET

C - Jkpov - kód zboží

D - BuyerTin - DIČ zákazníka\(odběratele\).

E - DateTime - datum a čas uvedený v Unixovém formátu. Je nutné převést pomocí vzorce na správný formát data a času v případě potřeby.

Čas je ve formátu [UNIX](https://en.wikipedia.org/wiki/Unix_time), převodní vzorec pro excel je:** =E2/\(60\*1000\*60\*\(24\)\)+"1/1/1970 01:00" **kde E2 je buňka času v exportu.

F - TotalValue - celková částka tržby účtenky

G - Text - název položky vložené na účtenku

H - Unit - jednotka například hmotnosti, ceny \(ks, Kč\)

I - UnitAmount -

J - UnitPrice - jednotková cena daného zboží

K - Quantity - počet

L - Amount - množství

M - QuantityAmount - počet množství

N - Netto - cena bez daně

O - Brutto - cena s daní

P - Tax - vypočtená daň z celkové hodnoty položky

Q - TaxPercentage - procento daně, ve které se daná položka nachází \(21%, 15%, 10% a BEZ DPH\)

R - BatchID - interní číslo skupiny v programu

S - BatchName - Název skupiny, ve které se zboží nachází

T - FIK - fiskárlní identifikační kód

U - EET\_SecureCode - BKP - bezpečnostní kód, který je obsažen jak na normalní účtence, tak na účtence s offlinovým PKP kódem.

V - EET\_SignatureCode - PKP kód, jedná se o případný offlinový kód, který je generován na účtenku pokud program detekuje výpadek internetu

W - Name - poznámka účtenky

