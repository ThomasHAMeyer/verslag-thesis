==========================
Noodzakelijke aanpassingen
==========================
In het prototype zijn nog enkele aanpassingen nodig vooraleer het in de praktijk getest kan worden.
Deze aanpassingen worden hieronder kort uiteengezet.

Policies
========
In het prototype wordt er niet nagekeken of een gebruiker de nieuwe methodes mag gebruiken.
Sommige links zijn verborgen voor gewone gebruikers, maar voorlopig wordt er nog niet nagekeken of een gebruiker wel of niet toegang heeft tot een bepaald webpagina.
Dit is op te lossen met Policy-objecten in Ruby on Rails en moet dus nog gedaan worden.

Opmaak consistent maken
=======================
Op sommige plaatsen worden er knoppen met verschillende opmaak gebruikt.
Dit moet aangepast worden voor een verzorgde indruk te scheppen.
De oorzaak hiervan is het gebruik van 'form' uit Ruby on Rails.
Dit wordt gebruikt om gemakkelijk formulieren te maken om nieuwe objecten aan te maken, maar genereert lelijke knoppen zonder opmaak.