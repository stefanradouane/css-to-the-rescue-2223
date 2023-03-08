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

### Versie 1

Na de eerste dag aan de opdracht werken had ik eigenlijk al een rubiks cube gemaakt van HTML en CSS. Deze cubus bestond uit 54 losse `div`'s. Ik liep alleen tegen een probleem aan nu en dat is dat ik de losse divs niet draaibaar kon maken, omdat ik deze divs met een eigen transform op de cube had geplaatst.

<img src="/assets/process-images/v1.png"
     alt="v1 image"
     style="width: 300px;"/>

<img src="/assets/process-images/v1-code.png"
     alt="v1 code"
     style="width: 300px;"/>

### Versie 2

#### Kubus schets

Vervolgens heb ik de hele cube opnieuw gemaakt, maar nu met 24 `span`'s voor alle blokken op de cube. Elk blokje kan bestaan uit 1, 2 of 3 vlakken. En elke vlak heeft een eigen positie in een 3D omgeving, deze omgeving is maximaal 300px bij 300px bij 300px. Elke 'blokje' is maximaal 300px bij 300px en staat ontzichtbaar gecentreerd in het midden van de kubus. De vlakken zijn wel zichtbaar en zijn allemaal correct gepositioneerd. Op deze manier kan ik het midden van het blokje draaien, en hierdoor draaien de vlakken correct mee.

Om dit idee uit te werken heb ik eerst een schets gemaakt.

<img src="/assets/process-images/v2-schets.png"
     alt="schets 3D-cube"
     style="width: 300px;"/>


#### Kubus fases

Om eerlijk was het wel een beetje puzzelen hoe de kubus nou precies opgebouwd moest worden uit kleuren, maar het is uiteindelijk wel gelukt.

<img src="/assets/process-images/v2-cube-fase-1.png"
     alt="3D-cube fase 1"
     style="width: 75px;"/>
<img src="/assets/process-images/v2-cube-fase-2.png"
     alt="3D-cube fase 2"
     style="width: 75px;"/>
<img src="/assets/process-images/v2-cube-fase-3.png"
     alt="3D-cube fase 3"
     style="width: 75px;"/>

<img src="/assets/process-images/v2-cube-fase-end.png"
     alt="3D-cube fase end"
     style="width: 100%;"/>


-   24 spans met daarin 1, 2 of 3 spans.
-   Dit is wel animeerbaar.
-   Foto van hoe de cubus is op gebouwd (schaal tekening)
-   Ik vond het lastig om de cubus te laten draaien
-   Nieuwe oplossing Impossible cube

### Versie 3

-   FB: Toch proberen werkend maken
-   Werkend gemaakt (levels rubisk cube)
-   Werkend.

### Versie 4 (eind)

-   Laatste versie
-   Alles fancy maken
-   Structuur van css bestanden (modulair)
-   Kleuren (werken met display-p3)
-   Slider
-   Levels (spectator)
-   Overheating cube.

Comming very soon...
