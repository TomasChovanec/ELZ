## Rozdělení transformátorů
Rozdělení podle počtu fází:
- jednofázové
- trojfázové

## Rozdělení podle konstrukce magnetického obvodu:
- plášťové
- jádrové
- toroidní

## Podle způsobu chlazení:
- chlazené vzduchem/plynem
- chlazené olejem/jinou kapalinou

## Podle využití transformátoru:
- síťový transformátor
- autotransformátor
- oddělovací transformátor
- svářecí transformátor
- měřicí transformátory

# Konstrukce transformátoru
Základ transformátoru tvoří magnetický a elektrický obvod.

Základem transformátoru jsou dvě cívky (primární a sekundární), nasazené na uzavřeném železném jádře. Vinutí primární cívky se připojuje ke zdroji střídavého proudu, k vinutí sekundární cívky se připojuje spotřebič. Jádro transformátoru je složeno z navzájem izolovaných plechů například z křemíkové oceli. Podle tvaru transformátorových plechů a uspořádání cívek se transformátory dělí na jádrové, plášťové a speciální. Podle počtu fází mohou být jednofázové, trojfázové nebo vícefázové.
V jádře transformátoru se neustále mění magnetické pole, vytvořené primární cívkou. Kdyby bylo jádro z masivního kusu železa, vznikaly by v takovém jádře silné vířivé proudy, jádro by se zahřívalo a elektrická energie by se místo přenosu z primární na sekundární cívku bez užitku měnila na teplo. V jádru z izolovaných plechů je vznik vířivých proudů silně omezený, tepelné ztráty jsou nepatrné a účinnost velkých energetických transformátorů může dosáhnout až 98%! S tak vysokou účinností pracuje jen málokterý stroj!



## Magnetický obvod
Magnetický obvod je složen z orientovaných plechů stažených svorníky.
Tvar magnetického obvodu se mění v závislosti na typu transformátoru. Třífázový
transformátor má magnetický obvod složen ze tří sloupků, v horní a spodní části propojených
spojkami. U transformátorů velkých výkonů je magnetický obvod odstupňován, aby co nejlépe
vyplnil prostor kruhové cívky. Jednofázové transformátory mají magnetické obvody složené
z plechů tvaru E – I, M, L, nebo je magnetický obvod vinutý – toroid, C – jádro.

### Permeabilita
Permeabilita je v elektrotechnice fyzikální veličina, která vyjadřuje vliv určitého materiálu na účinky magnetického pole. Některé materiály tyto účinky zesilují, jiná je zeslabují a existují také prostředí bez tohoto vlivu.

Jako **relativní permeabilita** se označuje podíl permeability daného materiálu a permeability vakua:

$$
\mu_r = \frac{\mu}{\mu_0}
$$

kde:
- $\mu_r$ – relativní permeabilita (bezrozměrná veličina)
- $\mu$ – absolutní permeabilita materiálu [H/m]
- $\mu_0$ – permeabilita vakua [H/m]

Relativní permeabilita většiny látek je velmi blízko hodnoty 1, což odpovídá slabé reakci na magnetické pole.

Na základě velikosti relativní permeability se materiály rozdělují do tří základních skupin:

- **Diamagnetické** ($\mu_r < 1$, $\chi_m < 0$, přibližně konstantní)
  - Magnetické pole mírně zeslabují, jsou z něj vytlačovány.
  - Např. kovy 11. a 12. skupiny (Cu, Ag, Au, Hg), dále inertní plyny a většina organických látek.
  - Supravodiče mohou za určitých podmínek zcela zamezit vnikání magnetického pole do svého objemu (Meissnerův jev). V ideálním případě je jejich relativní permeabilita $\mu_r = 0$.

- **Paramagnetické** ($\mu_r > 1$, $\chi_m > 0$, přibližně konstantní)
  - Magnetické pole mírně zesilují, jsou do něj vtahovány.
  - Např. z kovů Al, Mn, Cr, Pt, z nekovů například O (kyslík).

- **Feromagnetické** ($\mu_r \gg 1$, závisí na intenzitě magnetického pole)
  - Magnetické pole výrazně zesilují, jsou silně přitahovány.
  - Např. Fe (železo), Co (kobalt), Ni (nikl) a jejich slitiny.

| Materiál | Relativní permeabilita μᵣ |
|:---|---:|
| Dusík | 0,999 999 993 |
| Měď | 0,999 991 |
| Voda | 0,999 991 |
| Hliník | 1,000 023 |
| Platina | 1,000 27 |
| Vzduch | 1,000 000 35 |
| Kobalt | 80 až 200 |
| Nikl | až 1 120 |
| Železo | 300–10 000 |
| Permalloy | 50 000–140 000 |

## EI plechy
<img width="500" alt="image" src="https://github.com/user-attachments/assets/4106507d-0ef1-41b3-9723-f239b2b546ba" />

<img width="449" alt="image" src="https://github.com/user-attachments/assets/810755ab-1adf-47dc-b16b-e9ec87e37ca8" />


### Plášťový transformátor
<img width="408"  alt="image" src="https://github.com/user-attachments/assets/f6c35d84-c965-45b2-b841-8d2514ddf9c6" />

### Jádrový transformátor
<img width="346" alt="image" src="https://github.com/user-attachments/assets/3bcf5204-3747-4d81-9a24-99833c04d105" />

### Jádrový třífázový
<img width="400" height="421" alt="image" src="https://github.com/user-attachments/assets/7ea7dde7-98a2-465c-ae2c-7ad6c46994a7" />

### Toroidní transformátor
<img width="400" alt="image" src="https://github.com/user-attachments/assets/dbddf1bc-d6b1-4970-93bf-ebbf99617b21" />



## Elektrický obvod

Elektrický obvod tvoří primární a sekundární vinutí.

U třífázových transformátorů je strana nižšího napětí umístěna blíže k jádru, strana vyššího napětí je vně. Cívky vinutí bývají válcové nebo kotoučové, vzájemně propojené do hvězdy – Y, trojúhelníka – D, nebo lomené hvězdy – Z. Začátky a konce vinutí jsou vyvedeny na víko transformátoru, kde jsou připojeny k izolátorům. Regulaci napětí zajišťuje přepínač nebo přepojovač odboček. Oba obvody, jak elektrický, tak magnetický, bývají uloženy v nádobě a zality transformátorovým olejem. Ten zajišťuje chlazení transformátoru a zlepšuje izolační pevnost. Pro zlepšení odvodu tepla – zvětšení povrchu, bývá nádoba opatřena trubkami nebo radiátory, u velkých výkonů ofukovanými ventilátory. V horní části nádoby bývá zásobník oleje s olejoznakem. Používají se rovněž vzduchem chlazené třífázové transformátory.

Používají se dráty
• izolované smaltem,
• izolované smaltem a opletením hedvábím,
• izolované opletením papírovým páskem. 



### Zapojení cívek třífázového transformátoru
<img width="501" height="265" alt="image" src="https://github.com/user-attachments/assets/2498fb00-eacf-49de-ab6d-797fd8496dfe" />


### Třífázový transformátor zapojený do trojúhelníka
<img width="2560" height="1707" alt="image" src="https://github.com/user-attachments/assets/255413fe-f2bf-47e4-b63b-b1efed56a17b" />
