=============
Ruby on Rails
=============

Dodona wordt ontwikkeld met Ruby on Rails, een web framework dat het model-view-controller patroon volgt.
Het model-view-controller patroon is een design patroon waarbij er drie soorten klassen zijn.
De modellen die de objecten die persistent opgeslagen worden in een databank voorstellen.
Deze bevatten de meeste logica.
De controllers zijn de klassen die externe requests, zowel inkomende als uitgaande, verwerken.
Deze horen alleen de logica te bevatten om de verzoeken te kunnen verwerken, deze klassen roepen de methodes uit de modellen op voor hun werking.
De views zijn de bestanden die verwerkt worden en die dan doorgestuurd worden.
Dit zijn meestal html bestanden die door de browser van de gebruiker verwerkt worden naar een webpagina.

Ruby on Rails vergemakkelijkt het model-view-controller patroon door het linken van de verschillende klassen automatisch te doen.
Hiertoe moeten enkele conventies omtrent gebruikte namen gerespecteerd worden.
Zo wordt het meervoud van de naam van een klasse herkend en automatisch gebruikt.

Bij de ontwikkeling hebben we zoveel mogelijk de conventie dat we zoveel mogelijk logica in de models te plaatsen om de controllers simpel te houden gevolgd.
Ook is er moeite gedaan om code repetitie zoveel mogelijk te vermijden door waar mogelijk reeds geschreven code te hergebruiken.