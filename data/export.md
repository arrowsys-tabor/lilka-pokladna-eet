# Výstup dat \(export\)

* soubor obsahuje údaje o tržbách za dané období pro skladové a účetní systémy

Export dat provedeme vybráním záložky **Správa**. Následně v **Hlavní nabídce** vlevo vybereme položku **Správa**. Vybereme období ze kterého chceme data vybrat a klikneme na tlačítko **Export do CSV**.

Čas je ve formátu [UNIX](https://en.wikipedia.org/wiki/Unix_time), převodní vzorec pro excel je:** =E2/\(60\*1000\*60\*\(24\)\)+"1/1/1970 01:00" **kde E2 je buňka času v exportu.

### Android

Soubor se následně zapsán do datového úložiště zařízení. Ve výchozím stavu je úložiště nastaveno na /LILKA/pokladna-datumexportu.csv.

### Apple/Windows

Po stistknutí tlačítka bude vytvořen e-mail se spojovacím .csv souborem v příloze. E-mail odešlete na adresu ke které máte přístup i z účetního PC. Soubor z e-mail klienta uložte do PC. Pro funkci odesílání e-mailu z pokladny je zapotřebí mít nastavenou iCloud email aplikaci.

Vygenerovaný soubor je možné odeslat standardně přes poštovní aplikaci ve Vašem zařízení.



#### Sloupce a formát CSV

ReceiptId – interní ID účtenky,

InternalNo – číslo účtenky,

Jkpov – skladové označení položky,

BuyerTin – DIČ odběratele,

DateTime – datum a čas vystavení účtenky,

TotalValue – celková částka účtenky,

Text – název položky,

Unit – jednotka položky,

UnitAmount – jednotkové množství položky,

UnitPrice – jednotková cena položky,

Quantity - množství,

Amount - počet,

QuantityAmount - množství \(na účtence\),

Netto – částka položky bez DPH,

Brutto – cena položky s DPH,

Tax – DPH z položky,

TaxPercentage – Daňová sazba,

BatchId – ID skupiny,

BatchName - Název skupiny,

fik – fiskální kód,

EET\_SecureCode – BKP kód,

EET\_SignatureCode – PKP kód,

Name - poznámka účtenky





