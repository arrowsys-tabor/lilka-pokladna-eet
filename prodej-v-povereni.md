# Prodej v pověření

V pokladně je možné nastavit Pověřující DIČ, kterému se bude tržba na Finančním portále přiřazovat, tržby Pověřujícího \(osoby která tržby evidovala\) budou na portálu přiřazeny do kolonky tržby v Pověření. Pověřující DIČ se nastavuje v záložce Správa - Nastavení - Firma v poli **Pověřující DIČ.**

Do pole je zapotřebí uvést DIČ Pověřujícího poplatníka, který pověřil evidujícího k evidenci tržeb.

**Příklad - Pověření dle § 9 odst. 1 ZoET**

Řidič zakoupil na čerpací stanici pohonné hmoty v celkové částce 860 Kč včetně DPH, u kterých se uplatňuje základní sazba DPH \(21 %\). Základ daně činil 710,74 Kč a DPH činila 149,26 Kč.

Čerpací stanici provozuje poplatník s DIČ CZ12121218. Pohonné hmoty nejsou jeho vlastní zboží, nýbrž je prodává na základě pověření dle § 9 odst. 1 ZoET. Pověřující poplatník má DIČ CZ00000019.

Pověřený \(provozovatel stanice\) uvede v datové zprávě své DIČ do

položky DIČ poplatníka \(dic\_popl\), dále uvede označení \(číslo\) své provozovny, které mu bylo přiděleno Finanční správou při založení této čerpací stanice jako jeho provozovny v aplikaci EET a zprávu podepisuje svým certifikátem. Do položky DIČ pověřujícího poplatníka \(dic\_poverujiciho\) uvede DIČ pověřujícího, tedy CZ00000019.

![](/assets/poverujici_dic.png)

