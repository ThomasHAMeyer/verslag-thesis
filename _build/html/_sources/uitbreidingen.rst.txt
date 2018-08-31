=====================
Verdere uitbreidingen
=====================
Hieronder bespreken we verdere uitbreidingen die gedaan moeten/kunnen worden om het prototype beter te maken.
Deze uitbreidingen bevatten onder andere geplande delen die niet geïmplementeerd geraakt zijn als uitbreidingen die een verhoging in het gebruiksgemak teweeg kunnen brengen.

Berichten hergebruiken
======================
Een mogelijkheid die van bij aanvang gepland was maar die we niet hebben kunnen implementeren, is om feedbackberichten op te slaan en te hergebruiken (met de mogelijkheid om ze ook nog te bewerken).
Dit zou met verschillende scopes gedaan worden, zodat lesgevers berichten konden opslaan om te hergebruiken voor dezelfde oefening, voor dezelfde review (verschillende oefeningen) of globaal.
Deze feature zou het mogelijk maken om veelgemaakte opmerkingen eenvoudig te hergebruiken.
Afhankelijk van hoe vaak een gelijkaardige opmerking gemaakt moet worden zal deze feature een grotere dan wel kleinere impact hebben op de duur van het verbeterproces.

Peer reviews
============
Een zeer nuttige manier van leren is door middel van peer reviews, het verbeteren van oplossingen van andere studenten en feedback van andere studenten krijgen.
Het huidige systeem aanpassen om een optie te geven dat studenten aan peer reviews kunnen doen is relatief eenvoudig te doen.
Dit vergt aangepaste versies van de bestaande views en controllers waarbij er voor gezorgd moet worden dat anonimiteit verzekerd is.
Dit zou een zeer gewenste uitbreiding zijn omdat er voorlopig maar weinig systemen zijn die toelaten om eenvoudig peer reviews te doen.

Puntentelling
=============
Een logische uitbreiding is om punten te kunnen geven aan oplossingen.
Als dit op een gestructureerde manier gedaan wordt dan kan ervoor gezorgd worden dat dezelfde fout voor alle studenten evenveel impact heeft.
Als verschillende studenten dezelfde fout maken, dan zouden we hier dezelfde rubric aan kunnen linken.
Deze rubric geeft dan aan hoe zwaar de fout doorweegt.
Als er dan later besloten wordt dat deze fout meer of minder moet doorwegen dan moet deze rubrics één keer aangepast worden en geldt de aanpassing voor alle studenten. 
Op papier vereist het aanpassen van het gewicht van een fout dat alle reeds verbeterde oplossingen gecorrigeerd worden.

Automatische suggesties
=======================
Een geavanceerde uitbreiding zou zijn om met behulp van machine learning opmerkingen voor te stellen.
Dit zou het verbeter proces kunnen versnellen door te zoeken naar fouten en de daarmee gepaarde opmerkingen.
Dit zou in een eerste stap zoeken naar code of patronen waar vaak opmerkingen op gemaakt worden en dan in een volgende stap de meest gepaste opmerking voorstellen.

Een uitdaging hierbij is dat het snel moet gebeuren. Het is niet acceptabel om minuten te moeten wachten vooraleer men kan beginnen reviewen.
Een volgend "probleem" is het vinden van data. Voor machine learning hebben we veel data nodig wat hier moeilijk is.
Zo zijn de opmerkingen en fouten anders voor elke taal en is iets wat in een basiscursus aangeleerd wordt mogelijk fout voor een cursus gevorderde algoritmen waar de voorgestelde oplossing niet performant genoeg is.
Zo zijn geneste for-lussen iets wat een beginnend programmeur snel zal gebruiken terwijl dit voor ervaren programmeurs niet acceptabel is vanwege de complexiteit.  

PDF generatie
=============
Een feature die niet prioritair, maar wel nuttig is, is het kunnen omzetten van beoordeelde oplossingen naar pdf-formaat.
Dit zou gebruikt kunnen worden als het verplicht is om een papieren versie te archiveren.
Dit vereist dat er een speciaal formaat gezocht moet worden om de code en de opmerkingen ordelijk samen te voegen in pdf-formaat.
Zo is de aanpak gebruikt door Pycco zeer overzichtelijk maar zou het de pdf veel langer maken wat niet de bedoeling is.
Maar aangezien we beperkt zijn tot A4 formaat is het ook niet mogelijk om een zijbalk met daarin de opmerkingen te gebruiken.

Anonimiteit beoordelaar
=======================
Een kleine uitbreiding om te implementeren, is om de identiteit van de beoordelaar te verbergen.
Dit heeft als effect dat gebruikers niet kunnen klagen over wie hun oplossing heeft beoordeeld, maar dat ze enkel kunnen klagen over de beoordeling zelf.
Deze uitbreiding moet ook geïmplementeerd worden als men de peer reviews uitbreiding zou maken, zodat het niet mogelijk is om te weten wie welke beoordeling heeft gemaakt.