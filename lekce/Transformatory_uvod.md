<script type="text/javascript" id="MathJax-script" async 
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"> 
</script> 

# Transformátor

Transformátor je elektrický, netočivý stroj. Pomocí elektromagnetické indukce mění elektrickou energii jedněch parametrů na el. energii druhých parametrů - těmito parametry je napětí a proud, frekvence se nemění. Výkon se také nemění, jen se zmenší o ztráty transformátoru.

Používají se nejčastěji pro přeměnu střídavého napětí nebo na galvanické oddělení obvodů.

<img width="800" alt="image" src="https://github.com/user-attachments/assets/0ae56e65-800d-4184-9ab1-5f791869f5f1" />

## Princip činnosti

Transformátor má dvě cívky (vinutí) na společném železném jádru. Primární vinutí s N₁ závity se připojí ke střídavému napětí U₁. Protéká jím magnetizační proud, který v jádru vytvoří střídavý magnetický tok Φ. Tento tok prochází i sekundárním vinutím s N₂ závity a indukuje v něm napětí U₂.

<img width="550" alt="image" src="https://github.com/user-attachments/assets/de6c71e7-bba1-4593-98a1-b12cb36a7810" />

## Elektromagnetická indukce

Elektromagnetická indukce je jev, při kterém ve vodiči dochází ke vzniku indukovaného elektromotorického napětí Ui a v důsledku časové změny magnetického indukčního toku, tj. důsledkem umístění vodiče v měnícím se magnetickém poli.

Jev byl objeven roku 1831 Michaelem Faradayem.

Velikost indukovaného napětí závisí na velikosti **změny** magnetického pole a **rychlosti** této změny.

$$
\Large U_i = - \frac{d\Phi}{dt}
$$

Pro cívku s N závity pak:

$$
\Large U_i = -N \cdot \frac{d\Phi}{dt}
$$

### Simulace elektromagnetické indukce

[![Faradayův zákon – PhET](https://phet.colorado.edu/sims/html/faradays-law/latest/faradays-law-600.png)](https://phet.colorado.edu/sims/html/faradays-law/latest/faradays-law_all.html)

Napětí a proud, které vznikají při elektromagnetické indukci, nazýváme indukované. Elektromagnetická indukce se využívá  například:
- v transformátorech: střídavý proud v primární cívce vytváří proměnný tok v jádře, který indukuje napětí v sekundární cívce; poměr napětí je dán poměrem počtu závitů,
- v indukčních vařičích: cívka pod sklokeramickou deskou vytváří rychle se měnící magnetické pole, které v dně hrnce indukuje vířivé proudy, a hrnec se ohřívá přímo,
- v generátorech a alternátorech: v elektrárnách i v automobilech se pohybem cívky v magnetickém poli vyrábí střídavé napětí,
- v bezdrátovém nabíjení: například u telefonů nebo elektrických zubních kartáčků se energie přenáší bez kontaktu mezi dvěma cívkami,

<img width="800"  alt="image" src="https://github.com/user-attachments/assets/7463cbc2-b387-4ae7-8715-50b014ffa5a4" />

## Indukované napětí

Při sinusovém průběhu toku platí:

Φ = Φmax · sin ωt

Podle Faradayova zákona se ve vinutí o N závitech indukuje napětí

Ui = −N · dΦ/dt = −N · ω · Φmax · cos ωt

Indukované napětí je tedy derivací toku, takže je oproti toku posunuté o 90°. Když má tok maximum, je napětí nulové, a když tok prochází nulou, je napětí největší.

Amplituda indukovaného napětí je Um = ω · N · Φmax = 2π · f · N · Φmax. Efektivní hodnotu dostaneme dělením √2:

**Ui = 4,44 · f · N · Φmax**

Konstanta 4,44 vychází z 2π/√2. Vzorec platí pro primární i sekundární vinutí. Při zanedbání odporu vinutí je indukované napětí na primáru přibližně rovno přivedenému napětí (u₁ ≈ −e₁).

## Převod transformátoru

Tok Φ je v obou vinutích stejný, liší se jen počet závitů. Po dosazení do vzorce pro U a vydělení obou rovnic dostaneme převod:

**p = N₁ / N₂ = U₁ / U₂**

U ideálního transformátoru se výkon nemění (U₁ · I₁ = U₂ · I₂), proto pro proudy platí opačný poměr:

**p = N₁ / N₂ = U₁ / U₂ = I₂ / I₁**

Podle převodu rozlišujeme tři druhy transformátorů:

- p > 1: snižující transformátor, U₂ < U₁ a I₂ > I₁
- p < 1: zvyšující transformátor, U₂ > U₁ a I₂ < I₁
- p = 1: oddělovací transformátor, napětí se nemění, ale vstup a výstup jsou galvanicky oddělené


<iframe
  src="https://tomaschovanec.github.io/ELZ/files/trafo_applet.html"
  width="100%" height="620"
  style="border:0; max-width:900px;"
  loading="lazy"
  title="Simulace ideálního transformátoru">
  </iframe>

## Videa

[![FS-4.6. Transformátor | Fyzika SŠ](https://img.youtube.com/vi/Id1grnHkHeY/hqdefault.jpg)](https://www.youtube.com/watch?v=Id1grnHkHeY)

[![Pokusničení – Jak funguje transformátor?](https://img.youtube.com/vi/vdDFAl66rNg/hqdefault.jpg)](https://www.youtube.com/watch?v=vdDFAl66rNg)

## Otázky k opakování

### Teorie

**1. Která veličina se při transformaci nemění?**

- A) napětí
- B) proud
- C) frekvence
- D) počet závitů

<details>
<summary>Zobrazit odpověď</summary>
<p><b>C)</b> Frekvence se nemění. Napětí a proud se mění podle převodu a výkon se zmenší jen o ztráty.</p>
</details>

---

**2. Na čem závisí velikost indukovaného napětí?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Na velikosti změny magnetického pole (toku) a na rychlosti této změny. Čím rychleji se tok mění, tím větší napětí se indukuje.</p>
</details>

---

**3. Jaké je napětí ve chvíli, kdy má magnetický tok maximum? Proč?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Napětí je v tu chvíli nulové. Indukované napětí je derivací toku, takže je oproti toku posunuté o 90°. V maximu se tok na okamžik přestává měnit, a proto se neindukuje žádné napětí. Největší je napětí tam, kde tok prochází nulou a mění se nejrychleji.</p>
</details>

---

**4. Odkud se ve vzorci Ui = 4,44 · f · N · Φmax bere konstanta 4,44?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Amplituda napětí je Um = 2π · f · N · Φmax. Efektivní hodnotu dostaneme dělením √2, takže konstanta je 2π / √2 ≈ 4,44.</p>
</details>

---

**5. Jaké tři druhy transformátorů rozlišujeme podle převodu?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Snižující (p &gt; 1), zvyšující (p &lt; 1) a oddělovací (p = 1).</p>
</details>

---

**6. Proč má snižující transformátor na sekundární straně větší proud než na primární?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Výkon se (u ideálního transformátoru) nemění, platí U₁ · I₁ = U₂ · I₂. Pokud se napětí sníží, musí se proud o stejný poměr zvýšit.</p>
</details>

---

### Výpočty

**7. Transformátor má N₁ = 500 závitů a N₂ = 50 závitů. Primární vinutí je připojeno na U₁ = 230 V. Urči převod p a sekundární napětí U₂.**

<details>
<summary>Zobrazit odpověď</summary>
<p>p = N₁ / N₂ = 500 / 50 = <b>10</b><br>
U₂ = U₁ / p = 230 / 10 = <b>23 V</b><br>
Jde o snižující transformátor.</p>
</details>

---

**8. Zvyšující transformátor má N₁ = 200 závitů a N₂ = 1000 závitů. Na primár přivedeme U₁ = 24 V. Urči převod a napětí U₂.**

<details>
<summary>Zobrazit odpověď</summary>
<p>p = 200 / 1000 = <b>0,2</b><br>
U₂ = U₁ / p = 24 / 0,2 = <b>120 V</b></p>
</details>

---

**9. Ideální transformátor má převod p = 5 a sekundárním vinutím protéká proud I₂ = 2 A. Jaký proud teče primárním vinutím?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Ze vztahu p = I₂ / I₁ plyne I₁ = I₂ / p = 2 / 5 = <b>0,4 A</b>.</p>
</details>

---

**10. Ideální transformátor 230 V / 23 V odebírá z primáru proud 0,5 A. Jaký výkon přenáší a jaký proud poteče spotřebičem na sekundáru?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Výkon: S = U₁ · I₁ = 230 · 0,5 = <b>115 VA</b><br>
Proud na sekundáru: I₂ = S / U₂ = 115 / 23 = <b>5 A</b></p>
</details>

### [Zpět na obsah](../README.md)
