﻿# STATKI_GAME
Popularna gra w statki w której gramy z komputerem
Technologie jakie wykorzystałem w mojej aplikacji to czysty JavaScript, HTML i CSS
Każda funkcja zwięźle zakomentowana i opisana za co opdowiada
W kodzie mamy możliwość zmiany ilości statków ich rozmiaru oraz wielkości planszy ponieważ elementy są tworzone dynamicznie.

Po krótce streszczając kod aplikacji można go podzielić na trzy części:
1. Wygenerowanie statków z "kwadratów" np. statek o długości 3 składa się z 3 kwadratów. Gracz zaznacza który statek chce postawić na planszy, po postawieniu statek znika
2. Wyświetlenie pustej planszy na której gracz ma postawić swoje statki (gra nie pozwoli graczowi na postawienie statku nie zgodnie z zasadami). Gracz ma możliwość obrotu statku.
3. Wylosowanie ułożenia statków "komputera" (czyli przeciwnika)

Po czym rozpoczony się rozgrywka w której to gracz i "komputer" na zmianę oddają strzały na tablice gdy pudłują pojawia się O gdy trafią X a gdy zatopią statek podświetla się. Dodatkowo na górze strony są wyświetlane wiadomości do gracza które przedstawia obecną sytuację w grze czyli co gracz ma zrobić, kogo jest ruch oraz np rezultat strzału.

Wszystkie operacje logiczne odbywaja się na tablicach 2d
