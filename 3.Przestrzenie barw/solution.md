Kurde zadanko nr 3
==================

Będzie w tabelce a komentarze na dole

|                                          | RGB | CIE-XYZ | CIE-L*u*v* | HSL | CMYK | Y'CbCr |
|------------------------------------------|-----|---------|------------|-----|------|--------|
| Liniowość                                |  v  |    v    |      x     |  x  |   x  |    x   |
| Kolory ujemne                            |  x  |    x    |      x     |  x  |   x  |    v   |
| Zależy od urządzenia                     |  x  |    x    |      x     |  x  |   v  |    x   |
| Precyzyjnie równomierny rozkład kolorów  |  x  |    x    |      v     |  x  |   x  |    x   |
| Cała szarość jedną współrzędną           |  x  |    x    |      x     |  v  |   x  |    v   |
| Wszystkie kolory tęczy jedną współrzedną |  x  |    x    |      x     |  v  |   x  |    x   |

Liniowość
---------

TO najprostsze, w Y'CbCr na pewno liniosość psuje luma Y' bo jest po korekcji gamma

Kolory ujemne
-------------

Nie jestem pewien, explicite kolory ujemne posiada Y'CbCr bo to są te różnice
pomiędzy odcieniami. Nwm jak z resztą bo mają kolory które nie wpadają w gamucie np RGB...

Zależy od urządzenia
--------------------

O ciul chodzi, na pewno CMYK, RGB są różne standardy ale nwm.

Precyzyjnie równomierny rozkład kolorów
---------------------------------------

To te śmieszko elipsy w CIE-L*u*v*

Cała szarość
------------

Y' to jasność, jak jesteś w odpowiednim punkcie to tylko Y' manipulujesz, HSL chyba też...

Tęcza
-----

Parametr "odcień" w HSL
