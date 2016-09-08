# Hromadné vkládání produktů (import)

Funkce hromadného vložení produktů je přístupná v záložce ** Správa > Správa dat**, předpokladem pro úspěšný import je soubor **import.csv** uložený v adresáři **LILKA-DATA**. Hodnoty CSV souboru musejí být odděleny **čárkou** "," a v kódové tabulce **UTF-8**. 

Pro správné přiřazení produktů do existujících skupin vyplňte do ID skupiny číslo zobrazené u dané skupiny ve **Správa > Skupiny**. Dále je nutné mít zadány příslušné sazby DPH.

| Název | Zkratka | ID skupiny | DPH % | Cena | Množství | Jednotka | ČK | JKPOV |
| -- |
| text | text | int/text | decimal(2) | decimal(2) | decimal(4)| text | text | text |
| Párek v rohlíku | Pár. v r. | 1 | 15,00 | 35 | 1 | Ks| 0123| 100021 |
| Párek | parek |  | 15,00 | 35 | 1 | Ks| | | |
| Malinovka | Malin. | Nápoje  | 15,00 | 35 | 1 | Ks| | | |

* **Název** - název produktu
* **Zkratka** - text na účtenku, doporučeno je 20 znaků
* ID skupiny - Název nebo číslo pro dohledání skupiny. Pokud v LILKA již zadané ID/název existuje, přiřadí se produkt k vybrané skupině. V opačném případě bude vytvořena skupina s daným názvem/ID.
* **DPH %** - sazba DPH. Pro přenesenou daň vyplňte příslušný kód např. P-04
* **Cena** - prodejní cena produktu.
* Množství - Jednicové množství, výchozí 1
* **Jednotka**
* ČK - Čárový kód
* JKPOV - Číslo ceníku

**Zvýrazněné sloupce musejí být naplněny, ostatní mohou být prázdné.**

Datové typy

decimal - číslo v závorce za *decimal* definuje desetinná místa, podporované formáty: 2; 2.00; 2,00

**Šablona pro hromadný import:**

Excel s připravenou hlavičkou naleznete na [dokumentace.lilka.cz/tabulka-pro-import.xls](http://dokumentace.lilka.cz/tabulka-pro-import.xls). Pro úspěšný import do programu lilka je nutné převést soubor do CSV formátu v kódování UTF-8. Pokud si s tímto postupem nevíte rady, kontaktujte nás.