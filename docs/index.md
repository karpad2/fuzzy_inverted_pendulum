Óbudai Egyetem

![Óbudai Egyetem (\@uni_obuda) \|
Twitter](docs/media/image1.png){width="1.463999343832021in"
height="1.463999343832021in"}

Inverz inga szabályozása fuzzy és Labview alkalmazássávaL

projektum\
Fuzzy rendszerek tárgyból

témavezető: Dr.Simon János hallgató: Kovács Árpád\
főiskolai tanár Neptun kód: BPJZ56

Szabadka, 2020

Tartalom {#tartalom .TOC-Heading}
========

[Bevezető 4](#bevezető)

[1. Projektfeladat 4](#projektfeladat)

[2. Elméleti alapok 4](#elméleti-alapok)

[A felhasznált rövidítések 7](#a-felhasznált-rövidítések)

[Irodalom 7](#irodalom)

Bevezető
========

A dokumentum a fuzzy rendszerek projektumának tárgy dokumentálásának
céljából jött létre.

Projektfeladat
==============

Az én projekt feladatom az volt, hogy egy modellt felállítani majd ezt a
modellt szimulálni, s majd ezt a modellt fuzzy-val szabályozni. Ehhez a
modellhez az állapottéri modellt használtam fel.

Elméleti alapok
===============

![21.4. A megerősítéses tanulás általánosító-képessége \| Mesterséges
Intelligencia Elektronikus
Almanach](docs/media/image2.png){width="3.8017924321959753in"
height="3.1557852143482066in"}

#### Állapottéri modell:

![](docs/media/image3.png){width="0.7501049868766404in"
height="0.9793033683289589in"}

A kimeneti egyenletek ilyen módon egyszerűen adódnak, mert a mért érték
az inga szöghelyzete:

$$y = x_{3}$$

![](docs/media/image4.png){width="3.6359241032370955in"
height="1.156411854768154in"}

##### Az inga fizikai adatai:

A modellt a következő weboldalról töltöttem le:.

<https://ctms.engin.umich.edu/CTMS/index.php?example=InvertedPendulum&section=ControlStateSpace>

$$g = 9,81\frac{m}{s^{2}}$$

$$l = 0,3m$$

Behelyettesítve az adatokat:

![](docs/media/image5.png){width="3.427561242344707in"
height="2.6253663604549433in"}

A rendszer pólusai:

![](docs/media/image6.png){width="1.1980839895013122in"
height="1.2397561242344708in"}

#### Fuzzy szabályozás

A fuzzy szabályozás egy típusa a sávos logikának melyett elmósodott
halmazok logikájának neveznek.Ebben az állapotban úgy lett beállítva a
fuzzy mint egy lookup table. Adott értékre add, vagy visszavessz az
alapnak a sebbességéből. Ezáltal próbál egyensúlyozni.

![](docs/media/image7.png){width="6.8in" height="4.446527777777778in"}

ábra 1 Front panel

![](docs/media/image8.png){width="7.014173228346457in"
height="3.376000656167979in"}

ábra 2 Block diagram

### 3D modell:

A labview tartalmazz egy 3d megjelenítő modult, mely segítségével lehet
ábrázolni 3D testek mozgását. Gyárilag a labview is tartalmazz egy példa
programot a 3D inverz inga megjelenítéséhez ezért ez használtam fel.

![](docs/media/image9.png){width="6.8in" height="1.6756944444444444in"}

ábra 3 3D modell mozgatása

![](docs/media/image10.png){width="6.03200021872266in"
height="4.426669947506562in"}

A felhasznált rövidítések
=========================

A használt rövidítések jegyzéke és azok jelentése.

Irodalom
========

<https://www.w3schools.com/php/php_mysql_intro.asp>

<https://people.vts.su.ac.rs/~simon/bp2/Baze_Podataka2_Prirucnik_SR_2015.pdf>

<http://uni-obuda.hu/fodor/06_fuzzy_iranyitas.pdf>

<https://ctms.engin.umich.edu/CTMS/index.php?example=InvertedPendulum&section=ControlStateSpace>
