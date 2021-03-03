# Procesverslag

# Index

- [Welke Opdracht](#Welke-Opdracht)
- [Welke CSS Technieken](#Welke-CSS-Technieken)
- [Uitdagingen](<#Waar-liggen-de-(grootste)-uitdagingen>)
- [breakdown](#Breakdown-Schets)

## Welke Opdracht?

CSS Zen Garden - 2021 version

- Responsive restaurant menu (de ruwe html) <!-- EEN FOLDER, maar dan 1 die veel vaker uitklapt dan verwacht. -->
- Context: prefers-color-scheme & prefers-reduced-motion || print-stylesheet<!-- kleuren aanpassen a.d.h. preffered theme. -->
- Eisen: Geen vierkanten, rechthoeken, cirkels en driehoeken <!-- Ik wil de vormen 'semi' random maken.   --> & Twee kleuren

## Welke CSS-Technieken?

- [x] grid || Flex
- [x] Clamp
- [x] Transform (rotateX,Y, Z??)
- [x] prefers-color-scheme
- [ ] prefers-reduced-motion
- [x] root, css-variabelen
- [x] @keyframes
- [ ] @media print

## Waar liggen de (grootste) uitdagingen?

- Het leesbaar houden van de teksten die op de folder staan (gerechten)
  Neem Schets(en) van het ontwerp op.
- het rouleren / verplaatsen van de menu kaartjes
- Het behouden van kleur op de print versie.

## Breakdown Schets:

Hieronder ziet u de breakdown schets.
![Breakdown Schets](/assets/breakdown.JPG)

Het concept is om een uitklappende folder te realiseren. Een folder met 2 voorzijden. Hiervoor zijn de pseudo-elementen `:after` en `:before`. Binnen de folder wordt de informatie betreffende het gerecht weergegeven.

## Experimenten

- Onderzoek gedaan naar hoe het uiklappen van menukaarten reeds door anderen eerder gedaan is:
  https://codepen.io/lomojean/pen/EbKvu
- Nadat ik het college over typografie gevolgd heb ben ik gaan kijken hoe ik deze informatie het beste kon toepassen binnen dit concept.

## Nieuwe Inzichten

#### Random

Aan het begin van dit vak had ik veel ideeën die moeilijk uitvoerbaar waren binnen de context van deze opdracht. Ik wilde (semi) random vormen maken. Echte willekeurigheid is helaas moeilijk te bewerkstelligen in css.

#### Print

Het opmaken van een print stylesheet riep bij mij al gauw nieuwe vragen op.
![printStylesheet](/assets/printStylesheet.JPG)

Zo is het dat zelfs bij het uitzetten van achtergrondafbeeldingen er nog steeds kleuren doorgegeven worden. Wanneer is iets gedefinieerd als een achtergrondafbeelding en wanneer niet? Dit is afhankelijk van de property en het html element. Tekst zal dan ook niet als achtergrondafbeelding geinterpreteerd worden. Daarom zijn hier de kleuren blijven staan.

## Referenties:

- https://codepen.io/lomojean/pen/EbKvu
- https://css-tricks.com/almanac/
