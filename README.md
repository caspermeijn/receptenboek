---
# SPDX-License-Identifier: CC-BY-SA-4.0
# Copyright © 2021 Casper Meijn <casper@meijn.net>
# 
# This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. 
# To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or 
#   send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
---

Receptenboek
============

Dit is de broncode voor ons receptenboek. Het is gemaakt met [Hugo](https://gohugo.io/) static site generator en het [gochowdown](https://github.com/seanlane/gochowdown) thema. De recepten staan in de content map. Per recept is er een mapje met daarin een markdown bestand voor de tekst en een afbeelding.

GitPod
---------
Voor deze repository is GitPod ingesteld. Dit is een online VSCode. Ga naar [https://gitpod.io/#https://github.com/caspermeijn/receptenboek]. Er opent editor waarin een preview van het Receptenboek zichtbaar is. In deze editor kunnen de gewenste aanpassingen gemaakt worden en direct een pull request voor maken.

Nieuw recept
------------
Een nieuwe recept kan makkelijk door middel van een archetype aangemaakt worden. Vanuit GitPod kan je het volgende doen:
- Druk op F1
- Kies voor `Hugo: create content from archetype`
- Kies voor `recipes`
- Type de naam van de map voor het nieuwe recept
- Pas het bestand `recipes/nieuwe-naam/index.md` aan
- Voeg een foto toe
- Maak een PR in Github

License
-------
Dit werk valt onder een [Creative Commons Naamsvermelding-GelijkDelen 4.0 Internationaal-licentie](https://creativecommons.org/licenses/by-sa/4.0/).

Alle bestanden moeten een copyright notice hebben of er moet een `.license` betand met de notice. Hiermee is het compatible met [REUSE](https://reuse.software/).

