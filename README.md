# Budget_DK

En dansk budgetberegner i stil med Luksusfælden – samlet i én HTML-fil, der kører direkte i browseren. Ingen installation, ingen konto og ingen server.

## Funktioner

- **Løn før skat → udbetalt løn** med 2026-satser: AM-bidrag, ATP, kommune- og kirkeskat, bundskat, mellemskat, topskat og toptopskat, personfradrag, beskæftigelsesfradrag og jobfradrag.
- **Lønseddel pr. måned**: egen og firmabetalt pension (også med pensionsgrundlag), lønsedlens linjer (tillæg, skattepligtige goder, træk før og efter skat) og korrektioner, der kun gælder én måned.
- **Egen trækprocent og eget skattefradrag** fra lønsedlen, så beregningen rammer den rigtige lønseddel.
- **Faktisk udbetalt** pr. måned, som bruges i budgettet i stedet for den beregnede løn.
- **Poster pr. måned** med hyppighed (ugentligt, månedligt, kvartalsvis, halvårligt, årligt), der omregnes til et månedligt beløb.
- **Én eller flere personer**: bor man alene, er der én person. Bor man sammen, tilføjer man flere og vælger for hver post, om den er fælles eller kun én persons.
- **Rådighedsbeløb** for hele husstanden eller for den enkelte person, budgetkonto til regninger, der ikke kommer hver måned, og nøgletal.
- **Træk og slip** til at flytte poster rundt og mellem kategorier.
- **Gem som fil og importér**: gem budgettet som en `.json`-fil på pc eller mobil, og åbn det igen senere eller på en anden enhed.

## Hent beregneren

- **[⬇ Hent som ZIP](../../archive/refs/heads/main.zip)** – pak den ud og åbn `index.html`.
- **Via GitHub Pages** – åbn siden og tryk **Hent beregneren** øverst. Så får du `budget-beregner.html` som én fil.
- **[Hent filen direkte](../../raw/main/index.html)** – højreklik på linket og vælg **Gem link som…**.

Filen virker uden internet: gem den på pc'en eller telefonen og åbn den i en browser.

## Sådan bruger du den

1. Åbn den hentede fil i en browser – eller brug GitHub Pages-linket, hvis det er slået til.
2. Ret **kommuneskat** og **kirkeskat** til din egen kommunes satser (de står på skat.dk og på din forskudsopgørelse).
3. Skriv din bruttoløn og linjerne fra din lønseddel ind. Tilføj eventuelt en partner eller samlever med **+ Tilføj person**.
4. Udfyld dine poster for måneden. Brug **Kopiér beløb fra …** for at overføre faste poster til en ny måned.
5. Tryk **Gem som fil…** for at gemme en kopi, du selv bestemmer placeringen af.

## Dine data

Alt bliver i din egen browser (localStorage) eller i de filer, du selv gemmer. Intet sendes til en server. Siden henter kun skrifttyper fra Google Fonts; uden internet bruges systemets skrift.

## Forbehold

Beregningen er et estimat og erstatter ikke din lønseddel eller din forskudsopgørelse fra Skattestyrelsen. Skattesatserne gælder for 2026.

## Licens

Copyright (c) 2026 dashcoon.

Udgivet under [MIT-licensen](LICENSE). Du må frit bruge, kopiere, ændre og dele beregneren, også kommercielt, så længe copyright- og licensteksten følger med.
