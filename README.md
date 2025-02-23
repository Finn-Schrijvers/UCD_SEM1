# Mediflow
Een scan- en projectiesysteem dat de medicatievoorbereiding vereenvoudigt door visueel aan te geven waar medicatie moet worden geplaatst, met bijkomende controle.

Projectteam: Finn Schrijvers, Jento Van Laethem

Datum  17/01/2025

## Samenvatting

<div align="center">
  <img src="https://github.com/user-attachments/assets/ef4ac21a-f390-4071-8f2d-7a8a31f30769" width="50%">
</div>


  > [!NOTE]
> - Links naar volledige protocollen en reports zijn te vinden onder de [bijlagen](#bijlagen)
> - Ruwe data is te vinden in de bijhorende protocollen en reports.

Het probleem is dat medicatievoorbereiding in woonzorgcentra tijdrovend en foutgevoelig is, wat de werkdruk voor verpleegkundigen verhoogt en de kans op medicatiefouten vergroot. Om dit te onderzoeken, is er een gebruikersonderzoek uitgevoerd (interviews met zorgverleners en tests met primitieve prototypes). Dit leidde tot inzichten in de knelpunten van het huidige proces en gebruikersbehoeften.  

De oplossing is een systeem met een handscanner en plafondprojector. De handscanner leest medicijnzakjes en koppelt deze aan een digitale database met patiëntinformatie. De projector markeert visueel het juiste vakje in de medicatiekar waar het zakje moet worden geplaatst. Dit systeem logt automatisch welke medicatie is voorbereid en geeft directe feedback bij zowel een juiste als een foute plaatsing.  

Deze oplossing maakt de medicatievoorbereiding efficiënter door het proces eenvoudiger en gebruiksvriendelijker te maken, wat leidt tot tijdsbesparing en een vermindering van fouten. Het voorkomt dat verpleegkundigen handmatig informatie moeten controleren en zorgt voor een duidelijk, visueel gestuurde workflow. Het digitale logboek versterkt de controle en traceerbaarheid, wat bijdraagt aan een veilige medicatietoediening.

## Introductie

In woonzorgcentra (WZC) is medicatieverdeling een tijdrovende en foutgevoelige taak die direct bijdraagt aan de hoge werkdruk van verpleegkundigen. Onderzoek toont aan dat bijna **49% van de zorgverleners kampt met een hoge werkdruk**, mede veroorzaakt door personeelstekorten en de toenemende vergrijzing [^1]. In Vlaanderen voldoet bovendien **21% van de instellingen niet aan de wettelijke personeelsnormen**, wat de druk op bestaande medewerkers verder verhoogt. 

De voorbereiding van medicatie is een cruciaal maar tijdrovend onderdeel van het zorgproces in WZC. Elk pilletje komt in een individueel verpakt zakje binnen en moet handmatig verdeeld worden in de medicatiekar. Dit vereist het raadplegen van verschillende formulieren, visuele controle en het handmatig toevoegen van extra medicatie. Na deze stappen kan de verpleging met deze medicatiekar, op het juiste tijdsstip en bij de juiste persoon de medicatie toedienen. Dit proces is niet alleen arbeidsintensief, maar ook foutgevoelig, wat leidt tot onnodige vertragingen en frustratie bij het verplegend personeel. Het risico op fouten heeft bovendien grote gevolgen voor de veiligheid en het welzijn van de bewoners.

Het doel van dit project is het ontwikkelen van een verbetering die de efficiëntie en nauwkeurigheid van **medicatievoorbereiding** verbetert, zonder dat er een compleet nieuw systeem geïmplementeerd hoeft te worden. De oplossing moet betaalbaar, snel, eenvoudig te integreren, en gebruiksvriendelijk zijn. 
Randvoorwaarden:

- Betaalbaar
- Snel
- Eenvoudig te integreren
- Gebruiksvriendelijk

  
## Methodologie

Als eerst werd de opdracht verkend: Wat is het doel van de opdracht? Is het gestelde probleem ook daadwerkelijk een probleem, en vooral, kan dit probleem gekoppeld worden aan bestaande oplossingen? Deze opdracht startte met het verkennen van de designchallenge Werkbaar Werk in de Zorg met de bijhorende noden en behoeften. [^2]
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
De probleemruimte wordt verfijnd door contact te hebben met verpleegkundigen binnen WZC. Zij kunnen het beste aangeven welk aspect van de medicatieverdeling aandacht verdient voor optimalisatie. Voorafgaand aan de interviews werd een interviewprotocol opgesteld (zie bijlage). Dit beschrijft het doel van het interview en wat we willen weten van de gebruiker.

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

<div align="center">
  <img src="https://github.com/user-attachments/assets/c7c58312-9b7a-4bdd-bf65-a3381dbf65bc" width="50%">
</div>


(2) > "Het is voornamelijk het voorbereiden van de medicatie die vaak lang duurt."

(3) > "Soms beland het foute zakje in het bakje van de verkeerde persoon. Dit wordt wel altijd onderschept bij de laatste controle voor het toedienen van de medicatie."

(4) > "Vooral de voorbereiding van de medicatie is soms een frustrerende taak omdat het nogal lang duurt en omdat er af en toe fouten kunnen gebeuren"

(5) > "Wat in mijn ogen cruciaal is, is het regelmatig contact bij het toedienen van de medicatie tussen bewoners en zorgverleners, wat (vaak onbewust) essentieel is voor het mentale     welzijn van de bewoners. Tegelijkertijd biedt dit proces een moment om de toestand van de bewoners te controleren."

De interviews geven inzicht in het medicatieverdelingsproces in WZC. De grootste uitdaging ligt bij de medicatievoorbereiding die tijdrovende en foutgevoelig is. Hoewel fouten meestal tijdens de eindcontrole worden opgemerkt, blijft het proces frustrerend voor zorgverleners. Ook is het contact tussen zorgverleners en bewoners tijdens de medicatieronde cruciaal voor de juiste toediening en het welzijn van de bewoners.

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

### Conclusie
Uit de benchmarking en interviews blijkt dat het medicatieverdeelproces in woonzorgcentra aanzienlijke uitdagingen kent, zoals tijdsintensieve handelingen, frustraties en fouten. Bestaande technologieën zoals medicatiekarren bieden stabiliteit, maar missen automatisering. Slimme medicatiekarren en automatische dispensers verbeteren foutreductie en efficiëntie, maar integreren vaak niet goed met bestaande systemen en workflows.

Interviews benadrukken dat handmatige medicatievoorbereiding het meest tijdrovend en foutgevoelig is. Fysiek contact tussen zorgverleners en bewoners is cruciaal voor sociaal welzijn en controle bij medicatietoediening. Vanwege de hoge werkdruk en wisselende personen die de medicatie voorbereiden, is een gebruiksvriendelijk en toegankelijk systeem essentieel.

> [!IMPORTANT]
> Design Requirements:
> - Inspelen op medicatievoorbereiding 
> - Tijdbesparend
> - Integratie in bestaande workflow
> - Mag contact tussen verpleegkundige en bewoner niet verstoren
> - Moet toegankelijk zijn voor verschillende mensen

## Definition (N=3)
In de definitiefase bepalen we de oplossingen die we dit jaar zullen uitwerken. We onderzoeken mogelijke oplossingen op basis van het eerder gedefinieerde probleem, om een weloverwogen conceptkeuze te maken. Dit concept vormt de basis voor verdere ontwikkeling in het tweede semester. Deze definition fase zal opgedeeld worden in 3 waves waarbij het de bedoeling is om het concept bij elke wave telkens meer te kunnen verfijnen.

### Doelstellingen
Tot een conceptueel ontwerp komen m.b.v.  _quick-and-dirty_ prototypes

### Materiaal & methoden_
- kartonnen prototypes
- digitaal ontworpen interfaces
- gebruikerstesten

### Wave 1
In de eerste wave is het de bedoeling om te achterhalen of de conceptuele werking die we in ons hoofd hebben, een goede werking is. Als eerst hebben we de omgeving nagemaakt om d.m.v. roleplay beter inzicht te krijgen in het voorbereiden van de medicatie. De opstelling zoals hieronder te zien representeert een medicijnkar met de bakjes waarin de medicatie moet komen (op deze kar ligt het eerste prototype, dit mag je negeren).

<div align="center">
  <img src="https://github.com/user-attachments/assets/b2ecc2be-5ea1-41b3-ac69-c5f7cc917d90" width="50%">
</div>


#### Prototype
Na brainstormen is het concept voor het eerste prototype vastgelegd. Zoals hieronder te zien, beschrijft prototype 1 een dockingsysteem waarbij de medicatiekar gedeeltelijk wordt ingereden. In dit dock bevindt zich een dispenser waarin een medicijnrol geplaatst kan worden.

  ![image](https://github.com/user-attachments/assets/0438129f-f481-40b4-afd8-0186e96bd285) ![image](https://github.com/user-attachments/assets/e7150856-0355-4097-954b-3c07215c2f35)

De dispenser leest automatisch de gegevens op de medicatiezakjes, controleert de inhoud en plaatst ze in de juiste bakjes van de medicatiekar. Deze dispencer unitis meer gedetailleerd weergegeven op onderstaande afbeelding. De dispencer zal tot de juiste bakjes geraken d.m.v. coreXY bewegingen, die het in staat stelt om de zakjes in de juiste compartimenten te plaatsen.

   ![image](https://github.com/user-attachments/assets/d621e00f-b8bd-4fd4-ab80-113c9b5ae8fa) ![image](https://github.com/user-attachments/assets/3dd0fd7a-a330-4dc6-b660-fa45c71c2f4d)

Zoals vergroot weergegeven op onderstaande afbeelding, is de machine voorzien van een bedieningspaneel waarop verschillende statussen en knoppen geraadpleegd en bediend kunnen worden.

 ![image](https://github.com/user-attachments/assets/28cecc1b-dd88-44eb-bbcd-22678e4bfa52) ![image](https://github.com/user-attachments/assets/b0dfa3bd-de1d-45ca-b9b6-4aaa1f276b2c)

Om het prototype te ondersteunen met de handelingen is er eenvoudige interface voorzien. Dit interface zal toelichten welke handelingen ondernomen dienen te worden of informatie te verkrijgen tijdens het proces. Hoe deze interface er uit ziet, zie je op onderstaande afbeelding, de volledige interface is terug te vinden in bijlagen.

![image](https://github.com/user-attachments/assets/151c33c7-568b-4ac0-a7d3-86103347ae89)

#### Resultaten
Uit de eerste test blijkt dat het huidige prototype in zijn huidige vorm niet implementeerbaar is. Dit komt door meerdere factoren:  

1. **Variatie in medicatierollen**: Medicatierollen komen in WZC's op verschillende manieren binnen (per patiënt of één rol voor een groep). De oplossing moet al deze variaties ondersteunen.  
2. **Grootte en complexiteit**: Het prototype is te groot en complex, zowel qua functionaliteit als gebruiksvriendelijkheid voor verpleegkundigen. Een eenvoudiger, niet-machine-achtig ontwerp zou beter passen.  

Er is een pivot nodig naar een ander concept om medicatievoorbereiding te optimaliseren. Dit nieuwe concept moet rekening houden met de verwerking van meerdere medicatierollen per sessie, en de technische en gebruiksvriendelijke aspecten van de oplossing.  

> [!IMPORTANT]
> Design Requirements:
> - Ontwerp moet beperkt zijn in grootte
> - Bruikbaar in WZC die verschillende werking hebben omtrent de medicijnrol
> - Ontwerp moet beperkt zijn in complexiteit


### Wave 2
Na de grote pivot in wave 1 is het in deze fase belangrijk om eerst te verifiëren of het nieuwe concept bruikbaar is. We zijn tot een nieuw concept gekomen door te brainstormen, rekening houdend met de randvoorwaarden voortvloeiend uit wave 1.

#### Prototype
Het tweede prototype bestaat uit een scanner en een projector. De scanner heeft 2 verschillende variaties, rechts en in het midden te zien op onderstaande afbeelding en de projector is links op de figuur te zien.
 
<div align="center">
  <img src="https://github.com/user-attachments/assets/5f389de4-d7ed-4317-bb0e-7e394cee2486">
</div>

##### Scanner
Voor deze test is een traditionele supermarkt-scanner in klei nagemaakt (rechts in bovenstaande figuur) om medicatiezakjes te scannen.
In het midden van bovenstaande figuur staat een kleimodel van een borstscanner, bedoeld om handsfree scannen mogelijk te maken. Zoals getoond in onderstaande figuur, wordt deze scanner op de borst van de verpleegkundige bevestigd.
De borstscanner is gevuld om het gewicht en gebruik realistischer te maken. Hierdoor kan getest worden of de scanner bijvoorbeeld niet losraakt of hinderlijk is tijdens bewegingen.
 
<div align="center">
  <img src="https://github.com/user-attachments/assets/9d90fea1-d8ca-4b1c-b9a3-30006b2b6354" width="50%">
</div>


##### Projector
Links op de eerste afbeelding stelt het prototype een projector voor, waarbij na het scannen mee op de medicijnkar geprojecteerd zal worden om de plaats van het gescande zakje aan te geven.
Het is de bedoeling dat deze tegen de muur gemonteerd wordt om horizontaal op de schuiven van de kar te kunnen projecteren. Het prototype is voorzien van een lampje en een knop om het lampje aan te zetten om de interactie meer realistisch te maken.

#### Resultaten
Uit deze tweede test valt er te concluderen dat het prototype van de handscanner en projector wel implementeerbaar is mits enkele aanpassingen. De draagbare borstscanner werd meteen uitgesloten omdat het niet toegelaten is binnen WZC om dergelijke zaken op de kledij te dragen.

Een tweede projector, gemonteerd aan het plafond, zou zowel het bakje als het compartiment binnen dit bakje voor de toedientijdstippen kunnen aanduiden. Dit vergroot de toepasbaarheid van het concept, vooral bij medicijnkarren met schuiven waarbij de bakjes pas zichtbaar worden na het openen van een lade.
Daarnaast kan projectie in twee verschillende kleuren (groen en rood) dienen als feedbacksysteem: groen voor correct geplaatste zakjes en rood voor fout geplaatste zakjes. Om dit mogelijk te maken, moet het systeem herkennen in welk compartiment het zakje is geplaatst. Dit kan worden gerealiseerd door een geïntegreerde, getrainde camera in de projectoren.

> [!IMPORTANT]
> Design Requirements:
> - Moet capabel zijn om het compartiment voor toedieningstijdsstip van het medicatiebakje aan te duiden
> - Er moet een vorm van feedback zijn -> zakje juist geplaatst ja of nee?


### Wave 3
Uit wave 2 is er nood aan controle en feedback na het verdelen van de medicatie tijdens elke stap de foutgevoeligheid van de mens te verlagen. Bij het toedienen van de medicatie wordt er veranderstelt dat de voorgaande controles correct zijn voor gebruik. Echter kan er nadien nog altijd menselijke fouten gemaakt worden.

#### Prototype
Het derde prototype bestaat uit een methode om bewoners met de juiste medicatie te verbinden.

##### Scanner
Bij het testen van onderstaande methoden, werd een scanner voorzien die, volgens feedback uit wave 2, kan worden neergezet in een dock. Dit zie je in Figuur 4 en 5. Deze dock is gelijkaardig aan ontwerpen van elektrische aparaten. De scanner is in deze test zorgt voor een realistische weergave en ondersteuning voor de andere prototypes. 

<div align="center">
  <img src="https://github.com/user-attachments/assets/dfb1c586-b43f-452a-9c4a-4a4f38591cf0" width="50%">
</div>

##### Armband
Om de juiste bewoner te kunnen koppelen met de medicatie die op dat moment van toepassing is er een armband dat gebaseerd is op een huidige systeem van een ziekhuis.[^3] Hierbij wordt de persoon intern gekoppeld aan een kamernummer waarbij het systeem weet wie de inwoner is. 

<div align="center">
  <img src="https://github.com/user-attachments/assets/fceeee21-b496-46d7-9991-3f07e4f90693" width="50%">
</div>


##### Paper prototype met barcodes
Een papieren versie van de lay-out van de eetzaal gecombineerd met stickers in de kamers vormt, zoals bij de armband, een connectie tussen de bewoner en de juiste medicatie. Het prototype wordt meegenomen met de kar die samen met de scanner en een tablet verbonden via de cloud één geheeld vormt.

<div align="center">
  <img src="https://github.com/user-attachments/assets/b98ee84f-3bc1-45f5-bee8-953ce49d0985" width="50%">
</div>


#### Resultaten
Uit deze derde test valt er te concluderen dat naast het verdelen ook de controle mogelijk is via een handscanner dat samen werkt met een slimme camera en een programma mits de nodige aanpassingen. Het dragen van een armband is niet in conform met de richtlijnen van WZC Van Lierde en mogelijk andere woonzorgcentra. Hierdoor is het prototype met de armband uitgesloten.

![image](https://github.com/user-attachments/assets/862984b9-2ed9-4f5a-a57a-d566d354627a) ![image](https://github.com/user-attachments/assets/9621035c-9284-4976-98f2-4ecc7ec70d73)

Bij het controleren van de medicatie zijn er 2 verschillen ofwel 2 fasen. Tijdens de eerste fase heb je in de nacht de hoofdverpleger die 1 maal controleert en tijdens de dag een andere hoofdverpleger die nogmaals controleert via een programma op de computer. Hier blijft de medicatie op één plek. In fase 2 gaat de hoofdverpleger of zorgkundige de medicatie controleren via een tablet. Hierdoor is er nood aan feedback op de scanner die de huidige status toont.

> [!IMPORTANT]
> Design Requirements:
> - De scanner bezit een feedbackmethode om in verschillende stappen aan te duiden welke status de scan betreft. (goed, fout, handmatig, ...)
> - Het concept moet kunnen omgaan met bewoners die speciale medicatie nemen die niet worden meegegeven in zakjes.
> - De bewoners mogen, door regelgeving, geen draagbare identificatie bezitten. 

### Conclusies & implicaties
Het oorspronkelijke prototype uit test 1 is niet geschikt voor implementatie in zijn huidige vorm, vooral vanwege de complexiteit, omvang en het gebrek aan flexibiliteit om verschillende werkmethoden binnen WZC te ondersteunen. Dit heeft geleid tot de noodzaak voor een pivot naar een eenvoudiger en beter afgestemd concept.  

De inzichten uit test 2 tonen aan dat implementatie haalbaar is, mits enkele aanpassingen worden doorgevoerd. Een tweede projector, gemonteerd aan het plafond, kan zowel bakjes als compartimenten voor toedientijdstippen aanduiden, wat het concept flexibeler maakt. Daarnaast kan een feedbacksysteem met kleurprojectie (groen/rood) de gebruikservaring verder verbeteren, mits het systeem wordt uitgerust met een geïntegreerde camera om de plaatsing van de zakjes te controleren. Dit is iets dat getest kon worden in een 3de wave.

Wave 3 valt buiten de scope van dit project vanwege gebrekkige samenwerking en communicatie. Het project richt zich specifiek op medicatievoorbereiding, terwijl wave 3 zich bezighoudt met de effectieve toediening van medicatie. Bovendien staat wave 3 haaks op de gebruikersbehoeften die tijdens de discoveryfase van dit project zijn vastgesteld. Zo hebben verpleegkundigen aangegeven dat het behoud van menselijke controle essentieel is, iets waar prototype 3 niet aan voldoet.

Daarom wordt de focus voortgezet op prototype 2.


## Bill of materials
<div align="center">
  <img src="https://github.com/user-attachments/assets/ef4ac21a-f390-4071-8f2d-7a8a31f30769" width="50%">
</div>
<div align="center">
  <img src="https://github.com/user-attachments/assets/362ca6ff-acfa-471c-ab5a-c2fea9634293" height="300px">
  <img src="https://github.com/user-attachments/assets/440e40a9-345b-4afd-aedd-e05e3b5558f3" height="300px">
</div>

Volgende componenten zijn volgens het concept voldoende om 1 scanner en 1 projector te maken. Opmerkelijk hierbij is dat er wel 2 projectors nodig zijn. Dit is bewust gedaan om de kost van het prototype zo laag mogelijk te houden.

- Raspberry Pi
- Raspberry pi camera
- Drukknop
- Dualmode drukknop
- Lasers (rood en groen)
- Arduino
- Servomotoren 2 stuks
- Basiscomponenten zoals bekabeling, batterijen, 3D-geprinte onderdelen,...

## Kritische reflectie

Het **Mediflow-project** heeft waardevolle inzichten opgeleverd in de uitdagingen rondom medicatievoorbereiding in woonzorgcentra en biedt een innovatieve oplossing om deze processen te optimaliseren. Desondanks zijn er enkele leerpunten die tijdens het proces naar voren kwamen en die van belang zijn voor toekomstige iteraties en projecten.

### Sterke punten
#### Gebruikersgerichte aanpak
Bij de test van het eerste prototype bleek het van groot belang om te focussen op gebruiksgericht ontwerpen. Een complexe machine kan wel worden ontworpen, maar als de eindgebruiker er niet mee kan of wil werken, is het onbruikbaar.

Door middel van interviews en gebruikerstesten is er een duidelijk beeld verkregen van de behoeften en frustraties van zorgverleners. Deze inzichten hebben ervoor gezorgd dat de oplossing goed aansluit bij de praktijk.

#### Iteratieve methodologie
Het proces was sterk iteratief, waarbij prototypes snel werden ontwikkeld, getest en aangepast, al dan niet met een conceptpivot. Dit heeft geleid tot een ontwerp dat steeds beter aansluit bij de werkelijke behoeften van de gebruikers.

#### Focus op haalbaarheid bij implementatie
De oplossing houdt rekening met integratie in bestaande workflows, wat de implementatie haalbaar en laagdrempelig maakt.


### Zwakke punten
#### Beperkte diversiteit in gebruikersinterviews
Hoewel de interviews waardevolle informatie opleverden, was de steekproefgrootte beperkt (N=3). Een bredere groep respondenten had mogelijk meer diverse inzichten opgeleverd, bijvoorbeeld over variaties in workflows tussen verschillende woonzorgcentra.

#### Technische haalbaarheid
Hoewel het concept technisch interessant is, zijn er nog vragen over de haalbaarheid en betrouwbaarheid van het projectiesysteem in een drukke en soms chaotische zorgomgeving. Het risico van storingen of technische complicaties kan een belemmering vormen voor adoptie.

#### Kostenanalyse
Hoewel betaalbaarheid een randvoorwaarde is, is er nog geen uitgebreide kostenanalyse uitgevoerd. Dit is cruciaal om te bepalen of de oplossing financieel haalbaar is voor de meeste woonzorgcentra, die vaak met beperkte budgetten werken.

### Leerpunten

#### Slechte samenwerking
Ondanks dat de technische en gebruikersgerichte aspecten zo goed mogelijk zijn uit gewerkt, had dit project veel verder kunnen geraken als er een betere samenwerking zou geweest zijn. Zo werden er afspraken niet nagekomen en zaken vaak niet, of van onvoldoende kwaliteit uitgevoerd door één van de teamgenoten. Een vereenvoudigde takenverdeling is terug te vinden in [bijlagen](#bijlagen).

### Conclusie

Het Mediflow-project is een waardevolle stap richting efficiëntere en veiligere medicatievoorbereiding in woonzorgcentra. Het project heeft sterke punten in zijn gebruikersgerichte en iteratieve aanpak, maar vraagt nog om verdieping op het gebied van technische haalbaarheid, kosten en langetermijnimplementatie. De opgedane inzichten bieden een solide basis voor verdere ontwikkeling en verfijning van het concept.


## Bijlagen
- Takenverdeling: https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/Takenverdeling.docx?d=w5ec6dbe67c1f4606989a8b7d1c42f43c&csf=1&web=1&e=vEw5g2
- Discovery
  - Interview
    - Protocol:https://ugentbe-my.sharepoint.com/:b:/g/personal/finn_schrijvers_ugent_be/EcoTthYsxGFJtN3jjUL699IBEEbDjl1ifWImxwv9pCJupw?e=jNeKJb
    - Report: [https://ugentbe-my.sharepoint.com/:b:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/Discovery/Interview%20verslag.pdf?csf=1&web=1&e=BVS1c4](https://ugentbe-my.sharepoint.com/:b:/g/personal/finn_schrijvers_ugent_be/EYRURUgyOh1CmjkWjf7noQgBPfOw-SUfmo8IBAGYPrBS1Q?e=0BX6WX)
  - Benchmarking
    - Protocol:https://ugentbe-my.sharepoint.com/:b:/g/personal/finn_schrijvers_ugent_be/ESbbRborLb9OpKoyfDy2d1oB8pUYO5MkBOqB7pg_99yR1w?e=DWbjez
    - Report:https://ugentbe-my.sharepoint.com/:b:/g/personal/finn_schrijvers_ugent_be/EeoSfp9atvNIgY3D2ixI-50B0GlwUGT-gPK8U4ewq5R8Mw?e=7Bx0sK
- Definition
  - Testing
    - Wave 1
      - Protocol:  https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/WAVE%201/Testing%20protocol%20WAVE1.docx?d=w3b7c8de31d3f4563b06cfd0af58341d2&csf=1&web=1&e=V1jw9a
      - Report:    https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/WAVE%201/Testing%20report%20WAVE%201.docx?d=wc74c40cac1e54a6c8793ce94ca2871f9&csf=1&web=1&e=nZ065x
    - Wave 2
      - Protocol:  https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/WAVE%202/Testing%20protocol%20WAVE%202.docx?d=w26fee3c348404a939a03e8cec04b7c21&csf=1&web=1&e=n667sP
      - Report:    https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/WAVE%202/Testing%20report%20WAVE%202.docx?d=w04bddf93de244da8b173f20e97f99bb6&csf=1&web=1&e=ZRHxpe
    - Wave 3
      - Protocol:  https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/WAVE%203/Testing%20protocol%20WAVE%203.docx?d=w002937f2e4d64486a5eca4ded653fda4&csf=1&web=1&e=N9RhcN
      - Report:    https://ugentbe-my.sharepoint.com/:w:/r/personal/finn_schrijvers_ugent_be/Documents/Gebruiksgericht/WAVE%203/Testing%20report%20WAVE%203.docx?d=w3af82529caed4f46b8211b06139907d2&csf=1&web=1&e=hsep6W
- Develop
    - to be continued...
    - 
## Bronnen
[^1]:[Hoge werkdruk in rusthuizen | Beswic. (n.d.). https://beswic.be/nl/blog/hoge-werkdruk-rusthuizen]
[^2]:[Noden- en behoeftenanalyse van personeel in de zorg- en welzijnssectoren en maatwerkbedrijven. (z.j.). Ongepubliceerd document]
[^3]:[UZ Leuven. (z.d.). Identificatiebandje. Geraadpleegd op 10 januari 2025 van https://www.uzleuven.be/nl/raadpleging-en-opname/kwaliteit-en-veiligheid/patientenidentificatie/identificatiebandje]
