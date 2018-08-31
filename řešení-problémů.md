# Lilka mi nechce odesílat účtenky.

**1. ŘEŠENÍ - čekající program jak na tiskárnu tak na internet**

-zkontrolujte prosím nastavení tiskárny

-v záložce **SPRÁVA -&gt; INFORMACE O FIRMĚ** nastavte vyšší hodnotu časové odezvy pro **MEZNÍ DOBA ODEZVY**

**2. ŘEŠENÍ - zaseklá účtenlová tiskárna**

-zkontrolujte zda máte správně připojenou tiskárnu k Vašemu zařízení a zda-li je správně zadaná i v pokladně Lilka.

**SPRÁVA-&gt;TISKÁRNA-&gt;ÚDAJE PRO PŘIPOJENÍ K BLUETOOTH TISKÁRNĚ-&gt;NÁZEV ZAŘÍZENÍ**

\*pokud používáte Bluetooth tiskárnu, je nutné mít také zaškrtnuté pole **"POVOLIT TISK NA BLUETOOTH TISKÁRNU**"

\*\*pokud jste zvolili způsob odesílání pomocí emailu, povolte oprávnění\(naleznete v sekci "časté otázky" naší dokumentace\)

**3. ŘEŠENÍ - pouze zašedlé tlačítko uhradit a tisknout**

-zkontrolujte správnost zadání hesla k EET certifikátu a certifikát opětovně načtěte. Naleznete v **"SPRÁVA-&gt;INFORMACE O FIRMĚ"**.

# Nelze mi doodeslat účtenky

-přejděte do záložky **"SPRÁVA -&gt; NEODESLANÉ ÚČTENKY"** a stiskněte tlačítko **"ZNOVU ODESLAT VŠE".**

-pokud Vám Lilka nechce doodeslat neodeslané účtenky opakujte toto později, servery finanční správy jsou pravděpodobně v danou chvíli zaneprázdněné.

-zkontrolujte zda máte nainstalovanou nejnovější verzi aplikace **"ANDROID SYSTEM WEBVIEW"**. Tu naleznete k nainstalování v aplikaci **"OBCHOD PLAY"**, která slouží k instalaci a aktualizaci všech aplikací ve Vašem zařízení.

# Poskytovatel internetu blokuje komunikaci se servery EET

Poskytovatel internetu musí povolit komunikaci na port 443 a webové adresy:

1\) [https://prod.eet.cz:443/eet/services/EETServiceSOAP/v3](https://prod.eet.cz:443/eet/services/EETServiceSOAP/v3)

2\) [https://pg.eet.cz:443/eet/services/EETServiceSOAP/v3](https://pg.eet.cz:443/eet/services/EETServiceSOAP/v3)



# Výměna SSL certifikátu k datu 10.9.2018

Dne 10.9.2018 bude vyměněna SSL část certifikátu na straně serverů finanční správy na certifikáty od autority DigiCert. Přesněji pak kořenový certifikát "DigiCert Global Root G2". Tento certifikát musí být přítomen na straně zařízení. Zjistit lze dle postupů níže.

### Postup pro Windows

#### Kontrola:

1. Stiskněte kombinaci kláves "WINDOWS + R".
2. Napište "CERTMGR.MSC".
3. Vyhledejte "KOŘENOVÉ CERTIFIKAČNÍ AUTORITY" a přejěte do podsložky "CERTIFIKÁTY".
4. V seznamu se musí nacházet certifikát s názvem "DigiCert Global Root G2".

#### **Instalace - pokud není přítomno v PC: **

1. Z webu certifikační autority DigiCert stáhněte certifikát s názvem **"DigiCert Global Root G2"** s příponou .crt.
2. Spusťte jej v počítači a stiskněte **"AKTUALIZOVAT CERTIFIKÁT..."**.
3. Zaškrtněte **"AKTUÁLNÍ UŽIVATEL"** a klikněte na **"DALŠÍ"**.
4. Vyberte **"AUTOMATICKY VYBRAT ULOŽIŠTĚ NA ZÁKLADĚ TYPU CERTIFIKÁTU"** a klikněte na **"DALŠÍ"**.
5. Dokončete a systém by Vám měl nahlásit **"IMPORT PROBĚHL ÚSPĚŠNĚ"**.

* https://www.digicert.com/digicert-root-certificates.htm  - adresa pro stažení certifikátu DigiCert

### Postup pro Android

#### **Kontrola:**

1. Ze základní plochy zařízení přejděte do **"MENU-&gt;NASTAVENÍ-&gt;ZABEZPEČENÍ-&gt;DŮVERYHODNÁ POVĚŘENÍ"**.
2. Přejděte do záložky systém, kde se musí nacházet certifikát **"DigiCert Global Root G2"**.

#### Instalace - **pokud není přítomno v **zařízení Android: 

1. Z webu certifikační autority DigiCert stáhněte\(nejlépe na PC\) certifikát s názvem **"DigiCert Global Root G2"** s příponou .crt.
2. Uložený soubor si zašlete na **"GMAIL"**, který máte v zařízení
3. Přílohu emailu** "DigiCertGlobalRootG2.crt" **stáhněte do vnítřní paměti.
4. Ze základní plochy zařízení přejděte do **"MENU-&gt;NASTAVENÍ-&gt;ZABEZPEČENÍ-&gt;INSTALACE Z KARTY SD"**.
5. Vyberte soubor **"DigiCertGlobalRootG2.crt"** a vyplňte název certifikátu\(můžete napsat například DigiCert\).
6. Stiskněte **"OK"**.
7. Proveďte kontrolu v **"MENU-&gt;NASTAVENÍ-&gt;ZABEZPEČENÍ-&gt;DŮVERYHODNÁ POVĚŘENÍ-UŽIVATEL"**.



