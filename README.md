# Mediflow
Een scan- en projectiesysteem dat de medicatievoorbereiding vereenvoudigt door visueel aan te geven waar medicatie moet worden geplaatst, met bijkomende controle.

Projectteam: Finn Schrijvers, Jento Van Laethem 

Datum  17/01/2025

## Samenvatting

- Hero sketch/render/image)

  > [!NOTE]
> - Links naar volledige protocollen en reports zijn te vinden onder de [bijlagen](#bijlagen).
> - Ruwe data zoals foto's, video-opnames, _timetables_... zijn te vinden in de bijhorende protocollen en reports.
> - Volledige software, programma's en 3D-bestanden zijn te vinden in de map [files](/files).

Het probleem is dat medicatievoorbereiding in woonzorgcentra tijdrovend en foutgevoelig is, wat de werkdruk voor verpleegkundigen verhoogt en de kans op medicatiefouten vergroot. Om dit te onderzoeken, is er een gebruikersonderzoek uitgevoerd (interviews met zorgverleners en tests met primitieve prototypes). Dit leidde tot inzichten in de knelpunten van het huidige proces en gebruikersbehoeften.  

De oplossing is een systeem met een handscanner en plafondprojector. De handscanner leest medicijnzakjes en koppelt deze aan een digitale database met patiëntinformatie. De projector markeert visueel het juiste vakje in de medicatiekar waar het zakje moet worden geplaatst. Dit systeem logt automatisch welke medicatie is voorbereid en geeft directe feedback bij zowel een juiste als een foute plaatsing.  

Deze oplossing maakt de medicatievoorbereiding efficiënter door het proces eenvoudiger en gebruiksvriendelijker te maken, wat leidt tot tijdsbesparing en een vermindering van fouten. Het voorkomt dat verpleegkundigen handmatig informatie moeten controleren en zorgt voor een duidelijk, visueel gestuurde workflow. Het digitale logboek versterkt de controle en traceerbaarheid, wat bijdraagt aan een veilige medicatietoediening.

## Introductie

In woonzorgcentra (WZC) is medicatieverdeling een tijdrovende en foutgevoelige taak die direct bijdraagt aan de hoge werkdruk van verpleegkundigen. Onderzoek toont aan dat bijna **49% van de zorgverleners kampt met een hoge werkdruk**, mede veroorzaakt door personeelstekorten en de toenemende vergrijzing [^1] [Hoge werkdruk in rusthuizen | Beswic. (n.d.). https://beswic.be/nl/blog/hoge-werkdruk-rusthuizen]. In Vlaanderen voldoet bovendien **21% van de instellingen niet aan de wettelijke personeelsnormen**, wat de druk op bestaande medewerkers verder verhoogt. 

De voorbereiding van medicatie is een cruciaal maar tijdrovend onderdeel van het zorgproces in WZC. Elk pilletje komt in een individueel verpakt zakje binnen en moet handmatig verdeeld worden in de medicatiekar. Dit vereist het raadplegen van verschillende formulieren, visuele controle en het handmatig toevoegen van extra medicatie. Na deze stappen kan de verpleging met deze medicatiekar, op het juiste tijdsstip en bij de juiste persoon de medicatie toedienen. Dit proces is niet alleen arbeidsintensief, maar ook foutgevoelig, wat leidt tot onnodige vertragingen en frustratie bij het verplegend personeel. Het risico op fouten heeft bovendien grote gevolgen voor de veiligheid en het welzijn van de bewoners.

Het doel van dit project is het ontwikkelen van een verbetering die de efficiëntie en nauwkeurigheid van **medicatievoorbereiding** verbetert, zonder dat er een compleet nieuw systeem geïmplementeerd hoeft te worden. De oplossing moet betaalbaar, eenvoudig te integreren, en gebruiksvriendelijk zijn.  

  
## Methodologie

Als eerst werd de opdracht verkend: Wat is het doel van de opdracht? Is het gestelde probleem ook daadwerkelijk een probleem, en vooral, kan dit probleem gekoppeld worden aan bestaande oplossingen? Deze opdracht startte met het verkennen van de designchallange Werkbaar Werk in de Zorg met de bijhorende noden en behoeften.[Noden- en behoeftenanalyse van personeel in de zorg- en welzijnssectoren en maatwerkbedrijven. (z.j.). Ongepubliceerd document]

Tijdens de ontdekkingsfase onderzochten we hoe gebruikers, die dagelijks met het probleem te maken hebben, het probleem ervaren en welke oplossingen zij zelf voor ogen hebben. De user interviews bevestigden het probleem duidelijk. Uit benchmarking blijkt dat er al diverse oplossingen bestaan om de medicatievoorbereiding te vereenvoudigen. Echter, deze oplossingen hebben vaak belangrijke tekortkomingen, zoals hoge kosten, complexiteit of een gebrek aan gebruiksvriendelijkheid. Door deze zwakke punten te analyseren, konden we kansen identificeren om verbeteringen aan te brengen. Op basis van deze inzichten kan een eerste concept ontwikkeld worden dat zich binnen de oplossingsruimte bevindt.

In de definitiefase verdiepen we ons grondig in het probleem, volgens het principe "fall in love with the problem, not the solution." Tijdens deze fase worden de eerste prototypes ontwikkeld en testen we zo snel mogelijk of het concept levensvatbaar is voor verdere verfijning. Dit gebeurt in een vroege concepttest met verpleegkundigen in een WZC. De ontvangen feedback gebruiken we om het ontwerp aan te passen en verder te verbeteren.  

Deze iteratieve aanpak vormt de kern van ons ontwerpproces, waarbij we in volgende fasen steeds opnieuw testen met nieuwe of verfijnde prototypes. Tegelijkertijd bieden deze tests waardevolle inzichten in de gebruiker, waardoor we hun behoeften nog beter kunnen begrijpen en specificeren. Na elke test en elk onderzoek stellen we design requirements op die als leidraad dienen gedurende het hele proces.

De ontwerpmethodologie van dit proces is vastgelegd in onderstaande visuele tijdlijn.

![image](https://github.com/user-attachments/assets/5ac7e321-7b09-46eb-8382-fa2c81e23f1e)

---


## Discovery
Max. 1000 woorden
### Doestellingen
Wat wilde je bereiken?
### Materiaal & methoden
Hoe onderzocht je dit? Wees volledig.
### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
### Conclusies & implicaties
Definieer de belangrijkste designbeslissingen

## Definition
Max. 1000 woorden
### Doestellingen
Wat wilde je bereiken?
### Materiaal & methoden
Hoe onderzocht je dit? Wees volledig.
### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
### Conclusies & implicaties
Definieer de belangrijkste designbeslissingen

## Bill of materials
- Welk
- Materiaal
- Heb
- Je
- Nu
- Nodig
- Voor
- Je
- Prototype

## Kritische reflectie
Max. 500 woorden

## Bijlagen
- Discovery
  - Intervieuw
    - [protocol]
    - [report]
  - Benchmarking
    - [protocol]
    - [report]
- Definition
  - Testing
    - Wave 1
          - [protocol]
          - [report]
    - Wave 2
          - [protocol]
          - [report]
    - Wave 3
          - [protocol]
          - [report]
- Develop
    - to be continued...
    - 
## Bronnen
[^1]:
[^2]:
[^3]:
