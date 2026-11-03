# Transformátory

Transformátor je elektrický, netočivý stroj. Pomocí elektromagnetické indukce mění elektrickou energii jedněch parametrů na el. energii druhých parametrů - těmito parametry je napětí a proud, frekvence se nemění. Výkon se také nemění, jen se zmenší o ztráty transformátoru.

Používají se nejčastěji pro přeměnu střídavého napětí nebo na galvanické oddělení obvodů.

## Princip činnosti

Transformátor má dvě cívky (vinutí) na společném železném jádru. Primární vinutí s N₁ závity se připojí ke střídavému napětí u₁. Protéká jím magnetizační proud, který v jádru vytvoří střídavý magnetický tok Φ. Tento tok prochází i sekundárním vinutím s N₂ závity a indukuje v něm napětí u₂.

<img width="550" alt="image" src="https://github.com/user-attachments/assets/de6c71e7-bba1-4593-98a1-b12cb36a7810" />

## Elektromagnetická indukce

Elektromagnetická indukce je jev, při kterém ve vodiči dochází ke vzniku indukovaného elektromotorického napětí Ui a v důsledku časové změny magnetického indukčního toku, tj. důsledkem umístění vodiče v měnícím se magnetickém poli.

Jev byl objeven roku 1831 Michaelem Faradayem.

Velikost indukovaného napětí závisí na velikosti **změny** magnetického pole a **rychlosti** této změny.

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
- p = 1: oddělovací transformátor, mění se jen galvanické oddělení obvodů


<iframe
  src="https://tomaschovanec.github.io/ELZ/files/trafo_applet.html"
  width="100%" height="620"
  style="border:0; max-width:900px;"
  loading="lazy"
  title="Simulace ideálního transformátoru">
  </iframe>

