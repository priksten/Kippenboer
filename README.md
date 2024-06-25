# Kippenboer
Eenvoudig programma om de te verwachten winst te modelleren die een kippenboer kan behalen met zijn eierenproductie

# Omschrijving:
In dit project wordt een programma geschreven waarmee een kippenboer kan uitrekenen hoeveel omzet en winst hij maximaal kan verwachten met zijn eierenproductie. In dit programma worden de volgende aannames gemaakt:
-	De kippenboer heeft per week gemiddeld tussen de 2450 en 2525 kippen
-	Een kip legt gemiddeld 5 eieren per week
-	In een doosje passen 12 eieren
-	De verkoopprijs: €6 voor een doosje van 12 eieren, €1 voor een los ei
-	Statiegeld per doosje eieren: €1
-	Een medewerker kan per uur 1000 eieren verwerken
-	De medewerker verdient per uur €3,50
-	Per week krijgt de medewerker als bonus gratis 10 eieren mee

We ontwikkelen een programma dat op basis van een aantal variabelen de maximaal te verwachten omzet en winst kan berekenen. Deze variabelen zijn:
-	Aantal kippen dat in een bepaalde week eieren heeft gelegd
-	Aantal medewerkers die in een bepaalde week eieren verwerken
-	Het aantal uur dat deze medewerkers in totaal eieren verwerken

Het programma berekent dan automatisch hoeveel eieren er in totaal zijn gelegd en hoeveel daarvan ook daadwerkelijk verwerkt en verkocht kunnen worden. 
Verder biedt het programma ook de mogelijkheid om een kassabon te maken voor een klant die eieren bestelt. Op de bon is ook een QR-code zichtbaar.

# Programmeertaal + versie:
Python

# Gebruikte modules:
- datetime
- math
- qrcode

# Screenshots

![image](https://github.com/priksten/Kippenboer/assets/85739742/d23feef8-911b-4b54-9702-7c4e484b9b0c)
Het programma vraagt aan de gebruiker om de volgende gegevens in te vullen:
-	Een weeknummer (getal tussen 0 en 54)
-	Aantal kippen dat eieren legt (getal tussen 2450 en 2525)
-	Aantal medewerkers die in een week werken
-	Aantal uren dat de medewerkers samen eieren verwerken
De vragen verschijnen één voor één in het scherm. Bij de eerste twee gegevens, dus weeknummer en aantal kippen, wordt ook gecheckt of de gebruiker een getal heeft ingevoerd dat in het gewenste domein (dus resp (0,54) en (2450, 2525) ligt. Zolang dit niet het geval is, blijft het programma vragen om een getal in dit interval. Zodra dit getal is opgegeven gaat het programma door naar de volgende vraag. 

Nadat de gebruiker een antwoord op de vierde vraag heeft ingevoerd, verschijnt de output:
![image](https://github.com/priksten/Kippenboer/assets/85739742/0edd9d76-416c-4f48-9ad2-6b4f0aeb8784)
