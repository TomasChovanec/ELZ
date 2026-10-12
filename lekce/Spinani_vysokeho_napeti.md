# Spínací přístroje pro VN, VVN a ZVN

## Rozdělení napěťových hladin

| Označení | Jmenovité napětí | Typické hladiny v ČR |
|---|---|---|
| VN (vysoké napětí) | 1 kV až 52 kV | 6, 10, 22, 35 kV |
| VVN (velmi vysoké napětí) | 52 kV až 300 kV | 110 kV, 220 kV |
| ZVN (zvlášť vysoké napětí) | nad 300 kV | 400 kV |

Sítě VN slouží k distribuci, VVN k regionálnímu rozvodu a ZVN k přenosu na velké vzdálenosti (přenosová soustava).

## Vysokonapěťové pojistky

<img width="379" alt="image" src="https://github.com/user-attachments/assets/99c3ec83-9a2b-49ec-bc5b-47842e7e8c60" />

<img width="261" alt="image" src="https://github.com/user-attachments/assets/9ecf0f63-4f94-473d-b439-ac0d194a6d01" />

Vysokonapěťové pojistky chrání elektrická zařízení před nadproudy, zejména před zkratovými proudy. Používají se například při ochraně distribučních transformátorů a dalších zařízení VN. Vyrábějí se pro různá jmenovitá napětí, běžně až do 40 kV, a v širokém rozsahu jmenovitých proudů.

Základními částmi pojistkové vložky jsou keramické pouzdro, tavný vodič, keramický nosič a zhášecí náplň, obvykle z křemenného písku. Na koncích vložky jsou kontaktní víčka. Některé vložky jsou vybaveny také ukazatelem stavu nebo pružinovým úderníkem.

<img width="605" alt="image" src="https://github.com/user-attachments/assets/9e244def-ccc8-42bf-8110-441b8062b028" />

*Zdroj obrázku: https://projekty.osu.cz/irp2016/pojistky.html*

Při nadproudu se tavný vodič zahřívá a přetaví. Vzniklý elektrický oblouk je zhášecí náplní uhašen a proud se přeruší. Pojistka tak omezuje účinky zkratového proudu.

Úderník může po přetavení pojistky mechanicky aktivovat další přístroj. V pojistkové kombinaci s odpínačem tak může zajistit odpojení všech tří fází, i když se přetavila pouze jedna pojistková vložka.


## Odpojovače
Jsou to bezpečnostní prvky, které rozpojují obvod bez zatížení(bez proudu). Musí být schopny přenášet (nikoli vypínat) zkratové proudy v obvodu. Zpravidla nemají prvky pro zhášení oblouku

<img width="400" alt="image" src="https://github.com/user-attachments/assets/a389c8e1-8051-4bff-804b-eb73c75d299c" />
<img width="400"  alt="image" src="https://github.com/user-attachments/assets/2fcf5313-e07f-4a10-b0de-4b67d689d391" />

*Zdroj obrázku: https://dribo.cz/*

## Odpínače
Mají nouzové zhášecí zařízení, jsou schopny vypnout jmenovité (nikoli zkratové) proudy v obvodu, musí přenášet zkratové proudy.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/9890409c-295d-4ebe-899e-b8de43d35acb" />

*Zdroj obrázku: https://dribo.cz/*

## Výkonové vypínače 
Musí být schopny zajistit vypnutí všech proudů v obvodu, i zkratů. Jsou proto vybaveny výkonným zhášecím zařízením, které zabezpečí uhašení elektrického oblouku.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/27e6e80a-ccb7-4232-9143-c5971a1e128d" />

*Zdroj obrázku: https://dribo.cz/*


## Zhášení oblouku ve VN, VVN a ZVN
U vypínačů pro vysoká napětí si už nevystačíme s jednoduchými způsoby zhášení oblouků jeko například u instalačních jističů. Pro zvýšení zhášecího účinku se používají různá média (olej, vzduch, elektronegativní plyn), která jsou vháněna do prostoru hoření oblouku a hasí jej. Též mohou být použity elektromagnetické zhášecí cívky společně se zhášecími komorami,ve kterých dojde ke chlazení a přerušení oblouku.


### Máloolejové vypínače

Olej se při působení elektrického oblouku prudce zahřívá a rozkládá, čímž vzniká plynné prostředí, které pomáhá oblouk zhasnout. Od jejich použití se ustoupilo ve prospěch SF6 a vakuových vypínačů.

<img width="800"  alt="image" src="https://github.com/user-attachments/assets/4b2d4bf6-555b-4a8e-bd72-a5287b722519" />

---

### Stlačený vzduch

Vypínače vypínají tlakem vzduchu cca 30 MPa. Jsou velmi rychlé a výkonné, avšak hlučné a energeticky náročné, vyžadují vlastní kompresorovou stanici. V současné době už se nepoužívají.

### Fluorid sírový (SF₆)
Elektronegativní plyn s vysokou dielektrickou pevností a schopností rychle zachytávat volné elektrony, čímž urychluje deionizaci a zhášení oblouku. Má přibližně 3× lepší elektrickou pevnost než vzduch. SF₆ je skleníkový plyn, proto se od jeho použití postupně upouští, od roku 2032 už jej nebude možné používat v **nových** zařízeních (již fungující zařízení se měnit nemusí).

<img width="563" alt="image" src="https://github.com/user-attachments/assets/434215f0-7949-4d4f-87f4-19f462bd7072" />

<img width="625"  alt="image" src="https://github.com/user-attachments/assets/791ba34c-7b40-4354-8a51-09fe70f3c8fe" />

*Zdroj obrázku: https://savree.com/en/encyclopedia/sf6-circuit-breaker*

---
### Vakuum (p ≈ 10⁻¹⁰ Pa)

Vakuová zhášedla se dnes stále více používají pro své velké výhody: jsou nehořlavá, při funkci tichá, nevyfukují ionizované plyny nebo plameny, mají minimální opotřebení a malý potřebný zdvih.

Při tlaku nižším než 10⁻³ Pa je střední volná dráha elektronů ve zbytkovém plynu značně delší než vzdálenost kontaktů a proto po přiložení napětí ke kontaktům nemůže dojít k nárazové ionizaci volnými elektrony a samovolný elektrický výboj nenastane. Elektrická pevnost mezikontaktního prostoru ve vakuu je mnohokrát větší než pevnost tohoto prostoru při atmosférickém tlaku.

Při vypínacím pochodu nejprve zaniká kontaktní síla, tím se zmenšuje počet stykových bodů a proud se přesouvá do posledního místa dotyku kontaktů. Toto místo se Jouleovým teplem značně zahřívá, až dojde k vypaření části kontaktního kovu. Mezi kontakty se tak tedy objeví mrak kovových par a dochází k jejich ionizaci a k přenosu proudu vzniklým plazmatem.

Největším problémem vakuového vypínání spočívá v konstrukci mechanicky pevné a přitom vakuově těsné nádoby a ve volbě a technologickém zpracování kontaktních materiálů. Jak je patrné z obrázku jsou vakuová zhášedla celkem jednoduchá. Jedná se vždy o dva masivní kontakty umístěné čelně proti sobě ve vakuové nádobě. Nádoba je ze skla nebo vakuové keramiky s kovovými víky. Jeden z kontaktů je pevně připojen k víku a druhý má možnost osového pohybu několika milimetrů při zachování dokonalé těsnosti pružného členu - vlnovce. Vlnovec se většinou vyrábí z titanové oceli a určuje mechanickou životnost zhášedla (ta je asi 10⁶ cyklů). Aby nedocházelo k napařování kovových par na vnitřní straně vakuové nádoby, je kolem kontaktů kovové stínění. Po oddálení kontaktů tedy dojde za pomoci kovových par k zapálení oblouku. Při průchodu proudu nulou dojde ke zhasnutí oblouku a k jeho dalšímu zapálení už nedojde.

<img width="800"  alt="image" src="https://github.com/user-attachments/assets/c1fa33a4-8393-43ef-978c-d2920ed736c3" />


Reálné provedení vakuového vypínače

<img width="500" alt="image" src="https://github.com/user-attachments/assets/52068d73-826b-4e65-8b78-1a55b567d752" />

Kovový vlnovec umožňující pohyb kontaktu při zachování vakua

<img width="600" alt="image" src="https://github.com/user-attachments/assets/261ed760-12b6-4484-b884-f0d1313aa4d6" />

*Zdroj obrázku: https://dribo.cz/vyrobni-program/vypinace-osm-magvatech/#gallery-7*

# Videa

**Vše, co jste chtěli vědět o distribuční soustavě - O distribuci elektřiny**

[![](https://img.youtube.com/vi/A1oLSBq3BAE/0.jpg)](https://www.youtube.com/watch?v=A1oLSBq3BAE)

**Electrical Substation, 3D Virtual reality, Operation processes**

[![](https://img.youtube.com/vi/B0LsVtur4WE/0.jpg)](https://www.youtube.com/watch?v=B0LsVtur4WE)

**From 440kV to 440V: How Substations Deliver Electricity to Our Homes**

[![](https://img.youtube.com/vi/8xZVsckRgYw/0.jpg)](https://www.youtube.com/watch?v=8xZVsckRgYw)

**Inside the Relay Controlled SF6 Circuit Breaker**

[![](https://img.youtube.com/vi/oWJk5avZ4jI/0.jpg)](https://www.youtube.com/watch?v=oWJk5avZ4jI)

# Otázky k opakování
---
**Jaké napěťové hladiny označujeme jako VN, VVN a ZVN a jaké jsou jejich typické hodnoty v ČR?**
<details>
<summary>Odpověď</summary>
VN je 1–52 kV, typicky 6, 10, 22 a 35 kV. VVN je 52–300 kV, typicky 110 a 220 kV. ZVN je nad 300 kV, v ČR především 400 kV.
</details>

---
**K čemu slouží sítě VN, VVN a ZVN?**
<details>
<summary>Odpověď</summary>
VN slouží především k distribuci elektrické energie, VVN k regionálnímu rozvodu a ZVN k přenosu elektrické energie na velké vzdálenosti v přenosové soustavě.
</details>

---
**Jaký je hlavní rozdíl mezi odpojovačem, odpínačem a výkonovým vypínačem?**
<details>
<summary>Odpověď</summary>
Odpojovač je určen k rozpojení obvodu bez proudu. Odpínač umožňuje vypínat jmenovité proudy, ale ne zkratové proudy. Výkonový vypínač musí být schopen vypnout i zkratové proudy.
</details>

---
**Proč se odpojovač nesmí běžně ovládat při zatíženém obvodu?**
<details>
<summary>Odpověď</summary>
Odpojovač zpravidla nemá účinné zhášecí zařízení. Při rozpojení obvodu pod zatížením by proto mohl vzniknout nebezpečný elektrický oblouk, který by se nepodařilo bezpečně uhasit.
</details>

---
**Co musí odpojovač zvládnout v případě zkratu?**
<details>
<summary>Odpověď</summary>
Odpojovač musí být schopen přenášet zkratový proud, ale není určen k jeho vypínání.
</details>

---
**K čemu slouží odpojovač v elektrické stanici?**
<details>
<summary>Odpověď</summary>
Slouží především k bezpečnému galvanickému oddělení části elektrického zařízení od zbytku sítě, například před údržbou. Jeho rozpojená poloha umožňuje jednoznačně ověřit oddělení zařízení.
</details>

---
**Jaký proud může vypínat odpínač?**
<details>
<summary>Odpověď</summary>
Odpínač je schopen vypínat svůj jmenovitý proud, případně proudy stanovené výrobcem, ale není určen k vypínání zkratových proudů.
</details>

---
**Proč má odpínač zhášecí zařízení, i když není určen k vypínání zkratů?**
<details>
<summary>Odpověď</summary>
Při vypínání jmenovitého proudu vzniká mezi kontakty elektrický oblouk. Zhášecí zařízení jej musí bezpečně uhasit. Odpínač proto může vypínat provozní proudy, ale jeho zhášecí zařízení není určeno pro vypnutí velkého zkratového proudu.
</details>

---
**Co musí být schopen vypnout výkonový vypínač?**
<details>
<summary>Odpověď</summary>
Výkonový vypínač musí být schopen bezpečně vypnout všechny proudy, pro které je určen, včetně vysokých zkratových proudů.
</details>
---
**Jak funguje zhášení oblouku pomocí SF6 ve VN technice?**
<details>
<summary>Odpověď</summary>
SF6 (fluorid sírový) je elektronegativní plyn s vysokou dielektrickou pevností, který rychle zachytává volné elektrony, čímž urychluje deionizaci prostoru mezi kontakty a zhášení oblouku.
</details>

---
**Proč vakuová komora umožňuje velmi rychlé zhášení oblouku?**
<details>
<summary>Odpověď</summary>
Ve vysokém vakuu chybí médium schopné oblouk udržet. Oblouk, tvořený parami kovu z kontaktů, proto zhasíná velmi rychle při průchodu proudu nulou.
</details>

---

**Proč je výkonový vypínač vybaven výkonným zhášecím zařízením?**
<details>
<summary>Odpověď</summary>
Při vypínání velkého proudu vzniká mezi kontakty velmi intenzivní elektrický oblouk. Výkonné zhášecí zařízení zajistí jeho bezpečné uhašení a dostatečně rychlé obnovení elektrické pevnosti mezi kontakty.
</details>

---
**Proč má vakuum vysokou elektrickou pevnost?**
<details>
<summary>Odpověď</summary>
Při velmi nízkém tlaku je mezi kontakty jen velmi málo částic. Střední volná dráha elektronů je proto mnohem delší než vzdálenost kontaktů a nemůže docházet k běžné nárazové ionizaci plynu. Elektrický výboj se proto po oddálení kontaktů obtížně udržuje.
</details>

---
**Co způsobuje vznik oblouku ve vakuovém zhášedle?**
<details>
<summary>Odpověď</summary>
Po oddálení kontaktů se z jejich povrchu uvolní kovové páry. Ty se ionizují a vytvoří plazma, které umožní další průchod proudu mezi kontakty.
</details>

---
**Proč vakuový oblouk zhasne při průchodu střídavého proudu nulou?**
<details>
<summary>Odpověď</summary>
Při průchodu proudu nulou zanikne plazma tvořená kovovými parami. Ve vakuu se následně velmi rychle obnoví vysoká elektrická pevnost mezikontaktního prostoru, takže se oblouk znovu nezapálí.
</details>

---
**Jak je ve vakuovém zhášedle umožněn pohyb jednoho z kontaktů při zachování vakua?**
<details>
<summary>Odpověď</summary>
Pohyblivý kontakt je spojen s vnějším mechanismem pomocí kovového vlnovce. Ten umožňuje axiální pohyb kontaktu a současně zachovává vakuovou těsnost zhášedla.
</details>

---
**K čemu slouží kovový vlnovec ve vakuovém zhášedle?**
<details>
<summary>Odpověď</summary>
Umožňuje pohyb pohyblivého kontaktu při zachování dokonalé těsnosti vakuové nádoby.
</details>

---
**K čemu slouží kovové stínění kolem kontaktů vakuového zhášedla?**
<details>
<summary>Odpověď</summary>
Chrání vnitřní povrch vakuové nádoby před napařováním kontaktního materiálu, který se při vzniku oblouku odpařuje z kontaktů.
</details>


### [Zpět na obsah](../README.md)
