<script type="text/javascript" id="MathJax-script" async 
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"> 
</script> 


# Magnetický obvod transformátoru
Magnetický obvod je část transformátoru, která vede magnetický tok vytvořený primárním vinutím a zajišťuje jeho přenos do vinutí sekundárního. Tvoří ho jádro z magneticky měkkého materiálu s vysokou permeabilitou.

Podle tvaru transformátorových plechů a uspořádání cívek se transformátory dělí na jádrové, plášťové a toroidní. Podle počtu fází mohou být jednofázové, trojfázové nebo vícefázové.

Na obrázku níže je jednofázový plášťový, jednofázový jádrový a třífázový jádrový transformátor.

<img width="700" alt="image" src="https://github.com/user-attachments/assets/86cec193-b1de-4e15-bdcc-01eff7978027" />

**Plášťový transformátor**

---

<img width="300" alt="image" src="https://github.com/user-attachments/assets/3bcf5204-3747-4d81-9a24-99833c04d105" />

**Jádrový transformátor**

---

<img width="300" height="421" alt="image" src="https://github.com/user-attachments/assets/7ea7dde7-98a2-465c-ae2c-7ad6c46994a7" />

**Jádrový třífázový**

---

<img width="300" alt="image" src="https://github.com/user-attachments/assets/dbddf1bc-d6b1-4970-93bf-ebbf99617b21" />

**Toroidní transformátor**

---

### Permeabilita
Permeabilita je v elektrotechnice fyzikální veličina, která vyjadřuje vliv určitého materiálu na účinky magnetického pole. Některé materiály tyto účinky zesilují, jiná je zeslabují a existují také prostředí bez tohoto vlivu.

Jako **relativní permeabilita** se označuje podíl permeability daného materiálu a permeability vakua:

$$
\mu_r = \frac{\mu}{\mu_0}
$$

kde:
- $$\mu_r$$ – relativní permeabilita (bezrozměrná veličina)
- $$\mu$$ – absolutní permeabilita materiálu [H/m]
- $$\mu_0$$ – permeabilita vakua [H/m]

Relativní permeabilita většiny látek je velmi blízko hodnoty 1, což odpovídá slabé reakci na magnetické pole.

Na základě velikosti relativní permeability se materiály rozdělují do tří základních skupin:

- **Diamagnetické** ( $$\mu_r < 1$$, $$\chi_m < 0$$, přibližně konstantní)
  - Magnetické pole mírně zeslabují, jsou z něj vytlačovány.
  - Např. kovy 11. a 12. skupiny (Cu, Ag, Au, Hg), dále inertní plyny a většina organických látek.
  - Supravodiče mohou za určitých podmínek zcela zamezit vnikání magnetického pole do svého objemu (Meissnerův jev). V ideálním případě je jejich relativní permeabilita $$\mu_r = 0$$.

- **Paramagnetické** ($$\mu_r > 1$$, $$\chi_m > 0$$, přibližně konstantní)
  - Magnetické pole mírně zesilují, jsou do něj vtahovány.
  - Např. z kovů Al, Mn, Cr, Pt, z nekovů například O (kyslík).

- **Feromagnetické** ($$\mu_r \gg 1$$, závisí na intenzitě magnetického pole)
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


## Magnetizační křivka

<img width="700" alt="image" src="https://github.com/user-attachments/assets/de796452-d9b8-4f5e-ae26-e028466392e5" />

**a) Úzká smyčka**
Malá remanence 
Malá plocha uvnitř smyčky
Materiál se snadno zmagnetuje i odmagnetuje: magneticky měkký materiál
Použití: jádra transformátorů, cívek, motorů a generátorů (křemíková ocel, permalloy, ferity)

**b) Široká smyčka**
Velká remanence
Velká plocha uvnitř smyčky
Materiál si magnetizaci drží a těžko se odmagnetovává: magneticky tvrdý materiál
Použití: permanentní magnety (neodymové a samarium-kobaltové magnety, tvrdé ferity)


## EI plechy
V jádře transformátoru se neustále mění magnetické pole, vytvořené primární cívkou. Kdyby bylo jádro z masivního kusu železa, vznikaly by v takovém jádře silné vířivé proudy, jádro by se zahřívalo a elektrická energie by se místo přenosu z primární na sekundární cívku bez užitku měnila na teplo. V jádru z izolovaných plechů je vznik vířivých proudů silně omezený, tepelné ztráty jsou nepatrné a účinnost velkých energetických transformátorů může dosáhnout až 98%.

Transformátorové plechy se vyrábějí z křemíkové oceli (elektrotechnické oceli), tedy železa legovaného křemíkem, typicky přibližně 1–4,5 % Si (nejčastěji kolem 3 %).
Díky přídavku křemíku má ocel výhodnější vlastnosti:
- Vyšší rezistivita (měrný odpor): omezuje vířivé proudy, a tím ztráty.
- Nižší hysterezní ztráty: užší hysterezní smyčka, snadnější přemagnetování.
- Vysoká relativní permeabilita 

<img width="500" alt="image" src="https://github.com/user-attachments/assets/4106507d-0ef1-41b3-9723-f239b2b546ba" />

<img width="449" alt="image" src="https://github.com/user-attachments/assets/810755ab-1adf-47dc-b16b-e9ec87e37ca8" />

<img width="300"  alt="image" src="https://github.com/user-attachments/assets/f6c35d84-c965-45b2-b841-8d2514ddf9c6" />


## Videa

[![Video na YouTube](https://img.youtube.com/vi/96Vekm8Ws4U/hqdefault.jpg)](https://www.youtube.com/watch?v=96Vekm8Ws4U)

### [Zpět na obsah](../README.md)
