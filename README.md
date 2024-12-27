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

(1) Hoe werkt het huidige medicatieverdelingsproces?
(2) Welk proces neemt het meeste tijd in beslag?
(3) Welke handelingen lopen hierbij soms fout?
(4) Wat zijn de meest frustrerende taken en waarom?
(5) Wat zijn voor jou de belangrijkste vereisten bij het implementeren van nieuwe technologie binnen het medicatieverdelingsproces?
  
#### Resultaten
Alle interviews zijn van grote meerwaarde binnen dit onderzoek. De belangrijkste antwoorden worden hieronder weergegeven, deze worden verder geanalyseerd zullen worden voor in het vervolg van dit project:

(1) > De medicatie wordt besteld bij de apotheek en vaak nog dezelfde dag geleverd. De medicatie arriveert in een medicijnrol (ook wel "baxter" genoemd), waarbij elk pilletje afzonderlijk is verpakt in een zakje. Deze rol bevat de medicatie voor alle patiënten samen, zoals weergegeven in de onderstaande afbeelding.  

Vervolgens begint de voorbereiding: de zakjes worden handmatig verdeeld over de juiste bakjes in de medicijnkar. Tijdens dit proces moet alles nauwkeurig worden gelogd in een digitaal systeem. Daarnaast is er vaak extra medicatie, zoals siropen of poeders, die niet in de zakjes is verpakt. Voor deze extra medicatie is er wel een zakje voorzien met alle benodigde informatie, maar zonder inhoud. Het lege zakje wordt samen met de extra medicatie in het juiste bakje geplaatst.  

Op de geplande tijdstippen wordt de medicijnkar naar de bewoners gereden om de medicatie toe te dienen. Tijdens de toediening wordt een laatste controle uitgevoerd met behulp van een tablet.

![image](https://github.com/user-attachments/assets/c7c58312-9b7a-4bdd-bf65-a3381dbf65bc)

(2) > "Het is voornamelijk het voorbereiden van de medicatie die vaak lang duurt."

(3) > "Soms beland het foute zakje in het bakje van de verkeerde persoon. Dit wordt wel altijd onderschept bij de laatste controle voor het toedienen van de medicatie."

(4) > "Vooral de voorbereiding van de medicatie is soms een frustrerende taak omdat het nogal lang duurt en omdat er af en toe fouten kunnen gebeuren"

(5) > "Wat in mijn ogen cruciaal is, is het regelmatig contact bij het toedienen van de medicatie tussen bewoners en zorgverleners, wat (vaak onbewust) essentieel is voor het mentale     welzijn van de bewoners. Tegelijkertijd biedt dit proces een moment om de toestand van de bewoners te controleren."

Samengevat leveren de interviews belangrijke inzichten op in het huidige proces van medicatieverdeling in WZC. Het grootste knelpunt ligt in de voorbereiding van de medicatie, die tijdrovend is en soms leidt tot fouten. Hoewel deze fouten meestal worden onderschept tijdens de laatste controle voor de toediening, blijft het proces van voorbereiding frustrerend en tijdsintensief voor de zorgverleners. Daarnaast wordt benadrukt dat het contact tussen zorgverleners en bewoners tijdens de medicatieronde van cruciaal belang is, niet alleen voor de juiste toediening van medicatie, maar ook voor het welzijn van de bewoners.

#### Benchmarking (N=10)
Om de markt te analyseren maken we gebruik van een benchmarking, hierbij stellen we ons de vraag welke bestaande oplossingen bijdragen aan de efficiëntie en nauwkeurigheid van medicatieverdelingsrondes in woonzorgcentra, en wat zijn de voor- en nadelen van deze oplossingen?

Elk object of systeem binnen deze benchmarking wordt geëvalueerd op basis van volgende specifieke criteria. De bijbehorende vragen dienen als een houvast om elke beoordelingscategorie te verduidelijken.

Efficiëntie
     - Hoe draagt het bij aan het verminderen van de werklast voor zorgverleners?
Nauwkeurigheid en Foutreductie
     - Hoe effectief is het systeem in het voorkomen van medicatiefouten?
     - Welke mechanismen zijn aanwezig om menselijke fouten te minimaliseren?
Gebruikerservaring
     - Is het systeem intuïtief en gemakkelijk te gebruiken voor zorgverleners?
     - Is er enige weerstand of zijn er knelpunten die de werkbaarheid beïnvloeden?
Kosten en Implementatie
     - Wat zijn de kosten van implementatie en onderhoud?
     - Hoe gemakkelijk is het systeem te integreren in bestaande workflows?
Betrouwbaarheid en Ondersteuning
     - Hoe betrouwbaar is het systeem in dagelijks gebruik?
     - Welke ondersteuningsmogelijkheden zijn beschikbaar voor gebruikers?

Omdat de interviews wijzen op de medicatievoorbereiding, werd er voornamelijk gezocht naar bronnen die een verband hebben met de medicijnkar, medicijnrol, en distributietechnologie (zoals een medicijndispencer voor de thuiszorg). De zaken die onderzocht zijn in de benchmarking zijn in onderstaande tabel verzameld.

|Object|Geraadpleegde bronnen|
|---:|:---:|
|Veel voorkomende medicijnkar|https://www.medline.be/en/Unit-Dose-Medication-Cart-for-20-Patients , https://www.lapastilla.com/en/medication-carts/|
|Slimme medicijnkar|https://www.omnicell.co.uk/automating-the-continuum-of-care/point-of-care/amis-pro-smart-cart-smart-medication-dispensing-cart/ , https://www.youtube.com/watch?v=XUXfOwwEEyw](https://www.omnicell.co.uk/automating-the-continuum-of-care/point-of-care/amis-pro-smart-cart-smart-medication-dispensing-cart/ , https://www.youtube.com/watch?v=XUXfOwwEEyw , https://en.nubomed.com/products/ICMMS/medication-management-cabinet/Medication-Management-Cabinet-M3000-M , https://www.alphatronmedical.com/medication-cart)
|Slimme medicijndispencer|https://www.zorgvannu.nl/innovaties/slimme-medicijndispensers , https://medido.com/nl|
|Medicatierol	|https://www.coopapotheken.be/pages/zorgcentra , https://www.whitecrosspharmacy.com/pages/MedPack-How-It-Works.cfm|

Vervolgens werden de geraadpleegde bronnen geanalyseerd en beoordeeld o.b.v. vooraf bepaalde criteria (zie hierboven) en in onderstaande tabel geplaatst:

| Categorie            | Basis Medicatiekar                                                                                     | Slimme Medicatiekar                                                                                             | Slimme Medicijndispensers                                                                      | Medicatierollen                                                                               |
|-----------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| **Wat**              | Eenvoudigere medicatiekarren, transporteren van medicijnen                                            | Slimme medicatiekarren met geautomatiseerde processen en foutreductiemechanismen                              | Slimme Medicijndispensers voor thuiszorg, voor gerichte medicatiedosering                     | Apothekers bieden medicatierollen met medicijnen op tijdsvolgorde, georganiseerd per patiënt. |
| **Pro’s**            | Gebruiksvriendelijk, betaalbaar, eenvoudig in onderhoud                                               | Geavanceerde foutreductie, tijdbesparing, veilige dispensering                                                | Betrouwbare dosering, geheugensteuntjes voor gebruikers                                       | Efficiënt en gestructureerd, zo goed als overal toegepast                                     |
| **Con’s**            | Beperkt in foutcontrole en geen automatisering                                                        | Hoge kosten, vereiste technische kennis, grote verandering in systeem                                         | Minder geschikt voor gebruik op schaal in groepszorg                                          | Extern systeem                                                                                |
| **Relevantie**       | Basis om een slim systeem op te plaatsen, en laagdrempelig te implementeren met extra technologie voor foutcontrole en gebruikersinterface | Inspiratie voor foutcontrole, en visualisatieschermen die informatie over bewoners en medicatie weergeven     | Kan als inspiratie dienen voor automatische dosering per bakje, eventueel gekoppeld aan een slim scherm dat medicatie-informatie toont | Dit is een globaal systeem dat zo goed als overal wordt toegepast                             |


Samengevat blijkt uit deze benchmark dat hoewel de huidige technologieën en systemen voor medicatiedistributie in woonzorgcentra diverse voordelen bieden, er nog steeds ruimte is voor verdere optimalisatie. De meeste standaard medicatiekarren, zoals beschreven, leveren stabiliteit en gemak voor het organiseren van medicatie per bewoner. Dit systeem is echter beperkt in geautomatiseerde functionaliteiten en vraagt nog steeds handmatige tussenkomst van zorgpersoneel om elke medicatie correct en tijdig te verdelen.
Slimme medicatiekarren en geautomatiseerde kasten bieden een stap vooruit door medicatiebeheer efficiënter en veiliger te maken, en dragen bij aan een betere foutreductie. Systemen zoals de geavanceerde medicatiekarren met displays en vergrendelmechanismen minimaliseren het risico op fouten en verhogen de controle, maar missen vaak integratie met bestaande werkstromen. 
Systemen geïntegreerd in de thuiszorg zoals de automatic pill dispencer ontbreken de mogelijkheid tot sociaal contact tussen bewoner en zorgpersoneel.
Uit de benchmark blijkt dat er waarde kan liggen in systemen die bestaande karren kunnen uitbreiden met geautomatiseerde componenten.


### Conclusie
Uit de benchmarking en interviews blijkt dat het medicatieverdeelproces in woonzorgcentra aanzienlijke uitdagingen kent, met name op het gebied van tijdsintensieve handelingen, frustraties, en fouten. Hoewel bestaande technologieën zoals medicatiekarren en medicatierollen stabiliteit en basisfunctionaliteit bieden, zijn er nog steeds gebrekken. Slimme medicatiekarren en automatische dispensers tonen potentieel voor verbeterde foutreductie en efficiëntie, maar missen vaak een naadloze integratie met bestaande systemen en workflows.

De interviews benadrukken dat vooral het handmatig klaarzetten van medicatie, inclusief het verwerken van extra medicatie, het meest tijdrovend en foutgevoelig is. Bovendien is het behoud van fysiek contact tussen zorgverleners en bewoners cruciaal, zowel voor het sociale welzijn als voor de controle bij medicatietoediening.

De grootste kans voor innovatie ligt in het ontwikkelen van systemen die het bestaande proces vereenvoudigen en ondersteunen.

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
