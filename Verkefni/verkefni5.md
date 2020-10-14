# Verkefni 5 - 20%

Simon Says

## Verkefnalýsing

* Í þessu verkefni ætlar þú að smíða frá grunni, spilið [Simon Says](https://en.wikipedia.org/wiki/Simon_(game)).
* Fylgdu [Simon Says tutorial](https://www.instructables.com/id/Arduino-Simple-Simon-Says-Game/).
  * Settu Arduino [hugbúnaðinn](https://github.com/VESM1VS/H20/blob/master/Kennsluefni/arduino_uppsetning.md) upp á tölvuna þína og settu upp *ToneLibrary* safnið.
* Gerðu þína eigin 3D hönnun (frjáls útfærsla) með Tinkercad. Hér er metnaðarfullt [hönnunar sýnidæmi](https://www.youtube.com/watch?v=MDbnw7U_0-Q&vl=en).

Þegar þú hefur lokið við verkefnið ættir þú að hafa fullbúið spil í höndunum sem er tilbúið að fara í sölu.

## Skýrsla

Búðu til Github wiki síðu sem inniheldur eftirfarandi, skilaðu svo hlekk á síðuna á Innu:

* Hönnunarteikning (.stl)
* Ljósmynd af samsetningu (brauðbretti, skynjarar, vírar o.s.frv.).
* Myndband af virkni frumgerðar (án lóðunar og 3D prentunar).
* Ljósmynd af lóðun (þegar skólinn opnar aftur).
* Myndband af vikni lokafurðar (þegar skólinn opnar aftur).
* Ljósmynd af lokaafurð (þegar skólinn opnar aftur).

## Námsmat og skil

1. 6% 3D hönnun (frjáls útfærsla).
1. 6% Rafeindatækni og samsetning; Arduino, brauðbretti, vírar, buzzer, viðnám, led, hnappar osfrv.
1. 6% Lóðun á veroborð (þegar skólinn opnar aftur).
1. 2% Kóðavirkni.

Gefið er fullt fyrir hvern lið sem er fullnægjandi, hálft ef hann er ábótavant.
Skilaðu í Innu vefslóð á Github repository.

### Villa í kóða

Það er villa í kóðanum sem er á [Simon Says tutorial](https://www.instructables.com/id/Arduino-Simple-Simon-Says-Game/) vefsíðunni. Villurnar eru í línum 15 og 16 ca., þar er verið að skilgreina 2 fylki (```button``` og ```ledpin```) sem boolean en það þarf að skilgreina þau sem int. Villan lýsir sér þannig að það kviknar ekki á neinum led perum en tónlistin spilar eðlilega.

Línurnar

```cpp
boolean button[] = {2, 3, 4, 5}; //The four button input pins
boolean ledpin[] = {8, 9, 10, 11};  // LED pins
```

eiga að vera svona:

```cpp
int button[] = {2, 3, 4, 5}; //The four button input pins
int ledpin[] = {8, 9, 10, 11};  // LED pins
```
