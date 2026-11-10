# Náhradní schéma a fázorový diagram transformátoru

Náhradní schéma transformátoru je poskládáno z podélné větve složené z činných odporů
primárního a sekundárního vinutí (R1 a R2) a induktivních reaktancí obou cívek procházených
rozptylovým tokem (X1σ, X2σ) a z příčné větve složené z magnetického odporu magnetického
obvodu (RFe) a reaktance magnetického obvodu (Xμ).

<img width="1355" alt="image" src="https://github.com/user-attachments/assets/679827c1-8158-47c6-9d60-152af97b9a1f" />

X1 - rozptylová reaktance primární cívky dané rozptylovým magnetickým tokem Φ1
X2 - rozptylová reaktance sekundární cívky dané rozptylovým magnetickým tokem Φ
R1, R2 - činné odpory cívek
RFe - odpor magnetického obvodu je dán tepelnými ztrátami
X - reaktance magnetického obvodu


## Transformátor naprázdno

<img width="600" alt="image" src="https://github.com/user-attachments/assets/2f41515d-7fda-4137-83cd-d83c61ee8d52" />

Transformátor ve stavu naprázdno má rozpojené sekundární svorky a sekundárním vinutím tedy neprochází žádný proud. Vstupním vinutím prochází proud I10, který je velice malý a slouží k vytvoření magnetického toku v jádře a ke krytí ztrát v magnetickém obvodu. Skládá se tedy ze dvou částí:
z proudu magnetizačního I (fázově posunutého o 90°za Ui), který vytváří magnetické pole a z proudu na krytí tepelných ztrát v železe IFe (ve fázi s napětím Ui). Voltampérová charakteristika transformátoru naprázdno odpovídá magnetizační charakteristice. Ztráty v primárním vinutí jsou díky malému proudu velice malé, a proto je
zanedbáváme, veškeré ztráty ve stavu naprázdno tedy považujeme za ztráty v železe.


## Transformátor nakrátko

<img width="600" alt="image" src="https://github.com/user-attachments/assets/b6e5056f-54fe-4e47-998b-8a93ea6917dc" />

Transformátor ve stavu nakrátko má sekundární svorky propojeny bezodporovou propojkou (tedy napětí U2 = 0) a sekundárním obvodem prochází obrovský proud, který natolik zahřívá transformátor, že by mohlo dojít k jeho zničení. Musí tedy dojít k reakci ochran a transformátor musí
být odpojen. Při měření stavu nakrátko jsou výstupní svorky také spojeny do krátka a proto musíme snížit napětí na primární cívce tak, aby sekundárním vinutím procházel právě jmenovitý proud, který nezpůsobí zničení transformátoru. Sníženému primárnímu napětí říkáme napětí nakrátko a často jej vyjadřujeme
v procentech jmenovitého napětí.

Náhradní schéma transformátoru ve stavu nakrátko kreslíme bez paralelní větve RFe, X, neboť impedance zkratu je mnohonásobně menší a tedy téměř celý proud bude procházet zkratem. Měřením nakrátko (měříme napětí U1K, proud I1K a výkon P1K na primární straně) jsme zjistili
parametry....
