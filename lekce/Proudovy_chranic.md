# Proudový chránič

## Co to je
Proudový chránič (RCD – Residual Current Device, lidově „chránič“) je elektrický přístroj, který v okamžiku, kdy zjistí únik proudu mimo běžný obvod, rychle odpojí napájení. Chrání především **osoby před úrazem elektrickým proudem** a také objekty před požárem způsobeným zemními svody.

## Princip činnosti
Uvnitř chrániče je **součtový (sumační) transformátor**, kterým procházejí všechny pracovní vodiče (fáze a nulový vodič).

- **Za normálního stavu** proud, který teče do spotřebiče fázovým vodičem, se vrací nulovým vodičem. Součet proudů je nulový, magnetické toky se ruší a v transformátoru se nic neindukuje.
- **Při poruše** (např. dotyk osoby s živou částí nebo poškozená izolace) část proudu odteče jinou cestou, typicky přes zem nebo tělo člověka. Vzniká rozdíl proudů, tzv. **rozdílový (reziduální) proud**. Ten vyvolá magnetický tok, indukuje se napětí a spustí se vybavovací cívka, která přístroj vypne.

Vybavení je velmi rychlé, obvykle do 30 ms.

## Základní parametry
| Parametr | Význam |
|---|---|
| **Jmenovitý vybavovací rozdílový proud IΔn** | Proud, při kterém chránič vypíná. Nejčastěji 30 mA, 100 mA, 300 mA |
| **Jmenovitý proud In** | Největší trvalý proud, který smí chráničem procházet (např. 25 A, 40 A, 63 A) |
| **Počet pólů** | 2pólové (1fázové obvody), 4pólové (3fázové obvody) |
| **Typ (charakteristika)** | Určuje, na jaký druh rozdílového proudu chránič reaguje |

## Typy chráničů
- **Typ AC** – reaguje na střídavý sinusový rozdílový proud. Dnes už se pro nové instalace nedoporučuje.
- **Typ A** – reaguje i na pulzující stejnosměrný proud. Standard pro domácnosti (pračky, elektronika).
- **Typ F** – rozšířený typ A, vhodný např. pro spotřebiče s frekvenčními měniči.
- **Typ B** – reaguje i na hladký stejnosměrný proud (fotovoltaika, nabíjení elektromobilů, průmyslové pohony).

## Kde se používá
Ve **30mA provedení** je chránič povinný jako **doplňková ochrana** například v:
- zásuvkových obvodech do 32 A,
- koupelnách a dalších prostorách s vyšším rizikem,
- obvodech osvětlení v bytových prostorách,
- venkovních instalacích.

Chrániče s vyšším vybavovacím proudem (100–300 mA) se používají spíše pro **požární ochranu** nebo jako nadřazená ochrana.

## Co chránič nedělá
- **Nechrání před přetížením a zkratem** – k tomu slouží jistič. Proto se chránič kombinuje s jističem (nebo se používá kombinovaný přístroj **proudový chránič s nadproudovou ochranou, RCBO**).
- **Nechrání před dotykem dvou živých vodičů zároveň** (např. fáze a nulový vodič), protože tehdy proud protéká celým obvodem a rozdíl nevzniká.

## Kontrola funkce
Chránič má **testovací tlačítko (T)**. Po jeho stisknutí se uměle vytvoří rozdílový proud a chránič musí vypnout. Doporučuje se test provádět **jednou za 3 měsíce**. Pokud chránič nevypne, je nutné ho nechat vyměnit a zkontrolovat.

## Shrnutí
Proudový chránič sleduje rovnováhu proudů ve vodičích, a když zjistí únik, během zlomku sekundu obvod odpojí. Je nejdůležitější doplňkovou ochranou před úrazem elektrickým proudem, ale nenahrazuje jistič.

---

# Otázky k opakování

**Co je proudový chránič a k čemu se používá?**

<details markdown="1">
<summary>Odpověď</summary>
Proudový chránič (RCD) je elektrický přístroj, který při zjištění **úniku proudu mimo běžný obvod** rychle odpojí napájení. Chrání především **osoby před úrazem elektrickým proudem** a také objekty před požárem způsobeným zemními svody.
</details>

---

**Jak proudový chránič pozná poruchu?**

<details markdown="1">
<summary>Odpověď</summary>
Chránič porovnává proudy ve všech pracovních vodičích pomocí **součtového transformátoru**. Pokud je součet proudů nulový, je vše v pořádku. Pokud se součet liší, část proudu odtéká mimo obvod a chránič **vypne**.
</details>

---

**K čemu slouží součtový transformátor v chrániči?**

<details markdown="1">
<summary>Odpověď</summary>
Součtovým transformátorem procházejí **všechny pracovní vodiče** (fáze a nulový vodič). Vyhodnocuje rozdíl proudů, které do spotřebiče vstupují a které se z něj vracejí. Při poruše se v něm indukuje napětí, které spustí vybavovací cívku.
</details>

---

**Proč se za normálního stavu v součtovém transformátoru nic neindukuje?**

<details markdown="1">
<summary>Odpověď</summary>
Proud, který teče do spotřebiče fázovým vodičem, se vrací nulovým vodičem. Součet proudů je tedy **nulový** a magnetické toky obou vodičů se navzájem **ruší**.
</details>

---

**Co je rozdílový (reziduální) proud?**

<details markdown="1">
<summary>Odpověď</summary>
Rozdílový proud je **rozdíl mezi proudem, který do obvodu vstupuje, a proudem, který se vrací**. Vzniká, když část proudu odteče jinou cestou, například přes tělo člověka nebo přes poškozenou izolaci do země.
</details>

---

**Do jaké doby chránič obvykle vypne?**

<details markdown="1">
<summary>Odpověď</summary>
Vybavení chrániče je velmi rychlé, obvykle **do 30 ms**.
</details>

---

**Co znamená jmenovitý vybavovací rozdílový proud IΔn a jaké má nejčastější hodnoty?**

<details markdown="1">
<summary>Odpověď</summary>
IΔn je proud, **při kterém chránič vypíná**. Nejčastěji se používají hodnoty **30 mA, 100 mA a 300 mA**.
</details>

---

**Jaký je rozdíl mezi jmenovitým proudem In a jmenovitým vybavovacím proudem IΔn?**

<details markdown="1">
<summary>Odpověď</summary>
**In** je největší trvalý proud, který smí chráničem procházet (např. 25 A, 40 A, 63 A). **IΔn** je velikost rozdílového proudu, při které chránič vypne (např. 30 mA).
</details>

---

**Kolikapólový chránič použijeme pro jednofázový a kolikapólový pro třífázový obvod?**

<details markdown="1">
<summary>Odpověď</summary>

- **2pólový** chránič se používá pro **jednofázové** obvody.
- **4pólový** chránič se používá pro **třífázové** obvody.

</details>

---

**Jaké typy proudových chráničů rozlišujeme a na jaký proud reagují?**

<details markdown="1">
<summary>Odpověď</summary>

- **Typ AC** – reaguje na střídavý sinusový rozdílový proud, pro nové instalace se již nedoporučuje.
- **Typ A** – reaguje i na pulzující stejnosměrný proud.
- **Typ F** – rozšířený typ A, vhodný např. pro spotřebiče s frekvenčními měniči.
- **Typ B** – reaguje i na hladký stejnosměrný proud.

</details>

---

**Který typ chrániče zvolíte pro obvod pračky a proč?**

<details markdown="1">
<summary>Odpověď</summary>
Vhodný je **typ A**. Moderní pračky obsahují elektroniku, která může vytvářet **pulzující stejnosměrné rozdílové proudy**. Typ AC by na ně nemusel spolehlivě reagovat. Typ A je standard pro domácnosti.
</details>

---

**Kdy je vhodné použít chránič typu B?**

<details markdown="1">
<summary>Odpověď</summary>
Typ B reaguje i na **hladký stejnosměrný rozdílový proud**. Používá se například u **fotovoltaiky**, **nabíjení elektromobilů** a **průmyslových pohonů**.
</details>

---

**Kde je povinný chránič s vybavovacím proudem 30 mA?**

<details markdown="1">
<summary>Odpověď</summary>
Jako **doplňková ochrana** je povinný například:

- v zásuvkových obvodech do 32 A,
- v koupelnách a dalších prostorách s vyšším rizikem,
- v obvodech osvětlení v bytových prostorách,
- ve venkovních instalacích.

</details>

---

**K čemu se používají chrániče s vybavovacím proudem 100–300 mA?**

<details markdown="1">
<summary>Odpověď</summary>
Používají se spíše pro **požární ochranu** nebo jako **nadřazená ochrana**.
</details>

---

**Jaký je rozdíl mezi proudovým chráničem a jističem?**

<details markdown="1">
<summary>Odpověď</summary>

- **Jistič** chrání obvod před **přetížením a zkratem**.
- **Chránič** chrání především **osoby před úrazem elektrickým proudem** tím, že vypne při úniku proudu (rozdílovém proudu).

Chránič **nenahrazuje jistič**, proto se oba přístroje kombinují.

</details>

---

**Co je RCBO?**

<details markdown="1">
<summary>Odpověď</summary>
RCBO je **kombinovaný přístroj**, který spojuje funkci **proudového chrániče a jističe** (proudový chránič s nadproudovou ochranou). Chrání tedy před úrazem elektrickým proudem, přetížením i zkratem.
</details>

---

**Před čím proudový chránič nechrání?**

<details markdown="1">
<summary>Odpověď</summary>

- Nechrání před **přetížením a zkratem**.
- Nechrání před **dotykem dvou živých vodičů zároveň** (např. fáze a nulový vodič). Proud pak protéká celým obvodem a **rozdílový proud nevzniká**.

</details>

---

**Jak se kontroluje funkce proudového chrániče a jak často?**

<details markdown="1">
<summary>Odpověď</summary>
Stiskem **testovacího tlačítka (T)**, kterým se uměle vytvoří rozdílový proud. Chránič musí **vypnout**. Test se doporučuje provádět **jednou za 3 měsíce**.
</details>

---

**Co je nutné udělat, když chránič po stisknutí testovacího tlačítka nevypne?**

<details markdown="1">
<summary>Odpověď</summary>
Chránič je **nefunkční**, proto je nutné ho **nechat vyměnit** a instalaci zkontrolovat kvalifikovanou osobou.
</details>

---

### [Zpět na obsah](../README.md)
