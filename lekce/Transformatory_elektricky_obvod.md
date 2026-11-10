# Vinutí transformátoru

Vinutí transformátoru je tvořeno měděnými nebo hliníkovými cívkami navinutými na izolační kostře kolem magnetického jádra. Slouží k přenosu elektrické energie mezi obvody prostřednictvím elektromagnetické indukce.

## Hlavní části a princip

- Primární vinutí: Přivádí se do něj vstupní střídavé napětí, přičemž protékající proud vytváří střídavý magnetický tok v jádře.
- Sekundární vinutí: V něm se díky měnícímu se magnetickému toku indukuje (vytváří) výstupní střídavé napětí (podle Faradayova zákona elektromagnetické indukci).

## Materiály a provedení

- Materiál vodičů: Nejčastěji se používá měď (lepší vodivost, menší rozměry) nebo hliník (nižší cena a hmotnost).
- Izolace: Závity jsou od sebe a od jádra odděleny lakem, papírem, fóliemi nebo speciálními pryskyřicemi, aby nedošlo k mezizávitovému zkratu.
- Zapojení vinutí: V třífázových soustavách se nejčastěji zapojují do hvězdy (Y/Yn) nebo do trojúhelníku (D), případně jejich kombinacemi.

Používají se vodiče:
- izolované smaltem,
- izolované smaltem a opletením hedvábím,
- izolované opletením papírovým páskem.
  
<img width="250" alt="image" src="https://github.com/user-attachments/assets/779ab976-601d-4ebc-a342-8740423fd880" />
<img width="300" alt="image" src="https://github.com/user-attachments/assets/3bb98809-f4ae-41cc-a6ad-aa5306b388da" />
<img width="200" alt="image" src="https://github.com/user-attachments/assets/aef36cf6-d620-4470-9fd2-8c8d3ba0b03d" />

## Tvar cívek

Tvar cívek závisí na způsobu chlazení transformátoru.

### Válcová cívka
Vinutí je navinuto ve vrstvách do válce, vinutí nn a vn jsou soustředná a leží ve válcích kolem sloupku jádra.
Používá se u suchých transformátorů.
Cívky se zalévají do pryskyřice (epoxid), která je izoluje a chrání.
Chlazení vzduchem.

### Kotoučová cívka
Vinutí je rozděleno na ploché kotouče (sekce) naskládané nad sebou, často se střídají kotouče nn a vn.
Mezi kotouči jsou mezery
Používá se u transformátorů s olejovým chlazením.
Mezerami mezi kotouči proudí chladicí olej, který odvádí teplo.

<img width="449"  alt="image" src="https://github.com/user-attachments/assets/f38a7ab2-44d3-4f5d-a0df-0e751f8aa922" />

[![Video na YouTube](https://img.youtube.com/vi/_yRu-a9HjXI/hqdefault.jpg)](https://youtu.be/_yRu-a9HjXI)

## Zapojení cívek třífázového transformátoru

**Vinutí spojená do hvězdy** – značí se **Y**, cívky všech tří fází jsou spojeny paralelně. Vyvedením středního vodiče ze společného uzlu získáváme soustavu dvou napětí – sdružené (mezi fázemi) a fázové (mezi fázovým a středním vodičem)

**Vinutí spojená do trojúhelníku** – značí se **D**, cívky všech tří fází jsou spojeny do série – získáváme pouze sdružené napětí.

**Vinutí spojená do lomené hvězdy** – značí se **Z**. Cívky každé fáze jsou rozděleny na polovinu a jedna polovina je posunuta na následující sloupek magnetického obvodu. Používá se pouze na výstupní straně transformátoru pro vyrovnání nerovnoměrného zatížení jednotlivých fází.

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

### Způsoby přepínání

| Typ | Zkratka | Princip | Použití |
|---|---|---|---|
| Přepínání **bez zatížení** | PBZ | Transformátor se odpojí od sítě a odbočka se přepne ručně (nebo pohonem) | distribuční transformátory, regulace se mění jen zřídka (sezónně) |
| Přepínání **pod zatížením** | PPZ | Přepínač mění odbočky za provozu, aniž by se přerušil proud (používá přechodové odpory nebo tlumivky, aby nevzniklo zkratování závitů) | velké výkonové a regulační transformátory v rozvodnách |



### [Zpět na obsah](../README.md)
