# Výstup dat \(export\)

* soubor obsahuje údaje o tržbách za dané období pro skladové a účetní systémy

Export dat provedeme vybráním záložky **Správa**. Následně v **Hlavní nabídce** vlevo vybereme položku **Správa**. Vybereme období ze kterého chceme data vybrat a klikneme na tlačítko **Export do CSV**.

Čas je ve formátu [UNIX](https://en.wikipedia.org/wiki/Unix_time), převodní vzorec pro excel je:** =E2/\(60\*1000\*60\*\(24\)\)+"1/1/1970 01:00" **kde E2 je buňka času v exportu.

### Android

Soubor se následně zapsán do datového úložiště zařízení. Ve výchozím stavu je úložiště nastaveno na /LILKA/pokladna-datumexportu.csv.

### Apple/Windows

Po stistknutí tlačítka bude vytvořen e-mail se spojovacím .csv souborem v příloze. E-mail odešlete na adresu ke které máte přístup i z účetního PC. Soubor z e-mail klienta uložte do PC. Pro funkci odesílání e-mailu z pokladny je zapotřebí mít nastavenou iCloud email aplikaci.

Vygenerovaný soubor je možné odeslat standardně přes poštovní aplikaci ve Vašem zařízení.

