# Hromadné vkládání produktů (import)

Funkce hromadného vložení produktů je přístupný v záložce ** Správa > Správa dat**, předpokladem pro úspěšný import je soubor **import.csv** uložený v adresáři **LILKA**. Hodnoty CSV souboru musejí být odděleny **čárkou** "," a v kódové tabulce **UTF-8**.

Pro správné přiřazení produktů do existujících skupin vyplňte do ID skupiny číslo zobrazené u dané skupiny ve **Správa > Skupiny**.

| Název | Zkratka | ID skupiny | DPH % | Cena | Množství | Jednotka | ČK | JKPOV |
| -- |
| text | text(50) | int | decimal(2) | decimal(2) | decimal(2)| text | text | text |
| Párek v rohlíku | Pár. v r. | 1 | 15,00 | 35 | 1 | Ks| 0123| 100021 |
| Párek | parek |  | 15,00 | 35 | 1 | Ks| | | |

* **Název** - název produktu
* **Zkratka** - text na účtenku, maximum je 50 znaku
* ID skupiny - vytvoří novou skupinu importovaných produktů. Pokud v ANetCa již zadané ID existuje, přiřadí se produkt k vybrané skupině.
* **DPH %** - sazba DPH. Pro přenesenou daň vyplňte příslušný kód např. P-04
* **Cena** - prodejní cena produktu, bude přiřazena k výchozí cenové kategorii v ANetCa
* Množství - Jednicové množství, výchozí 1
* **Jednotka**
* ČK - Čárový kód
* JKPOV - Číslo ceníku

**Zvýrazněné sloupce musejí být naplněny, ostatní mohou být prázdné.**

Datové typy

decimal - číslo v závorce za *decimal* definuje desetinná místa, podporované formáty: 2; 2.00; 2,00