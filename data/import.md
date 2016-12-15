# Hromadné vkládání produktů \(import\)

Funkce hromadného vložení produktů je přístupná v záložce ** Správa &gt; Správa dat**, předpokladem pro úspěšný import je soubor **import.csv** uložený v adresáři **LILKA-data \(pro vkládání\) **ve Vašem zařízení. Hodnoty CSV souboru musejí být odděleny **čárkou** "," a v kódové tabulce **UTF-8**.

Pokud do kolonky **"ID skupiny"** vyplníte skupinu, která ještě neexistuje a provedete úspěšný import, bude tato skupina nově vytvořena. Pokud skupina již existuje, přidají se do ní pouze nově položky, které v ní ještě před importem nebyly. Skupiny lze editovat v **Správa-&gt;Skupiny.**

| Název | Zkratka | ID skupiny | DPH % | Cena | Množství | Jednotka | ČK | Kód zboží | Prodejní množství | Kuchyně | PLU |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| text | text | int/text | decimal\(2\) | decimal\(2\) | decimal\(4\) | text | text | text |  | bit | text |
| Párek v rohlíku | Pár. v r. | 1 | 15,00 | 35 | 1 | Ks | 0123 | 100021 |  | 1 | 101 |
| Párek | parek |  | 15,00 | 35 | 1 | Ks |  |  |  |  |  |
| Malinovka | Malin. | Nápoje | 15,00 | 35 | 1 | Ks |  |  |  |  |  |

* **Název** - název vkládaného produktu
* **Zkratka** - text zobrazený účtence, doporučeno je 20 znaků
* **ID skupiny** - Název skupiny, ve které se zboží bude nacházet. Pokud v LILKA již zadaný název existuje, přiřadí se produkt k dané skupině. V opačném případě bude vytvořena nová skupina s tímto názvem.
* **DPH %** - sazba DPH. Pro přenesenou daň vyplňte příslušný kód např. P-04
* **Cena** - prodejní cena produktu.
* Množství - Jednotkové množství, výchozí 1
* **Jednotka **- jednotka, ke které bude množství přiřazeno
* ČK - Čárový kód
* Kód zboží - Číslo ceníku
* Prodejní množství - prázdný sloupec, výchozí hodnota 1
* **Kuchyně** - 1 - položka patří do kuchyně, 0 - položky nepatří do kuchyně
* PLU - Price Look Up kód - uživatelsky volitelný kód pro rychlé hledání či vkládání pomocí kalkulačky

**\*zvýrazněné sloupce musejí být naplněny, ostatní mohou být prázdné.**

Datové typy:

decimal - číslo v závorce za _decimal_ definuje desetinná místa, podporované formáty: 2; 2.00; 2,00

**Šablona pro hromadný import:**

**Vzorovou tabulku** si můžete stáhnout ve formátu **.xls** [ZDE](https://dokumentace.lilka.cz/import.xls) nebo k nahlédnutí přímo na **Google Drive** [ZDE](https://docs.google.com/spreadsheets/d/1CkQYw7V3bmsWK2f9R8JflQ8GQnmu664KwrTVstGxiCQ/edit?usp=sharing) . Pro úspěšný import do programu lilka je nutné převést soubor do **CSV** formátu v kódování **UTF-8**. Doporučujeme využívat editor tabulek v [Google Drive](https://www.google.cz/intl/cs/drive/). Excel ve výchozím nastavení UTF-8 neexportuje. Pokud si s tímto postupem nevíte rady, kontaktujte nás.



**Import pro Windows 10:**

Po dokončení všech kroků uvedených výše, je nutno z vytvořeného souboru **import.csv** zkopírovat jeho obsah \(hodnoty oddělené čárkou\) do aplikace LILKA. Pole pro vložení zkopírovaného obsahu naleznete v záložce **Správa -&gt; Správa dat **.

