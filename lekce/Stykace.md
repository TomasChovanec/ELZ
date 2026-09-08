# Stykače

<img width="800"  alt="image" src="https://github.com/user-attachments/assets/5c344942-4d0e-4ac1-be05-71383c91118a" />

*Zdroj obrázku: https://www.petanovo.cz/jak-zapojit-stykac/*

Stykač je elektromagnetický spínací přístroj určený k častému spínání a vypínání elektrických obvodů pod zatížením, ovládaný na dálku (elektricky, nejčastěji cívkou). Na rozdíl od jističe není určen k jištění proti zkratu nebo přetížení, ale k provoznímu spínání – typicky motorů, topných těles, osvětlení nebo jiných spotřebičů.

## Použití

Stykače se používají zejména:
- k dálkovému a automatizovanému ovládání motorů (přímé spouštění, hvězda-trojúhelník)
- v rozvaděčích pro spínání topných okruhů, osvětlení, kompenzace jalového výkonu
- v kombinaci s tepelným relé jako tzv. motorový spouštěč, který zajišťuje i ochranu proti přetížení

<img width="600" alt="image" src="https://github.com/user-attachments/assets/75e689a2-367e-4dd4-bebd-56de6858cffa" />

## Konstrukce a princip činnosti

<img width="800" alt="image" src="https://github.com/user-attachments/assets/30d62d1b-5a15-42f2-8c9e-8f60ffe7e091" />

*Zdroj obrázku: https://www.electrical4u.net/siemens-contactor-disassembly/*

Stykač se skládá ze tří základních částí:

**Elektromagnetický pohon (cívka)** – po přivedení napětí na cívku vznikne magnetické pole, které přitáhne kotvu a sepne kontakty.

**Hlavní kontakty –** slouží k sepnutí/rozepnutí hlavního (silového) obvodu, jsou dimenzované na jmenovitý proud zátěže.

**Pomocné kontakty –** slouží k ovládání a signalizaci (např. blokování, indikace stavu, propojení do řídicího obvodu).

Po odpojení napětí od cívky (vypnutí, výpadek napájení) se kontakty vlivem pružiny vrátí do klidové polohy – stykač je tedy v klidovém stavu rozepnutý (bezpečnostní vlastnost).

## Důležité parametry stykače

Při výběru stykače nestačí sledovat pouze jeho jmenovitý proud. Stykač musí být vhodný pro druh proudu, napětí, charakter zátěže, velikost proudu a způsob ovládání.

### Jmenovitý proud 
Jmenovitý pracovní proud je největší proud, který může stykač spínat za stanovených podmínek, aniž by došlo k jeho nepřípustnému zahřívání nebo poškození.

### Jmenovité napětí 
Jmenovité pracovní napětí je napětí, pro které je stykač určen při spínání dané zátěže. Stykač musí být pro použité napětí vhodný z hlediska izolace i vypínání elektrického oblouku.

### Druh proudu – AC / DC
U stykače je nutné rozlišovat, zda jsou jeho kontakty určeny pro:

AC – střídavý proud,
DC – stejnosměrný proud.

Stejnosměrný proud je z hlediska zhášení elektrického oblouku náročnější než střídavý proud. Proto je důležité použít stykač určený přímo pro daný druh proudu a napětí.

### Napájecí napětí cívky
Napájecí napětí cívky je napětí, které musí být přivedeno na ovládací cívku stykače, aby se stykač sepnul.
- 24 V DC 
- 24 V AC
- 230 V AC

Napětí cívky nesouvisí přímo s napětím spínaným kontakty. Například stykač může mít cívku 24 V AC, ale jeho hlavní kontakty mohou spínat 400 V AC.

### Počet hlavních a pomocných kontaktů
Hlavní kontakty slouží ke spínání vlastní zátěže, například motoru. Běžný třífázový stykač má 3 hlavní kontakty (L1–T1, L2–T2, L3–T3).
Pomocné kontakty slouží k ovládání a signalizaci – například k vytvoření samodržného obvodu, blokování jiného stykače nebo signalizaci sepnutí. Mohou být:

### Rozdělení podle zátěže
Podle normy ČSN EN 60947-4-1 se stykače dělí do kategorií užití podle charakteru spínané zátěže, např.:

<table>
<tr>
  <th>Druh proudu</th>
  <th>Kategorie užití</th>
  <th>Popis</th>
</tr>
<tr>
  <td rowspan="3">Střídavý proud</td>
  <td><b>AC-1</b></td>
  <td>Neinduktivní nebo mírně induktivní zátěže, odporové pece</td>
</tr>
<tr>
  <td><b>AC-3</b></td>
  <td>Motory s kotvou nakrátko, spouštění, vypínání motorů v chodu</td>
</tr>
<tr>
  <td><b>AC-4</b></td>
  <td>Motory s kotvou nakrátko, spouštění, reverzace, krátkodobý chod</td>
</tr>
<tr>
  <td rowspan="3">Stejnosměrný proud</td>
  <td><b>DC-1</b></td>
  <td>Neinduktivní nebo mírně induktivní zátěže, odporové pece</td>
</tr>
<tr>
  <td><b>DC-2</b></td>
  <td>Derivační motory, spouštění, reverzace, krátkodobý chod, dynamické brzdění motorů</td>
</tr>
<tr>
  <td><b>DC-3</b></td>
  <td>Sériové motory, spouštění, reverzace, krátkodobý chod, dynamické brzdění motorů</td>
</tr>
</table>

Vyšší kategorie znamenají náročnější spínací podmínky – tedy vyšší zapínací/vypínací proudy a intenzivnější namáhání kontaktů obloukem.


## Co musí technik při výběru stykače znát?
- co bude stykač spínat – motor, topení, osvětlení…,
- četnost spínání
- druh proudu – AC nebo DC,
- napětí hlavního obvodu,
- proud zátěže,
- napětí a druh proudu cívky,
- počet hlavních a pomocných kontaktů,


## Zhášení oblouku u stykačů
Protože stykač často spíná induktivní zátěže (motory), vzniká při rozpojování kontaktů elektrický oblouk. Ten je řešen podobně jako u jiných spínacích přístrojů – zhášecími komorami s dělicími můstky nebo hřebeny, případně magnetickým vyfukováním. Vyšší kategorie užití (AC-3, AC-4) proto vyžadují robustnější zhášecí systém a odolnější kontaktní materiály.


## Schématické značení stykačů
<img width="800" alt="image" src="https://github.com/user-attachments/assets/4542d6ce-95ea-40ab-890d-6f4a4fa9a5d2" />

*Zdroj obrázku: https://www.petanovo.cz/jak-zapojit-stykac/*

  
<img width="400" height="291" alt="image" src="https://github.com/user-attachments/assets/9e4ad4f6-0771-458e-bdce-4e183ba42ce5" />

<img width="222" height="400" alt="image" src="https://github.com/user-attachments/assets/582f10aa-f342-4d86-940f-534c7257912c" />

<img width="406" height="294" alt="image" src="https://github.com/user-attachments/assets/30de5afc-57e0-42ae-b4c1-21cccc3ed497" />



## Pomocné kontakty a jejich využití
<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/72e1390f-8839-431f-add2-7e9cb3e9efea" />

<img width="500" height="281" alt="image" src="https://github.com/user-attachments/assets/a9e8ca73-7d90-444c-84d4-d5307e91b3ac" />

- **NO** (spínací - **N**ormally **O**pen) – při sepnutí stykače kontakt sepne,
- **NC** (rozpínací - **N**ormally **C**losed) – při sepnutí stykače kontakt rozepne.

### Ssamodržné zapojení stykače
Zapojení se samodržením – tlačítko Start je přemostěno pomocným kontaktem stykače, takže po jeho sepnutí zůstává cívka pod napětím i po uvolnění tlačítka.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/933234aa-35db-455b-b2be-baebc2b6706b" />

### Reverzace otáček motoru s blokováním
<img width="795" height="292" alt="image" src="https://github.com/user-attachments/assets/63eb9517-e309-4da5-91d2-d564ba82accf" />
  
<img width="786" height="729" alt="image" src="https://github.com/user-attachments/assets/578a65e0-b193-49fe-a041-2cce7f315ed0" />
 
<img width="800" height="764" alt="image" src="https://github.com/user-attachments/assets/77bb1caa-898e-42d6-8101-52c2329fca45" />


## Další zajímavé materiály
[![](https://img.youtube.com/vi/FCsgUXPRew8/0.jpg)](https://www.youtube.com/watch?v=FCsgUXPRew8)

[![](https://img.youtube.com/vi/eKI1LF5q3JE/0.jpg)](https://www.youtube.com/watch?v=eKI1LF5q3JE)


# Otázky k opakování

**Co je stykač a k čemu se používá?**

<details>
<summary>Odpověď</summary>
Stykač je elektromechanický spínací přístroj určený především k **častému spínání výkonových elektrických obvodů**. Typicky se používá ke spínání elektromotorů, topných zařízení nebo osvětlení. Výkonový obvod je ovládán elektrickým signálem přivedeným na cívku stykače.
</details>

---

**Jak funguje elektromagnetický mechanismus stykače?**

<details>
<summary>Odpověď</summary>
Po přivedení napětí na cívku stykače začne cívkou procházet proud a vznikne magnetické pole. To přitáhne pohyblivou kotvu elektromagnetu a mechanicky přestaví kontakty. Po odpojení napětí magnetické pole zanikne a pružina vrátí kotvu a kontakty do výchozí polohy.
</details>

---

**Jaké jsou hlavní části stykače?**

<details>
<summary>Odpověď</summary>
Mezi základní části patří:
- **cívka** – vytváří magnetické pole,
- **elektromagnet a kotva** – zajišťují mechanický pohyb,
- **hlavní kontakty** – spínají výkonový obvod,
- **pomocné kontakty** – slouží k řízení, blokování a signalizaci,
- **zhášecí komory** – omezují a zhášejí elektrický oblouk při rozepnutí kontaktů,
- **pružina** – vrací mechanismus do výchozí polohy.
</details>

---

**Jaký je rozdíl mezi hlavními a pomocnými kontakty stykače?**

<details>
<summary>Odpověď</summary>
**Hlavní kontakty** jsou určeny k přenosu většího proudu a spínají výkonový obvod, například elektromotor. **Pomocné kontakty** jsou určeny především pro řídicí, signalizační a blokovací obvody a obvykle spínají výrazně menší proud.
</details>

---

**Co znamená označení NO a NC u kontaktů stykače?**

<details>
<summary>Odpověď</summary>
- **NO (Normally Open)** – spínací kontakt, který je při vypnutém stykači rozepnutý a po sepnutí stykače se uzavře.
- **NC (Normally Closed)** – rozpínací kontakt, který je při vypnutém stykači sepnutý a po sepnutí stykače se rozepne.
</details>

---

**Jaké je typické označení hlavních a pomocných kontaktů stykače?**

<details>
<summary>Odpověď</summary>
Hlavní kontakty třípólového stykače se typicky označují **1–2, 3–4, 5–6**. Pomocný spínací kontakt bývá označen **13–14** a pomocný rozpínací kontakt **21–22**. Cívka se označuje **A1 a A2**.
</details>

---

**Proč se pro ovládání výkonového obvodu používá stykač místo běžného vypínače?**

<details>
<summary>Odpověď</summary>
Stykač umožňuje ovládat **velký elektrický výkon pomocí malého ovládacího obvodu**. Umožňuje také časté a dálkové spínání, automatické ovládání a snadné propojení s tlačítky, senzory, PLC nebo jinými řídicími prvky.
</details>

---

**Jak funguje samodržné zapojení stykače?**

<details>
<summary>Odpověď</summary>
Po stisknutí tlačítka **START** se sepne cívka stykače. Současně se sepne jeho pomocný kontakt NO, který je zapojen paralelně k tlačítku START. Po uvolnění tlačítka proto proud stále prochází pomocným kontaktem a stykač zůstane sepnutý. Stisknutím tlačítka **STOP**, které je v sérii s cívkou, se obvod přeruší a stykač odpadne.
</details>

---

**Proč je ve stykači zhášecí komora?**

<details>
<summary>Odpověď</summary>
Při rozepnutí kontaktů vzniká elektrický oblouk. Zhášecí komora oblouk **prodlužuje, rozděluje, ochlazuje a deionizuje**, čímž usnadňuje jeho zhasnutí. Zároveň omezuje opalování a poškozování kontaktů.
</details>

---

**Proč jsou kontakty stykače při spínání elektromotoru namáhány více než při spínání odporové zátěže?**

<details>
<summary>Odpověď</summary>
Elektromotor je **induktivní zátěž**. Při vypínání se indukčnost snaží zachovat protékající proud a může vytvořit vysoké přepětí. To podporuje vznik a udržování elektrického oblouku mezi rozpojujícími se kontakty a způsobuje jejich větší opotřebení.
</details>

---

**Jaký je rozdíl mezi stykačem a relé?**

<details>
<summary>Odpověď</summary>
Oba přístroje pracují na principu elektromagnetického ovládání kontaktů. **Stykač** je konstrukčně určen především pro spínání výkonových obvodů, zejména motorů, a je konstruován pro větší proudy a časté spínání. **Relé** se častěji používá v řídicích, signalizačních a elektronických obvodech s menšími proudy.
</details>

---

**Jaký je rozdíl mezi stykačem s AC a DC cívkou?**

<details>
<summary>Odpověď</summary>
Cívka stykače musí být napájena **správným druhem a jmenovitým napětím**. AC a DC cívky mají odlišnou konstrukci a způsob omezení proudu. Stykač s cívkou 24 V DC proto nelze jednoduše připojit na 24 V AC a naopak.
</details>

---

**Co se stane se stykačem při výpadku napětí na jeho cívce?**

<details>
<summary>Odpověď</summary>
Magnetické pole cívky zanikne, kotva se pomocí pružiny vrátí do výchozí polohy a **hlavní i pomocné kontakty se vrátí do klidového stavu**. Výkonový obvod se tak obvykle automaticky odpojí.
</details>

---

**Proč se stykač používá například pro přímé spouštění třífázového motoru?**

<details>
<summary>Odpověď</summary>
Stykač umožňuje současně spínat všechny tři fáze motoru pomocí jediného elektromagnetického mechanismu. Cívka stykače může být ovládána tlačítky nebo automatizačním systémem, zatímco hlavní kontakty vedou proud motoru.
</details>

---

**Proč musí být stykač správně dimenzován pro spínanou zátěž?**

<details>
<summary>Odpověď</summary>
Při spínání a vypínání vzniká elektrický oblouk a kontakty jsou tepelně i elektricky namáhány. Stykač proto musí být vhodný pro **napětí, proud, druh zátěže a četnost spínání**. Například stykač určený pro odporovou zátěž nemusí být vhodný pro stejně velký výkon elektromotoru.
</details>


### [Zpět na obsah](../README.md)
