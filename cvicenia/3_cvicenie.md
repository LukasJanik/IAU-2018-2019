# 1. Kto prežije?
Spomínate si ešte na dáta z Titanicu? Porovnajte dva tutoriály, ktoré tentokrát na prieskumnú analýzu dát (a ich čistenie) nepoužívajú Excel, ale Python:
https://www.kaggle.com/startupsci/titanic-data-science-solutions
https://github.com/donnemartin/data-science-ipython-notebooks/blob/master/kaggle/titanic.ipynb

Všimnite si mieru podrobnosti sprievodného textu - neopisuje len pozorovania, ale aj rozhodnutia pre ďalšie kroky dátovej analýzy a objavovania znalostí.


# 2. Analýza údajov o nadváhe a obezite svetovej populácie
[https://ourworldindata.org/obesity](https://ourworldindata.org/obesity)

1. Z internetovej stránky vyššie získajte údaje o obezite vo formáte CSV. Zaujíma nás podiel ľudí s nadváhou - obezitou v celej populácii.
2. Načitajte a zobrazte dané údaje pomocou knižnice pandas
3. Vyberte údaje pre *Severnú Ameriku a Európu*
4. Vykreslite graf priebehu podielu obéznej populácie v čase pomocou knižnice `matplotlib` alebo `seaborn`
5. Pridajte do tohto grafu trendovú čiaru pomocou lineárnej regresie
6. Analyzujte rovnicu výslednej krivky vo formáte y=ax+b. Aký bude (podľa tohto jednoduchého lineárneho modelu) podiel obéznej populácie v ďalekej budúcnosti (napr. V roku 2200)?


# 3. Analýza údajov o krajinách
https://www.kaggle.com/fernandol/countries-of-the-world

1. Stiahnite si údaje o krajinách vo formáte CSV. Dajte si pozor na správny formát dát (napr. desatinná čiarka vs. bodka, biele znaky v reťazcoch). V prípade potreby transformujte dáta do požadovaného formátu.
2. Overte, či sú v dátach chýbajúce hodnoty.
3. Pozrite sa na distribúciu HDP na obyvateľa (`GDP ($ per capita)`) vzhľadom na jednotlivé svetové regióny; využite pri tom boxplot. Koľko krajín je v jednotlivých regiónoch? Koľká najbohatšia krajina (na základe HDP na obyvateľa) je Slovensko? Koľko percent z priemeru európskych krajín predstavuje slovenské HDP na obyvateľa?
4. Porovnajte mieru gramotnosti medzi krajinami bývalej Východnej a Západnej Európy. Ktorá krajina má najnižšiu, a ktorá najvyššiu mieru gramotnosti? Vieme na základe dát (a podporných vizualizácií) povedať, či je významný rozdiel v miere gramotnosti medzi Východnou a Západnou Európou?
5. Pozrite sa na hustotu obyvateľstva v krajinách Európy. Vyskytujú sa v dátach nejaké vychýlené (extrémne vysoké alebo extrémne nízke hodnoty)? Zamyslite sa, čo by ste s nimi pri analýze spravili. Aký majú efekt na priemer hustoty obyvateľstva v Európe? Vyskúšajte hustotu obyvateľstva vizualizovať pomocou boxplotu, histogramu aj stĺpcového diagramu. Pri stĺpcovom diagrame ofarbite krajiny podľa toho, či patria do Východnej alebo Západnej Európy. Aké sú výhody/nevýhody daných typov grafov, resp. kedy je vhodné ktorý použiť?
6. Analyzujte vzťahy medzi numerickými atribútmi v dátach. Využite pri tom `pairplot` z knižnice `seaborn`. Pozrite sa bližšie na koreláciu medzi HDP na obyvateľa (`GDP ($ per capita)`) a pôrodnosťou (`Birthrate`), resp. počtom mobilov v populácii (`Phones (per 1000)`) a pôrodnosťou. Ako ju môžeme interpretovať?