<script type="text/javascript" id="MathJax-script" async 
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"> 
</script> 

# Transformátor

Transformátor je elektrický, netočivý stroj. Pomocí elektromagnetické indukce mění elektrickou energii  na elektrickou energii jiných parametrů - těmito parametry je napětí a proud, frekvence se nemění. Výkon se také nemění, jen se zmenší o ztráty transformátoru.

Používají se nejčastěji pro změnu velikosti střídavého napětí nebo na galvanické oddělení obvodů.

<img width="800" alt="image" src="https://github.com/user-attachments/assets/0ae56e65-800d-4184-9ab1-5f791869f5f1" />

## Princip činnosti

Transformátor má dvě cívky (vinutí) na společném železném jádru. Primární vinutí s N₁ závity se připojí ke střídavému napětí U₁. Protéká jím magnetizační proud, který v jádru vytvoří střídavý magnetický tok Φ. Tento tok prochází i sekundárním vinutím s N₂ závity a indukuje v něm napětí U₂.

<img width="700" alt="image" src="https://github.com/user-attachments/assets/fbc75d53-6866-4a5c-9a10-d0adf7235559" />

## Elektromagnetická indukce

Elektromagnetická indukce je jev, při kterém ve vodiči dochází ke vzniku indukovaného elektromotorického napětí Ui a v důsledku časové změny magnetického indukčního toku, tj. důsledkem umístění vodiče v měnícím se magnetickém poli.

Jev byl objeven roku 1831 Michaelem Faradayem.

### Faradayův zákon
Hodnota indukovaného napětí je rovna časové změně magnetického toku, který prochází elektrickým obvodem. 

$$
\large u_i = - \frac{d\Phi}{dt}
$$

Pro cívku s N závity pak:

$$
\large u_i = -N \cdot \frac{d\Phi}{dt}
$$

kde:

- $$u_i$$ je okamžitá hodnota indukovaného napětí ve vinutí, jednotka [V],
- $$N$$ je počet závitů vinutí, bez jednotky,
- $$\Phi$$ je magnetický tok procházející vinutím, jednotka [Wb],
- $$t$$ je čas, jednotka [s],
- $$\frac{\mathrm{d}\Phi}{\mathrm{d}t}$$ je rychlost změny magnetického toku, jednotka [Wb/s].
- Znaménko mínus vyjadřuje Lenzův zákon: indukované napětí působí proti změně toku, která ho vyvolala. Jednotky sedí, protože [Wb/s] = [V].

Napětí a proud, které vznikají při elektromagnetické indukci, nazýváme indukované. Elektromagnetická indukce se využívá  například:
- **v transformátorech:** střídavý proud v primární cívce vytváří proměnný tok v jádře, který indukuje napětí v sekundární cívce; poměr napětí je dán poměrem počtu závitů,
- **v generátorech a alternátorech:** v elektrárnách i v automobilech se pohybem cívky v magnetickém poli vyrábí střídavé napětí,
- **v indukčních vařičích:** cívka pod sklokeramickou deskou vytváří rychle se měnící magnetické pole, které v dně hrnce indukuje vířivé proudy, a hrnec se ohřívá přímo,
- **v bezdrátovém nabíjení:** například u telefonů nebo elektrických zubních kartáčků se energie přenáší bez kontaktu mezi dvěma cívkami,

### Simulace elektromagnetické indukce

[![Faradayův zákon – PhET](https://phet.colorado.edu/sims/html/faradays-law/latest/faradays-law-600.png)](https://phet.colorado.edu/sims/html/faradays-law/latest/faradays-law_all.html)

## Indukované napětí transformátoru

Při sinusovém průběhu toku platí:

$$
\large \Phi = \Phi_{max} \cdot \sin \omega t
$$

Podle Faradayova zákona se ve vinutí o N závitech indukuje napětí úměrné **rychlosti změny toku**, tedy jeho derivaci podle času (derivace říká, jak rychle se veličina mění):

$$
\large u_i = -N \cdot \frac{\mathrm{d}\Phi}{\mathrm{d}t} = -N \cdot \frac{\mathrm{d}}{\mathrm{d}t}\left(\Phi_{max} \cdot \sin \omega t\right)
$$

Po derivaci dostaneme:

$$
\large u_i = -N \cdot \omega \cdot \Phi_{max} \cdot \cos \omega t
$$

Amplituda indukovaného napětí je

$$
\large U_imax = \omega \cdot N \cdot \Phi_{max} = 2\pi \cdot f \cdot N \cdot \Phi_{max}
$$

Efektivní hodnotu dostaneme dělením $$\sqrt{2}$$:

$$
\large {U_ief = \frac{U_imax}{\sqrt{2}}}
$$

$$
\large \boxed{U_ief  = 4{,}44 \cdot f \cdot N \cdot \Phi_{max}}
$$

kde:

- $$U_{i\mathrm{ef}}$$ je efektivní hodnota indukovaného napětí ve vinutí [V],
- $$f$$ je frekvence střídavého napájení [Hz],
- $$N$$ je počet závitů vinutí [-],
- $$\Phi_{max}$$ je amplituda magnetického toku v jádru, jednotka weber [Wb].
- Konstanta 4,44 je bezrozměrná, vychází z $$2\pi/\sqrt{2}$$.

Indukované napětí je **derivací toku**, takže je oproti toku **posunuté o 90°**. Když má tok maximum, je jeho změna nulová, a tedy i napětí je nulové. Když tok prochází nulou, mění se nejrychleji, a napětí je proto největší.

<img width="800"  alt="image" src="https://github.com/user-attachments/assets/7463cbc2-b387-4ae7-8715-50b014ffa5a4" />


## Převod transformátoru
Tok $$\Phi$$ je v obou vinutích stejný, liší se jen počet závitů. Po dosazení do vzorce pro $$U$$ a vydělení obou rovnic dostaneme převod:

$$
\large \boxed{p = \frac{N_1}{N_2} = \frac{U_1}{U_2}}
$$

U ideálního transformátoru se výkon nemění ($$U_1 \cdot I_1 = U_2 \cdot I_2$$), proto pro proudy platí opačný poměr:

$$
\large \boxed{p = \frac{N_1}{N_2} = \frac{U_1}{U_2} = \frac{I_2}{I_1}}
$$

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

[![FS-4.6. Transformátor - Fyzika SŠ](https://img.youtube.com/vi/Id1grnHkHeY/hqdefault.jpg)](https://www.youtube.com/watch?v=Id1grnHkHeY)

[![Pokusničení – Jak funguje transformátor?](https://img.youtube.com/vi/vdDFAl66rNg/hqdefault.jpg)](https://www.youtube.com/watch?v=vdDFAl66rNg)

## Otázky k opakování

### Teorie

**Která veličina se při transformaci nemění?**

- A) napětí
- B) proud
- C) frekvence
- D) počet závitů

<details>
<summary>Zobrazit odpověď</summary>
<p><b>C)</b> Frekvence se nemění. Napětí a proud se mění podle převodu a výkon se zmenší jen o ztráty.</p>
</details>

---

**Na čem závisí velikost indukovaného napětí?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Na velikosti změny magnetického pole (toku). Čím více se tok mění, tím větší napětí se indukuje.</p>
</details>

---

**Jaké je napětí ve chvíli, kdy má magnetický tok maximum? Proč?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Napětí je v tu chvíli nulové. Indukované napětí je derivací toku, takže je oproti toku posunuté o 90°. V maximu se tok na okamžik přestává měnit, a proto se neindukuje žádné napětí. Největší je napětí tam, kde tok prochází nulou a mění se nejrychleji.</p>
</details>

---

**Odkud se ve vzorci Ui = 4,44 · f · N · Φmax bere konstanta 4,44?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Amplituda napětí je Um = 2π · f · N · Φmax. Efektivní hodnotu dostaneme dělením √2, takže konstanta je 2π / √2 ≈ 4,44.</p>
</details>

---

**Jaké tři druhy transformátorů rozlišujeme podle převodu?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Snižující (p &gt; 1), zvyšující (p &lt; 1) a oddělovací (p = 1).</p>
</details>

---

**Proč se elektrická energie přenáší na vysokém napětí a ne rovnou na 400/230 V?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Přenášený výkon je P = U · I, takže při stejném výkonu znamená vyšší napětí menší proud. Ztráty na vedení jsou úměrné druhé mocnině proudu (ΔP = R · I²), a proto malý proud ztráty výrazně sníží. Napětí se pak u spotřebitele transformuje zpět na bezpečnou hodnotu.</p>
</details>

---

**Funguje transformátor na stejnosměrné napětí?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Ne. Stejnosměrný proud vytvoří neměnný magnetický tok, takže dΦ/dt = 0 a v sekundáru se neindukuje žádné napětí. Primární vinutí má navíc malý odpor, takže by jím tekl velký proud a vinutí by se mohlo poškodit.</p>
</details>

---

**Co znamená převod transformátoru?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Převod p udává poměr závitů primáru a sekundáru, p = N₁ / N₂. U ideálního transformátoru je stejný jako poměr napětí a opačný poměr proudů: p = U₁ / U₂ = I₂ / I₁.</p>
</details>

---

**Jak se změní napětí a proud, když dvojnásobíme počet závitů na sekundáru?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Převod se zmenší na polovinu. Napětí na sekundáru U₂ se při stejném U₁ zdvojnásobí, protože je úměrné počtu závitů. Výkon se u ideálního transformátoru nemění, takže proud I₂ klesne na polovinu.</p>
</details>

---

**Proč má snižující transformátor na sekundární straně větší proud než na primární?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Výkon se (u ideálního transformátoru) nemění, platí U₁ · I₁ = U₂ · I₂. Pokud se napětí sníží, musí se proud o stejný poměr zvýšit.</p>
</details>

---

**Transformátor má N₁ = 500 závitů a N₂ = 50 závitů. Primární vinutí je připojeno na U₁ = 230 V. Urči převod p a sekundární napětí U₂.**

<details>
<summary>Zobrazit odpověď</summary>
<p>p = N₁ / N₂ = 500 / 50 = <b>10</b><br>
U₂ = U₁ / p = 230 / 10 = <b>23 V</b><br>
Jde o snižující transformátor.</p>
</details>

---

**Zvyšující transformátor má N₁ = 200 závitů a N₂ = 1000 závitů. Na primár přivedeme U₁ = 24 V. Urči převod a napětí U₂.**

<details>
<summary>Zobrazit odpověď</summary>
<p>p = 200 / 1000 = <b>0,2</b><br>
U₂ = U₁ / p = 24 / 0,2 = <b>120 V</b></p>
</details>

---

**Ideální transformátor má převod p = 5 a sekundárním vinutím protéká proud I₂ = 2 A. Jaký proud teče primárním vinutím?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Ze vztahu p = I₂ / I₁ plyne I₁ = I₂ / p = 2 / 5 = <b>0,4 A</b>.</p>
</details>

---

**Ideální transformátor 230 V / 23 V odebírá z primáru proud 0,5 A. Jaký výkon přenáší a jaký proud poteče spotřebičem na sekundáru?**

<details>
<summary>Zobrazit odpověď</summary>
<p>Výkon: S = U₁ · I₁ = 230 · 0,5 = <b>115 VA</b><br>
Proud na sekundáru: I₂ = S / U₂ = 115 / 23 = <b>5 A</b></p>
</details>

### [Zpět na obsah](../README.md)
