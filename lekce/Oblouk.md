# Elektrický oblouk v elektrických zařízeních

Při rozpojování elektrického obvodu, ktrým protéká proud, vzniká mezi rozpojujícími se kontakty elektrický oblouk. Jde o vodivý ionizovaný kanál plynu s teplotou až několik tisíc °C, kterým prochází proud i po fyzickém oddálení kontaktů. Právě proto musí být spínací a jisticí přístroje (stykače, jističe, pojistky, odpojovače) konstruovány tak, aby oblouk co nejrychleji a bezpečně uhasily.


### Ilustrační video

[![](https://img.youtube.com/vi/qE8W10z76zs/0.jpg)](https://www.youtube.com/shorts/qE8W10z76zs)

[![](https://img.youtube.com/vi/W4oydQ4afJA/0.jpg)](https://www.youtube.com/shorts/W4oydQ4afJA)



## Opalování kontaktů
Vysoká teplota oblouku způsobuje tepelné a elektroerozivní opotřebení kontaktů – dochází k tavení a odpařování materiálu kontaktů (opalování). To zkracuje jejich životnost, zvyšuje přechodový odpor a při opakovaném spínání může vést až ke svaření kontaktů. Proto se kontakty vyrábí ze speciálních slitin (např. AgCdO, AgNi) odolných proti opalu a přístroje se navrhují s dostatečnou spínací rychlostí a zhášecím systémem.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/8d3bfe9c-0e03-41f3-9bb1-d0fa704edc22" />

## Vypínání induktivních zátěží
Zvýšené problémy s obloukem nastávají při vypínání induktivních zátěží, jako jsou motory, transformátory nebo cívky. Indukčnost se brání náhlé změně proudu a při přerušení obvodu generuje vysoké přepětí (podle vztahu u = -L·di/dt), které se snaží proud udržet i přes rozpojující se kontakty. To vede k intenzivnějšímu a hůře zhasitelnému oblouku i k namáhání izolace přepětím. Proto se u spínání motorů a podobných zátěží používají přístroje s vyšší zhášecí schopností a často i doplňková ochranná opatření (např. RC členy, varistory nebo zhášecí diody u stejnosměrných obvodů).

## Rozdíl mezi zhášením DC a AC oblouku
- AC oblouk – proud přirozeně prochází nulou dvakrát za periodu (100× za sekundu při 50 Hz). V tomto okamžiku oblouk zaniká sám a stačí zabránit jeho opětovnému zapálení (dostatečná izolační pevnost mezery, ochlazení plazmatu). Zhášení je proto relativně snazší.
- DC oblouk – proud nemá přirozený průchod nulou, takže oblouk hoří trvale, dokud se uměle neprotáhne a neochladí natolik, že klesne pod hodnotu potřebnou k jeho udržení. Vyžaduje účinnější zhášecí opatření (např. zhášecí komory s dělicími můstky, magnetické vyfukování obloukem) a obecně je obtížnější a nebezpečnější než zhášení AC oblouku.

## Způsoby zhášení oblouku

### A. Dělením oblouku (vlastní zhášecí prostředky)

**a) Můstkové kontakty**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/39fdefac-2753-43eb-80be-f760e8a3bbd7" />

Můstkový kontakt (pohyblivý) rozdělí oblouk na dvě poloviny, čímž se napětí na oblouku rozdělí na polovinu. Tím vzniká výhodnější charakteristika hoření a dochází k rychlejšímu uhašení oblouku.
Používá se u vypínačů do 40 A.

**b) Zhášecí hřebeny**

<img width="461" alt="image" src="https://github.com/user-attachments/assets/387ec243-d8d6-449c-ac77-68cba427ddf5" />

*Zdroj obrázku: https://switchgearcontent.com/2019/09/05/853/arc-chutes-principles-in-air-at-lv-circuit-breaker/*

Oblouk je vháněn vlastním magnetickým polem do zhášecí komory, kde se na zhášecím hřebeni (celu) rozdělí na několik dílčích oblouků – obdobně jako u můstkových kontaktů se tím sníží napětí na jednotlivých částech a oblouk zhasne.
Komora je vyrobena z izolačního (odolného) materiálu. Pro zvýšení účinku se v praxi doplňuje pomocné magnetické pole v příčném směru, vytvářené např. elektromagnetem nebo permanentními magnety.

---

### B. Cizí zhášecí prostředky

Používají se u elektrických přístrojů na vysoké napětí (VN), velmi vysoké napětí (VVN) a zvlášť vysoké napětí (ZVN).

**a) Minerální oleje**

V současnosti se využívají u máloolejových výkonových vypínačů.

<img width="325" height="400" alt="image" src="https://github.com/user-attachments/assets/bf4403d3-a27f-4507-a7b2-cc7e3cf6ea51" />

<img width="450" height="361" alt="image" src="https://github.com/user-attachments/assets/e11bcb09-aa72-49db-bdc5-ed3fd6ee0977" />


---

**b) Stlačený vzduch**

Vypínače vypínají tlakem vzduchu cca 30 MPa. Jsou velmi rychlé a výkonné, avšak hlučné a energeticky náročné.

**c) Fluorid sírový (SF₆)**

<img width="512" alt="image" src="https://github.com/user-attachments/assets/48f528c9-a449-4088-a3dc-f2d31dea4194" />

*Zdroj obrázku: https://okmarts.com/news/how-do-circuit-breakers-extinguish-electric-arc.html*

Elektronegativní plyn s vysokou dielektrickou pevností a schopností rychle zachytávat volné elektrony, čímž urychluje deionizaci a zhášení oblouku. Má přibližně 3× lepší elektrickou pevnost než vzduch. 

---
**d) Vakuum (p ≈ 10⁻¹⁰ Pa)**

Vakuová komora – kontakty jsou umístěny ve vysokém vakuu, kde chybí médium schopné oblouk udržet; oblouk (tvořený parami kovu z kontaktů) zhasíná velmi rychle při průchodu proudu nulou.

<img width="200" height="803" alt="image" src="https://github.com/user-attachments/assets/ae939d27-0b62-433c-a31c-54376bb6504b" />



# Elektrický oblouk – vznik, rizika a zhášení


**Jak vzniká elektrický oblouk mezi rozpojujícími se kontakty?**
<details>
<summary>Odpověď</summary>
Ionizací plynu v mezeře mezi kontakty. Volné elektrony jsou urychlovány elektrickým polem a při srážkách s atomy plynu je ionizují, čímž vzniká vodivý plazmový kanál, kterým prochází proud i po oddálení kontaktů.
</details>

---
**Jaká rizika pro elektrické přístroje přináší elektrický oblouk?**
<details>
<summary>Odpověď</summary>
- pokračující průtok proudu i po vypnutí – dokud oblouk hoří, obvodem stále protéká proud, takže samotné rozpojení kontaktů ještě neznamená přerušení obvodu; teprve zhasnutí oblouku skutečně přeruší tok proudu.
- přehřátí a poškození kontaktů – kontakty se opalují, taví a mohou se svařit,
- poškození izolace – vysoká teplota může roztavit nebo zuhelnatět izolační materiál,
- elektromagnetické rušení – oblouk vytváří vysokofrekvenční rušení,
- požár – vysoká teplota oblouku může zapálit okolní materiály,
</details>

---
**Co je hlavní příčinou opalování kontaktů?**
<details>
<summary>Odpověď</summary>
Vysoká teplota oblouku (až několik tisíc °C), která taví a odpařuje materiál kontaktů. To zkracuje jejich životnost, zvyšuje přechodový odpor a při opakovaném spínání může vést až ke svaření kontaktů.
</details>

---
**Proč je zhášení AC oblouku snazší než DC oblouku?**
<details>
<summary>Odpověď</summary>
U AC prochází proud přirozeně nulou dvakrát za periodu (100× za sekundu při 50 Hz) a v tomto okamžiku oblouk zaniká sám – stačí zabránit jeho opětovnému zapálení. DC oblouk nemá přirozený průchod nulou a hoří trvale, dokud se uměle neprotáhne a neochladí.
</details>

---
**Jaké metody se používají ke zhášení DC oblouku?**
<details>
<summary>Odpověď</summary>
Protože DC oblouk nemá přirozený průchod nulou, musí se uměle protáhnout a ochladit pod hodnotu potřebnou k jeho udržení. Používají se např. zhášecí komory s dělicími můstky, magnetické vyfukování oblouku nebo zhášení cizím médiem - olejem, stlačeným vzduchem SF6 či zhášení ve vakuu..
</details>

---
**Proč je vypínání induktivních zátěží (motorů, transformátorů) náročnější na zhášení oblouku?**
<details>
<summary>Odpověď</summary>
Indukčnost se brání náhlé změně proudu a při přerušení obvodu generuje vysoké přepětí (u = -L·di/dt), které se snaží proud udržet i přes rozpojující se kontakty. To vede k intenzivnějšímu a hůře zhasitelnému oblouku i k namáhání izolace přepětím.
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
