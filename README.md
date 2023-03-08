# :package: The Cube Trainer

Dit is het proces van het vak CSS to the rescue.
Gemaakt door Stefan Radouane

## :alembic: Mijn leerdoel

Ik wil tijdens dit vak de nieuwste CSS features leren en experimenteren met 3D objecten, vervolgens wil ik deze nieuw geleerde technieken toepassen in mijn eindopdracht.

## :sparkles: Keuze project en browser

Voor het project is het de bedoeling dat we een keuze maakten uit 3 opdrachten de opdrachten de opties waren:

- Een bedieningspaneel
- Een vuurwerkshow
- Een rubiks cube

Ik heb uiteindelijk gekozen voor de rubiks cube, omdat ik toevallig zelf ook bezig was met het leren van een rubiks cube oplossen. Daarnaast paste dit precies bij het leerdoel van mij dat ik wil leren om 3D objecten te maken met CSS.

## Proces

### Versie 1 - Simpele kubus

Na de eerste dag aan de opdracht werken had ik eigenlijk al een rubiks cube gemaakt van HTML en CSS. Deze cubus bestond uit 54 losse `div`'s. Ik liep alleen tegen een probleem aan nu en dat is dat ik de losse divs niet draaibaar kon maken, omdat ik deze divs met een eigen transform op de cube had geplaatst.

<img src="/assets/process-images/v1.png"
     alt="v1 image"
     style="width: 45%;"/>
<img src="/assets/process-images/v1-code.png"
     alt="v1 code"
     style="width: 45%;"/>

### Versie 2 Draaibare kubus

#### Kubus schets

Vervolgens heb ik de hele cube opnieuw gemaakt, maar nu met 24 `span`'s voor alle blokken op de cube. Elk blokje kan bestaan uit 1, 2 of 3 vlakken. En elke vlak heeft een eigen positie in een 3D omgeving, deze omgeving is maximaal 300px bij 300px bij 300px. Elke 'blokje' is maximaal 300px bij 300px en staat ontzichtbaar gecentreerd in het midden van de kubus. De vlakken zijn wel zichtbaar en zijn allemaal correct gepositioneerd. Op deze manier kan ik het midden van het blokje draaien, en hierdoor draaien de vlakken correct mee.

Om dit idee uit te werken heb ik eerst een schets gemaakt.

<img src="/assets/process-images/v2-schets.jpeg"
     alt="schets 3D-cube"
     style="width: 45%;"/>


#### Kubus fases

Om eerlijk was het wel een beetje puzzelen hoe de kubus nou precies opgebouwd moest worden uit kleuren, maar het is uiteindelijk wel gelukt.

<img src="/assets/process-images/v2-cube-fase-1.png"
     alt="3D-cube fase 1"
     style="width: 20%;"/>
<img src="/assets/process-images/v2-cube-fase-2.png"
     alt="3D-cube fase 2"
     style="width: 20%;"/>
<img src="/assets/process-images/v2-cube-fase-3.png"
     alt="3D-cube fase 3"
     style="width: 20%;"/>

<img src="/assets/process-images/v2-cube-fase-end.png"
     alt="3D-cube fase end"
     style="width: 45%;"/>
<img src="/assets/process-images/v2-code.png"
     alt="v2 code"   
     style="width: 45%;"/>

> Zoals je kan zien gebruik ik `data-color` om de kleur van het vlak te bepalen. Dit zorgt ervoor dat ik gemakkelijk verschillende level kan implementeren.

#### Draaibaar maken

Nu ik de cubus had ging ik proberen om de rijen van de kubus te laten draaien. Na veel proberen met de kubus had ik het opgegeven, omdat ik hoofdpijn kreeg van het proberen. Ik heb op dit moment bedacht om mijn idee te veranderen naar de 'impossible cube'. Het lukte mij wel om de losse blokken te transformeren, alleen niet op een realistiche wijze, daarom dacht ik met CSS kan je de natuurwetten een beetje verbuigen en dat zorgt ervoor dat de impossible cube wel mogelijk was op een website. 

<img src="/assets/process-images/v2-impossible.png"
     alt="v2 impossible"   
     style="width: 45%;"/>


### Versie 3

#### Cube trainer

Tijdens werd mij verteld dat ik het toch nog een keer moest proberen om de kubus draaibaar te maken. Ik heb hiernaar geluisterd en heb het een tweede kans gegeven. Aangezien een kubus [43.252.003.274.489.856,000](https://www.redbull.com/nl-nl/10-feiten-rubiks-cube#:~:text=43.252.003.274.489.856%2C000) mogelijkheden, heb ik dit iets versimpeld voor mijzelf. Ik weet dat er een beginners stappen plan is om te leren hoe je een kubus moet oplossen, en ik heb dus besloten om mijn concept te veranderen naar een 'cube trainer'. Dit concept splitst de kubus op in 7 levels. Elk level heeft een aantal stappen die gevolgt moeten worden, om de kubus op te lossen. Ik heb besloten om de laatste stap van deze stappenreeks uit te werken.

Als eerst heb ik bedacht om dit te doen met een soort spel bedieningspaneel. Ik heb hiervoor een schets gemaakt, maar ik vond zelf gelijk na het schetsen dat dit paneel te druk was. Ik heb bepaalde onderdelen hiervan wel verwerkt in de uiteindelijke werking van mijn concept.

<img src="/assets/process-images/v3-schets.jpeg"
     alt="schets bedieningspaneel"
     style="width: 45%;"/>

Daarnaast heb ik ook een schets gemaakt van het level overzicht.

<img src="/assets/process-images/v3-schets-levels.jpeg"
     alt="schets levels"
     style="width: 45%;"/>


#### Werking level

Ik heb besloten om wel te werken met 6 knoppen (links onder op de schets). Met deze knoppen wil ik het mogelijk maken om de kubus op te lossen. Ik heb ervoor gekozen dat de juiste knop elke keer op een andere plaats staat, zodat dit niet elke keer bijvoorbeeld links boven is.

<img src="/assets/process-images/v3-werking-levels.jpeg"
     alt="schets werking levels"
     style="width: 45%;"/>



### Versie 4 (eind)

-   Laatste versie
-   Alles fancy maken
-   Structuur van css bestanden (modulair)
-   Kleuren (werken met display-p3)
-   Slider
-   Levels (spectator)
-   Overheating cube.

Comming very soon...
