# CleanCode
- snake case: minden karakter kicsivel írunk, illetve _ karakter kell bele, általában python, java,javascript, typescriptben jöhet veled szembe, illetve adatbázisban tábla létrehozáskor stb
- Kebab case: ugyanugy kicsi karakterekkel kell írni, csak - jellel, legtöbbször az url-ben találkozhatunk vele
- Camel case: a kezdő szó első betűje mindig kicsi, majd az utána következő szavak kezdőbetűje mindig nagy és egybeírjuk. java, javascript, typescriptben találkozhatunk velük, pl method készítésekor
- Pascal case: Minden kezdőbetű nagy, ezt kb az összes programozási nyelv elfogadja
## Script írási szabályok
-A script átláthatóságának érdekében fontos odafigyelni, hogy az elnevezések pontosan írják le azt, amit éppen csinál az adott dolog
-A sok commentelés nem megengedett, hisz kuszává teszi a kódot, fontos, hogy csak akkor használj commentelést a kódban, ha a annak működése nem egyértelmű, illetve elfelejtenéd idővel, hogy mit miért csináltál, de ne legyen sok comment benne.
-Programegységre való széntbontás: A programok betöltése miatt érdemes felülről->alúlra írni, így átláthatóvá válik a kód pl: a deklarációkat legfelülre rakjuk, majd a metódusok, majd a végrehajtásuk, illetve kiírásuk következik sorrendben. Mindegyik kap egy szekciót
-A whitespacek hazsnálata a kódban: az átláthatóság érdekében, érdemes üres sorokkal és spacekkel tagolni a kódot.
-A félrevezethető elnevezéseket, kerüljük. Igyekezzünk igéket használni, illetve pontos megnevezéseket a metodusoknak stb, hogy elkerüljük a félreértéseket.
-Kis lépésekben építsük fel a programot (Agilis fejlesztési módszer), hogy elkerüljük a felnem használt utasítások,eljárásokat. Ez lehetővéteszi, hogy dinamikusan és egyedileg tudunk reagálni az új feltételekre
-Ne duplikálj semmit
-Lehetőleg a kódunkban ne legyenek 5-20 sornál több metódusok, mert az átláthatóságot rombolja 
-A deklarálás is legyen lényegretörő, hisz később nem biztos, hogy tudni fogod, hogy mit szerettél volna kihozni belőle
-OOP szemlélet az újrafelhasználhatóságot segíti elő
