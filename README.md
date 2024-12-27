# Mediflow
Een scan- en projectiesysteem dat de medicatievoorbereiding vereenvoudigt door visueel aan te geven waar medicatie moet worden geplaatst, met bijkomende controle.

Projectteam: Finn Schrijvers, Jento Van Laethem 

Datum  17/01/2025

## Samenvatting

- Hero sketch/render/image)

  > [!NOTE]
> - Links naar volledige protocollen en reports zijn te vinden onder de bijlagen (**klikbare link maken naar hoofdstukje bijlagen**).
> - Ruwe data zoals foto's, video-opnames, _timetables_... zijn te vinden in de bijhorende protocollen en reports.

Het probleem is dat medicatievoorbereiding in woonzorgcentra tijdrovend en foutgevoelig is, wat de werkdruk voor verpleegkundigen verhoogt en de kans op medicatiefouten vergroot. Om dit te onderzoeken, is er een gebruikersonderzoek uitgevoerd (interviews met zorgverleners en tests met primitieve prototypes). Dit leidde tot inzichten in de knelpunten van het huidige proces en gebruikersbehoeften.  

De oplossing is een systeem met een handscanner en plafondprojector. De handscanner leest medicijnzakjes en koppelt deze aan een digitale database met patiëntinformatie. De projector markeert visueel het juiste vakje in de medicatiekar waar het zakje moet worden geplaatst. Dit systeem logt automatisch welke medicatie is voorbereid en geeft directe feedback bij zowel een juiste als een foute plaatsing.  

Deze oplossing maakt de medicatievoorbereiding efficiënter door het proces eenvoudiger en gebruiksvriendelijker te maken, wat leidt tot tijdsbesparing en een vermindering van fouten. Het voorkomt dat verpleegkundigen handmatig informatie moeten controleren en zorgt voor een duidelijk, visueel gestuurde workflow. Het digitale logboek versterkt de controle en traceerbaarheid, wat bijdraagt aan een veilige medicatietoediening.

## Introductie

In woonzorgcentra (WZC) is medicatieverdeling een tijdrovende en foutgevoelige taak die direct bijdraagt aan de hoge werkdruk van verpleegkundigen. Onderzoek toont aan dat bijna **49% van de zorgverleners kampt met een hoge werkdruk**, mede veroorzaakt door personeelstekorten en de toenemende vergrijzing [^1]. In Vlaanderen voldoet bovendien **21% van de instellingen niet aan de wettelijke personeelsnormen**, wat de druk op bestaande medewerkers verder verhoogt. 

De voorbereiding van medicatie is een cruciaal maar tijdrovend onderdeel van het zorgproces in WZC. Elk pilletje komt in een individueel verpakt zakje binnen en moet handmatig verdeeld worden in de medicatiekar. Dit vereist het raadplegen van verschillende formulieren, visuele controle en het handmatig toevoegen van extra medicatie. Na deze stappen kan de verpleging met deze medicatiekar, op het juiste tijdsstip en bij de juiste persoon de medicatie toedienen. Dit proces is niet alleen arbeidsintensief, maar ook foutgevoelig, wat leidt tot onnodige vertragingen en frustratie bij het verplegend personeel. Het risico op fouten heeft bovendien grote gevolgen voor de veiligheid en het welzijn van de bewoners.

Het doel van dit project is het ontwikkelen van een verbetering die de efficiëntie en nauwkeurigheid van **medicatievoorbereiding** verbetert, zonder dat er een compleet nieuw systeem geïmplementeerd hoeft te worden. De oplossing moet betaalbaar, snel, eenvoudig te integreren, en gebruiksvriendelijk zijn. 
Randvoorwaarden:

- betaalbaar
- snel
- eenvoudig te integreren
- gebruiksvtiendelijk

  
## Methodologie

Als eerst werd de opdracht verkend: Wat is het doel van de opdracht? Is het gestelde probleem ook daadwerkelijk een probleem, en vooral, kan dit probleem gekoppeld worden aan bestaande oplossingen? Deze opdracht startte met het verkennen van de designchallange Werkbaar Werk in de Zorg met de bijhorende noden en behoeften. [^2]
Tijdens de ontdekkingsfase onderzochten we hoe gebruikers, die dagelijks met het probleem te maken hebben, het probleem ervaren en welke oplossingen zij zelf voor ogen hebben. De user interviews bevestigden het probleem duidelijk. Uit benchmarking blijkt dat er al diverse oplossingen bestaan om de medicatievoorbereiding te vereenvoudigen. Echter, deze oplossingen hebben vaak belangrijke tekortkomingen, zoals hoge kosten, complexiteit of een gebrek aan gebruiksvriendelijkheid. Door deze zwakke punten te analyseren, konden we kansen identificeren om verbeteringen aan te brengen. Op basis van deze inzichten kan een eerste concept ontwikkeld worden dat zich binnen de oplossingsruimte bevindt.

In de definitiefase verdiepen we ons grondig in het probleem, volgens het principe "fall in love with the problem, not the solution." Tijdens deze fase worden de eerste prototypes ontwikkeld en testen we zo snel mogelijk of het concept levensvatbaar is voor verdere verfijning. Dit gebeurt in een vroege concepttest met verpleegkundigen in een WZC. De ontvangen feedback gebruiken we om het ontwerp aan te passen en verder te verbeteren.  

Deze iteratieve aanpak vormt de kern van ons ontwerpproces, waarbij we in volgende fasen steeds opnieuw testen met nieuwe of verfijnde prototypes. Tegelijkertijd bieden deze tests waardevolle inzichten in de gebruiker, waardoor we hun behoeften nog beter kunnen begrijpen en specificeren. Na elke test en elk onderzoek stellen we design requirements op die als leidraad dienen gedurende het hele proces.

De ontwerpmethodologie van dit proces is vastgelegd in onderstaande visuele tijdlijn.

![image](https://github.com/user-attachments/assets/5ac7e321-7b09-46eb-8382-fa2c81e23f1e)

---


## Discovery (N totaal =13)
Tijdens de ontdekkingsfase richten we ons op het verkrijgen van een duidelijk inzicht in de probleemruimte en het identificeren van kansen. In het begin van deze fase wordt de probleemruimte bewust breed gehouden. Zo wordt het algemene proces van medicatieverdeling in WZC's grondig onderzocht, waarna we ons kunnen toespitsen op een specifiek aspect binnen dit proces.  

De kansen die we identificeren ontstaan uit zowel gebruikersinterviews als benchmarking. Met andere woorden, we brengen het probleem waarop we ons richten helder in kaart en onderzoeken het grondig om een sterke basis te leggen voor het verdere ontwerpproces.

### Doelstellingen
Een helder geformuleerde _"how might we"_ bekomen.

### Materiaal & methoden
- _contextual inquiries_
- gebruikersinterview
- benchmarking

### Gebruikersinterview (N=3)
Voordat er al gebrainstormed wordt over het maken van ontwerpen, wordt eerst de probleemruimte verder verfijnd door in contact te komen met verpleegkundigen binnen WZC. Deze personen staan dag dagelijks in de probleemruimte dus zij kunnen ons het best aangeven welk aspect binnen de medicatieverdeling het best meer aandacht verdient voor optimalisatie. Alvorens het uitvoeren van de intervieuws werd er een interview protocol werd opgesteld (zie bijlage). Dit protocol beschrijft het doel van het interview, zijnde wat we te weten willen komen van de gebruiker:

- Hoe werkt het huidige medicatieverdelingsproces?
- Welk proces neemt het meeste tijd in beslag?
- Welke handelingen lopen soms fout?
- Wat zijn de meest frustrerende taken en waarom?
- Wat zijn voor jou de belangrijkste vereisten bij het implementeren van nieuwe technologie binnen het medicatieverdelingsproces?
  
#### Resultaten
Alle interviews zijn van grote meerwaarde binnen dit onderzoek. Concreet zijn dit de belangrijkste antwoorden die verder geanalyseerd zullen worden voor in het vervolg van dit project:

> "De medicatie wordt besteld bij de apotheker, deze komt vaak de dag van bestelling nog binnen. Elk pilletje is afzonderlijk verpakt in een zakje, al deze zakjes zijn opgerold tot 1 medicijnrol (="baxter") ***voor alle patiënten tesamen***. Vervolgens moet alle medicatie worden voorbereid, dit omvat het handmatig verdelen van de zakjes in de juiste desbetreffende bakjes in de medicijnkar, hierbij moet ook alles gelogd worden in een digitaal document. Vaak is er ook extra medicatie die niet verpakt is in de zakjes (siroopp, poeder,...) voor deze medicatie is er wel een zakje voorzien met alle info op, maar zit er niets in. Hierbij wordt telkens het zakje in het bakje gelegd, samen met de nodige extra medicatie.

Vervolgens kan men op de nodige tijdsstippen van de dag met de kar naar de bewoner rijden om de medicatie toe te dienen. Hierbij wordt er een laatste check gedaan of het om de juiste medicatie gaat."
> 
> "Dit proces is een lange en soms frustrerende taak omdat er af en toe fouten gebeuren. Het is dan ook snel gebeurt dat je iets fout leest of vergeet aan te vinken."

> "Wat in mijn ogen cruciaal is, is het regelmatig contact bij het toedienen van de medicatie tussen bewoners en zorgverleners, wat (vaak onbewust) essentieel is voor het mentale welzijn van de bewoners. Tegelijkertijd biedt dit proces een moment om de toestand van de bewoners te controleren."



Een ander interessant aspect dat aangehaald werd was het veilig versturen van sms’en achter het stuur. Een alternatief op spraakbediening wanneer deze niet optimaal zou werken is het kiezen tussen vaste berichten die je via ons concept zou kunnen lezen op het HUD. Scrollen en selecteren gebeurt dan met de _dial_.

<p align="center">
  <img width="60%" src="/images/focus group.png">
  <img width="38%" src="/images/focus group tafel.jpg">
</p>

#### Benchmarking (N=10)
Om de markt te analyseren maken we gebruik van benchmarking, heel wat designkeuzes zijn vaak al succesvol opgelost door anderen. Je hoeft niet alles opnieuw te onderzoeken, maar door bestaande oplossingen aandachtig te bestuderen kunnen we focussen op meer belangrijke onbekende factoren.

Het probleem werd opgesplitst in twee fundamentele deelproblemen. Hoe kunnen we informatie weergeven en hoe kunnen we bepaalde functies bedienen? Voor beide werden de voor- en nadelen op een rijtje gezet. Daarna werd alles samengegoten in een overzichtelijke *problem-solution* matrix.

<p align="center">
  <img src="/images/benchmarking visualisation.jpg" width="49%"/>
  <img src="/images/benchmarking controls.jpg" width="49%"/>
</p>

<img src="/images/benchmarking problem solution matrix.jpg"/>

### Conclusies & implicaties
De afleiding tijdens het rijden wordt niet veroorzaakt door het touchscreen zelf, maar door het gebrek aan tactiele feedback bij het bedienen van het scherm. Je moet visueel verifiëren wat je gedaan hebt en of je het juist gedaan hebt. Verder genieten knoppen op het stuur en bediening via het touchscreen de voorkeur van gebruikers, gevolgd door fysieke knoppen en stembediening.

HUD's die in de voorruit of op de onderste zwarte band van de ruit geplaatst worden tonen informatie zonder dat de bestuurder zijn ogen van de baan hoeft te halen, wat de veiligheid bevordert. 3D-schermen en hologrammen bieden een goede ervaring en een grote aanpasbaarheid, maar zijn over het algemeen kostbaarder en complexer. Augmented reality-schermen combineren digitale informatie met de echte wereld, wat de navigatie- en veiligheidskenmerken verbetert. Traditionele schermen kunnen ondanks dat ze kosteneffectief en vertrouwd zijn de aandacht van de weg brengen. Fysieke knoppen en knoppen op het stuur geven prioriteit aan tastbare feedback en minimale afleiding, terwijl aanraakschermen en spraakbesturing veelzijdigheid bieden, maar mogelijk ten koste gaan van de veiligheid. Context, compatibiliteit en de leercurve zijn ook belangrijke factoren om in overweging te nemen.

**Hoe kunnen we een _dial_ en een HUD gebruiken om afgeleide bestuurders gefocust te houden op de weg, terwijl ze interageren met het dashboard?**

> [!IMPORTANT]
> Design Requirements:
> - D3.1 Het touchscreen laat toe de functies en hun bijhorende posities onderling te wijzigen.
> - D1.1 Het product laat toe functies te bedienen zonder dat de ogen van de baan afwijken.
> - D2.1 De _dial_ geeft haptische feedback bij het bedienen van de functies.
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
[^1]:[Hoge werkdruk in rusthuizen | Beswic. (n.d.). https://beswic.be/nl/blog/hoge-werkdruk-rusthuizen]
[^2]:[Noden- en behoeftenanalyse van personeel in de zorg- en welzijnssectoren en maatwerkbedrijven. (z.j.). Ongepubliceerd document]
[^3]:
