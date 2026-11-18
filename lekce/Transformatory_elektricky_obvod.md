<script type="text/javascript" id="MathJax-script" async 
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"> 
</script> 

# Vinutí transformátoru

Vinutí transformátoru je tvořeno měděnými nebo hliníkovými cívkami navinutými na izolační kostře kolem magnetického jádra. Slouží k přenosu elektrické energie mezi obvody prostřednictvím elektromagnetické indukce.

## Hlavní části a princip

- Primární vinutí: Přivádí se do něj vstupní střídavé napětí, přičemž protékající proud vytváří střídavý magnetický tok v jádře.
- Sekundární vinutí: V něm se díky měnícímu se magnetickému toku indukuje (vytváří) výstupní střídavé napětí (podle Faradayova zákona elektromagnetické indukci).

## Materiály a provedení

### Vodiče
Nejčastěji se používá měď (lepší vodivost, menší rozměry) nebo hliník (nižší cena a hmotnost).

Podle tvaru dělíme vodiče na:

- **Kruhový** vodič (drát) se používá u malých transformátorů a u vinutí vn s malým proudem.
- **Profilový** (plochý) vodič lépe vyplní prostor cívky. Je nejběžnější u distribučních a výkonových transformátorů.

<img width="300" alt="image" src="https://github.com/user-attachments/assets/fa854ec8-5078-4e2d-9348-3bb8921b9e29" />


Při velkých proudech se vodič dělí na více tenčích paralelních vodičů, protože masivní vodič by měl velké ztráty vířivými proudy. U velkých transformátorů se používá transponovaný vícesvazkový vodič (CTC). Je to svazek tenkých izolovaných vodičů, které se průběžně překřižují, aby se proud rozdělil rovnoměrně.

<img width="300"  alt="image" src="https://github.com/user-attachments/assets/11e5077b-143a-48f7-b45b-a74a9b9295cb" />


### Izolace
Závity jsou od sebe a od jádra odděleny lakem, papírem, fóliemi nebo speciálními pryskyřicemi, aby nedošlo k mezizávitovému zkratu.

Používají se vodiče:
- izolované smaltem,
- izolované smaltem a opletením hedvábím,
- izolované opletením papírovým páskem.
  
<img width="270" alt="image" src="https://github.com/user-attachments/assets/779ab976-601d-4ebc-a342-8740423fd880" />
<img width="210" alt="image" src="https://github.com/user-attachments/assets/aef36cf6-d620-4470-9fd2-8c8d3ba0b03d" />
<img width="280" alt="image" src="https://github.com/user-attachments/assets/3bb98809-f4ae-41cc-a6ad-aa5306b388da" />


## Tvar cívek

Tvar a typ vinutí závisí hlavně na napětí, proudu a výkonu transformátoru, částečně i na způsobu chlazení.

### Válcové vinutí
Válcové (vrstvové) vinutí je navinuto ve vrstvách do válce. Vinutí nn a vn jsou soustředná kolem sloupku jádra. Používá se u menších a středních transformátorů, suchých i olejových, často pro nn. U suchých transformátorů se vinutí může zalévat do epoxidové pryskyřice. Chlazení zajišťují mezery mezi vrstvami.

### Kotoučové vinutí
Kotoučové vinutí je rozděleno na ploché kotouče naskládané nad sebou. Používá se hlavně pro vn u větších olejových transformátorů. Mezerami mezi kotouči proudí olej a odvádí teplo. Kotouče také dobře snášejí vysoké napětí a zkratové síly.

<img width="449"  alt="image" src="https://github.com/user-attachments/assets/f38a7ab2-44d3-4f5d-a0df-0e751f8aa922" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/5ab8929d-eb6e-4f6c-becf-30e504db24a9" />


## Zapojení cívek třífázového transformátoru

**Vinutí spojená do hvězdy** – značí se **Y**, začátky (nebo konce) všech tří cívek jsou spojeny do společného uzlu. Vyvedením středního vodiče ze společného uzlu získáváme soustavu dvou napětí – sdružené (mezi fázemi) a fázové (mezi fázovým a středním vodičem)

**Vinutí spojená do trojúhelníku** – značí se **D**, cívky všech tří fází jsou spojeny do uzavřeného trojúhelníku – získáváme pouze sdružené napětí.

**Vinutí spojená do lomené hvězdy** – značí se **Z**. Cívky každé fáze jsou rozděleny na polovinu a jedna polovina je posunuta na následující sloupek magnetického obvodu. Používá se typicky na straně nízkého napětí distribučního transformátoru pro vyrovnání nerovnoměrného zatížení jednotlivých fází.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/c6ff1724-e243-44e7-a7c6-cee6e2e4201d" />

### Třífázový transformátor zapojený do trojúhelníka
<img width="700" alt="image" src="https://github.com/user-attachments/assets/255413fe-f2bf-47e4-b63b-b1efed56a17b" />

## Odbočky transformátoru
Odbočka je vývod z vinutí vyvedený z určitého místa mezi začátkem a koncem. Umožňuje použít jen část vinutí, tedy změnit počet závitů a tím i převod transformátoru:

U₂ / U₁ = N₂ / N₁

Odbočky umožňují:

**Regulace napětí:** napětí v síti kolísá a při zatížení vzniká na vinutích úbytek. Odbočkami se sekundární napětí dorovná na požadovanou hodnotu.

**Přizpůsobení různým sítím:** jeden transformátor lze použít pro různá vstupní napětí (např. 220 / 230 / 240 V).

**Více výstupních napětí:** u malých transformátorů bývají odbočky na sekundáru (např. 6 / 9 / 12 V).

**Symetrické napětí:** odbočka přesně uprostřed vinutí (střední vývod) umožňuje získat dvě stejná napětí vůči společnému bodu, např. 2 × 9 V .

<img width="371" alt="image" src="https://github.com/user-attachments/assets/a6a2650c-0952-450a-b8ce-a1e97d3c159a" />

Při regulaci na primární straně platí: více primárních závitů znamená nižší sekundární napětí (a naopak).

Příklad: Transformátor 22 kV / 400 V má odbočky ±2 × 2,5 %. Pokud je napětí v síti trvale vyšší (např. 22,55 kV, tedy +2,5 %), přepne se na odbočku s více závity (+2,5 %) a sekundární napětí zůstane na 400 V.

## Regulace napětí

Napětí v síti kolísá podle toho, kolik odběratelé zrovna odebírají. Při zatížení navíc vzniká úbytek napětí na samotném transformátoru (viz [náhradní schéma](Transformatory_nahradni_schema.md)) i na vedení. Odběratel ale potřebuje napětí v předepsaných mezích. Napětí proto regulujeme **změnou převodu**, tedy změnou počtu závitů pomocí **odboček** (princip odboček viz [Vinutí transformátoru](Transformatory_elektricky_obvod.md)):

$$
\large U_2 = U_1 \cdot \frac{N_2}{N_1}
$$

Odbočky bývají na **vinutí VN**, protože:

- teče jím menší proud, takže přepínač i kontakty mohou být menší,
- má více závitů, takže jeden závit představuje menší část napětí a regulace může být jemnější.

Na straně VN platí: **více závitů primáru znamená nižší sekundární napětí**. Když je napětí v síti vysoké, přepneme na odbočku s více závity, a naopak.

<iframe src="https://tomaschovanec.github.io/ELZ/files/regulace-odbockami.html" width="100%" height="640" style="border:0"></iframe>

### Přepínání bez zatížení

Používá se u **distribučních transformátorů 22/0,4 kV**. Transformátor se musí odpojit od sítě, pak se odbočka přepne ručně přepínačem na víku nádoby. Přepíná se zřídka, například při uvedení do provozu nebo po změně poměrů v síti. Typický rozsah je **±2 × 2,5 %**: transformátor 22 ± 2 × 2,5 % / 0,4 kV má pět poloh od −5 % do +5 %.

**Příklad:** Napětí sítě VN v místě transformátoru je trvale 23 kV a transformátor 22/0,4 kV je na střední odbočce. Pak

$$
\large U_2 = 23\,000 \cdot \frac{0{,}4}{22} \approx 418\ \text{V}
$$

Po přepnutí na odbočku +5 % (převod 23,1/0,4 kV) bude $$U_2 = 23\,000 \cdot 0{,}4 / 23{,}1 \approx 398\ \text{V}$$.

### Přepínání pod zatížením

Používá se u **velkých transformátorů v rozvodnách**, například 110/22 kV. Přepínač mění odbočky **za provozu, bez přerušení proudu**. Skládá se ze dvou částí:

- **volič odboček** předem vybere následující odbočku (bez proudu),
- **zatěžovací přepínač** rychle přepne proud na novou odbočku. Při přepnutí jsou na okamžik spojené dvě odbočky a zkrat mezi nimi omezují **přechodové odpory** (nebo tlumivky).

Přepínač ovládá **automatický regulátor napětí**, který měří napětí na straně 22 kV a při odchylce přepne o jeden stupeň. Transformátory 110/22 kV mají typicky převod **110 ± 8 × 2 % / 23 kV**, tedy 17 poloh po 2 %. Distributor tím udržuje napětí v síti 22 kV přibližně v rozmezí 22,8 až 23,8 kV, aby nepřekročilo 24 kV.

> Napětí naprázdno sekundáru bývá o něco vyšší než jmenovité napětí sítě (23 kV místo 22 kV, 0,42 kV místo 0,4 kV). Tím se předem vyrovná úbytek napětí, který vznikne při zatížení.

Při paralelním chodu transformátorů s přepínači odboček musí být oba transformátory vždy **na odpovídajících odbočkách**, jinak mezi nimi teče vyrovnávací proud (viz podmínka č. 1).

## Kontrolní otázky
1. Proč se odbočky pro regulaci napětí umisťují na vinutí VN?
1. Jaký je rozdíl mezi přepínáním odboček bez zatížení a pod zatížením? Kde se které používá?

## Video

[![Video na YouTube](https://img.youtube.com/vi/96Vekm8Ws4U/hqdefault.jpg)](https://www.youtube.com/watch?v=96Vekm8Ws4U)

### [Zpět na obsah](../README.md)
