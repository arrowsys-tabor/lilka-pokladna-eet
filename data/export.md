# Výstup dat \(export\)

* soubor obsahuje údaje o tržbách za dané období pro skladové a účetní systémy

Export dat provedeme vybráním záložky **Správa**. Následně v **Hlavní nabídce** vlevo vybereme položku **Správa**. Vybereme období ze kterého chceme data vybrat a klikneme na tlačítko **Export do CSV**.

Čas je ve formátu [UNIX](https://en.wikipedia.org/wiki/Unix_time), převodní vzorec pro excel je:** =E2/\(60\*1000\*60\*\(24\)\)+"1/1/1970 01:00" **kde E2 je buňka času v exportu.

### Android

Soubor se následně zapsán do datového úložiště zařízení. Ve výchozím stavu je úložiště nastaveno na /LILKA/pokladna-datumexportu.csv.

### Apple/Windows

Po stistknutí tlačítka bude vytvořen e-mail se spojovacím .csv souborem v příloze. E-mail odešlete na adresu ke které máte přístup i z účetního PC. Soubor z e-mail klienta uložte do PC. Pro funkci odesílání e-mailu z pokladny je zapotřebí mít nastavenou iCloud email aplikaci.

Vygenerovaný soubor je možné odeslat standardně přes poštovní aplikaci ve Vašem zařízení.

## Postup pro převod dat výstupu .csv na .xls

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

#### Sloupce a formát CSV

A - ReceiptId – interní ID účtenky,

B - InternalNo – číslo účtenky,

C- Jkpov – skladové označení položky,

D - BuyerTin – DIČ odběratele,

E - DateTime – datum a čas vystavení účtenky,

F - TotalValue – celková částka účtenky,

G - Text – název položky,

H - Unit – jednotka položky,

I - UnitAmount – jednotkové množství položky,

J - UnitPrice – jednotková cena položky,

K - Quantity - množství,

L - Amount - počet,

M - QuantityAmount - množství \(na účtence\),

N - Netto – částka položky bez DPH,

O - Brutto – cena položky s DPH,

P - Tax – DPH z položky,

Q - TaxPercentage – Daňová sazba,

R - BatchId – ID skupiny,

S - BatchName - Název skupiny,

T - fik – fiskální kód,

U - EET\_SecureCode – BKP kód,

V - EET\_SignatureCode – PKP kód,

W - Name - poznámka účtenky

