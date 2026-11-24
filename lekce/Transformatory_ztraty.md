<script type="text/javascript" id="MathJax-script" async 
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"> 
</script> 


# Ztráty, účinnost a chlazení transformátoru

Transformátor patří k nejúčinnějším strojům vůbec. Velké transformátory mají účinnost přes 99 %. Přesto se ztrátami zabýváme podrobně: transformátor je připojený k síti nepřetržitě, 8760 hodin ročně, a v síti jich pracují desetitisíce. I malé ztráty se tak sčítají do velkého množství energie. Navíc se všechny ztráty mění v **teplo**, které musíme z transformátoru odvést.

## Energetická bilance

<img width="600" alt="image" src="https://github.com/user-attachments/assets/5ca57863-4430-4ec1-aa22-ad552b481f9f" />

Příkon $$P_1$$, který transformátor odebírá ze sítě, se rozdělí na výkon do zátěže $$P_2$$ a na ztráty:

$$
\large P_1 = P_2 + \Delta P_{Fe} + \Delta P_{Cu}
$$

Ztráty dělíme na dvě skupiny, které přesně odpovídají prvkům [náhradního schématu](Transformatory_nahradni_schema.md):

| | Ztráty v železe $$\Delta P_{Fe}$$ | Ztráty v mědi $$\Delta P_{Cu}$$ |
|---|---|---|
| kde vznikají | v magnetickém obvodu (jádře) | ve vodičích primárního a sekundárního vinutí |
| na čem závisí | na **napětí** (magnetickém toku) a frekvenci | na **proudu**, tedy na zatížení ($$\sim I^2$$) |
| při provozu | **stálé**: jsou stejné naprázdno i při plném zatížení | **proměnné**: rostou s druhou mocninou proudu |
| jak je změříme | měřením **naprázdno**: $$P_0 \approx \Delta P_{Fe}$$ | měřením **nakrátko**: $$P_k \approx \Delta P_{Cu}$$ |

## Účinnost

Účinnost je poměr výkonu a příkonu:

$$
\large \eta = \frac{P_2}{P_1} = \frac{P_2}{P_2 + \Delta P_{Fe} + \Delta P_{Cu}}
$$


## Ztráty v železe

Ztráty v železe vznikají ve střídavém magnetickém poli jádra. Mají dvě složky:

- **Hysterezní ztráty:** při každé periodě se magnetické domény v plechu přemagnetují tam a zpět. Spotřebovaná energie odpovídá ploše hysterezní smyčky a ztráty rostou úměrně frekvenci. Snižují se použitím **magneticky měkké** oceli s úzkou hysterezní smyčkou (křemíková ocel, orientované plechy).

<img width="258" height="243" alt="image" src="https://github.com/user-attachments/assets/d5939b01-c5ef-48ad-87e8-92b2a6b4f75f" />

- **Ztráty vířivými proudy:** proměnný tok indukuje přímo v železe jádra napětí, které v něm vyvolá vířivé proudy, a ty jádro zahřívají. Ztráty rostou s druhou mocninou frekvence i tloušťky plechu. Snižují se tím, že je jádro **složené z tenkých plechů** (asi 0,23 až 0,35 mm) navzájem izolovaných, a přidáním křemíku, který zvyšuje měrný odpor oceli. Podrobněji viz kapitola [Magnetický obvod transformátoru](Transformatory_magneticky_obvod.md).

Obě složky rostou přibližně s druhou mocninou magnetické indukce, tedy i napětí. Při jmenovitém napětí jsou ztráty v železe **stálé**, ať transformátor zatížíme jakkoli.

## Ztráty ve vinutí

Ztráty ve vinutí (často se jim říká ztráty v mědi, i když vinutí může být hliníkové) jsou **Jouleovy ztráty** v odporu vodičů:

$$
\large \Delta P_{Cu} = R_1 \cdot I_1^2 + R_2 \cdot I_2^2
$$


## Chlazení transformátoru

Všechny ztráty se mění v teplo. Kdyby se neodvádělo, teplota vinutí by rostla a **izolace by rychle stárla**. Životnost izolace je silně závislá na teplotě: podle často uváděného pravidla zvýšení trvalé teploty zhruba o 6 až 8 K zkrátí její životnost přibližně na polovinu. Teplota je proto hlavní veličina, která omezuje výkon transformátoru. Transformátor stejné velikosti s lepším chlazením může přenášet větší výkon.

Teplo vzniká v jádře a ve vinutí. Odtud ho **chladivo** (vzduch nebo olej) přenáší na povrch transformátoru a z povrchu do okolního vzduchu (nebo vody).

### Suché transformátory

Vinutí je zalité v pryskyřici nebo izolované lakem a chladí se přímo **vzduchem**. Používají se tam, kde by olej představoval riziko požáru nebo úniku: v budovách, nemocnicích, obchodních centrech, metru. Izolace snese vyšší teploty než olejová (běžně teplotní třída F, tj. 155 °C, nebo H, tj. 180 °C), ale chlazení vzduchem je méně účinné. Proto jsou suché transformátory větší a dražší.

<img width="460" alt="image" src="https://github.com/user-attachments/assets/67568571-c76a-4c46-8cb3-b0197cb389c7" />

### Olejové transformátory

Jádro a vinutí jsou ponořené v nádobě s **transformátorovým olejem**, který má dvě funkce:

1. **izoluje**: má mnohem větší elektrickou pevnost než vzduch,
2. **chladí**: ohřátý olej stoupá vzhůru, předá teplo stěnám nádoby nebo radiátorům, ochladí se a klesá zpět dolů. Vzniká přirozený oběh.

Olej při ohřátí zvětšuje objem. Podle toho, jak se s tím transformátor vyrovná, rozlišujeme:

- **transformátory s konzervátorem**: nad nádobou je vyrovnávací nádržka (konzervátor), do které olej při ohřátí vytéká. V potrubí mezi nádobou a konzervátorem bývá **plynové (Buchholzovo) relé**, které zachytí plyny vznikající při vnitřní poruše a transformátor odpojí,
- **hermetické transformátory**: nádoba je zcela uzavřená a má zvlněné (vlnovcové) stěny, které se při změně objemu oleje pruží. Olej nepřichází do styku se vzduchem, a proto méně stárne. Dnes se tak vyrábí většina distribučních transformátorů.

<img width="400" alt="Olejový distribuční transformátor 20 kV s konzervátorem v trafostanici" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Netzstation_Trafo.jpg/960px-Netzstation_Trafo.jpg" />

*Olejový distribuční transformátor 20 kV v trafostanici. Nádoba má chladicí žebra, vlevo nahoře je vyrovnávací nádržka (konzervátor). Foto: MdE, [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Netzstation_Trafo.jpg), CC BY-SA 3.0.*

<img width="480" alt="image" src="https://github.com/user-attachments/assets/54892066-7e64-4d7c-a7d3-f03a12c968bd" />

*Požár olejového transformátoru. Zdroj: https://www.pozary.cz/clanek/11929-pozar-transformatoru-na-rakovnicku/*

## Kontrolní otázky

1. Jaké dvě skupiny ztrát v transformátoru rozlišujeme? Na čem závisí každá z nich?
1. Čím se snižují ztráty hysterezí a čím ztráty vířivými proudy?
1. Proč je jádro složené z tenkých izolovaných plechů?
1. Jak se změní ztráty ve vinutí, když zatížení klesne na polovinu?
1. Proč se u distribučních transformátorů klade důraz hlavně na malé ztráty naprázdno?
1. Jaké dvě funkce má olej v transformátoru?
1. K čemu slouží plynové (Buchholzovo) relé?

### [Zpět na obsah](../README.md)
