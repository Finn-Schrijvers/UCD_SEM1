# Mediflow
Een scan- en projectiesysteem dat de medicatievoorbereiding vereenvoudigt door visueel aan te geven waar medicatie moet worden geplaatst, met bijkomende controle.

*Projectteam: Finn Schrijvers, Jento Van Laethem 

Datum  17/01/2025

## Samenvatting
(Max 200 woorden. Beschrijf je project in het kort, waarbij je deze vragen zeker beantwoordt:

- Wat is het probleem?
- Hoe heb je dit onderzocht?
- Wat is jouw oplossing?
- Hoe lost jouw oplossing het probleem op?
- Hero sketch/render/image)

Het probleem is dat medicatievoorbereiding in woonzorgcentra tijdrovend en foutgevoelig is, wat de werkdruk voor verpleegkundigen verhoogt en de kans op medicatiefouten vergroot. Om dit te onderzoeken, is er een gebruikersonderzoek uitgevoerd (interviews met zorgverleners en tests met primitieve prototypes). Dit leidde tot inzichten in de knelpunten van het huidige proces en gebruikersbehoeften.  

De oplossing is een systeem met een handscanner en plafondprojector. De handscanner leest medicijnzakjes en koppelt deze aan een digitale database met patiëntinformatie. De projector markeert visueel het juiste vakje in de medicatiekar waar het zakje moet worden geplaatst. Dit systeem logt automatisch welke medicatie is voorbereid en geeft directe feedback bij zowel een juiste als een foute plaatsing.  

Deze oplossing maakt de medicatievoorbereiding efficiënter door het proces eenvoudiger en gebruiksvriendelijker te maken, wat leidt tot tijdsbesparing en een vermindering van fouten. Het voorkomt dat verpleegkundigen handmatig informatie moeten controleren en zorgt voor een duidelijk, visueel gestuurde workflow. Het digitale logboek versterkt de controle en traceerbaarheid, wat bijdraagt aan een veilige medicatietoediening.

## Introductie
(Max 300 woorden. Kader je project. Introduceer het probleem en jouw doelstellingen (inclusief boundary conditions). Maak gebruik van bronverwijzingen (zie APA stijl).)

In woonzorgcentra (WZC) is medicatieverdeling een tijdrovende en foutgevoelige taak die direct bijdraagt aan de hoge werkdruk van verpleegkundigen. Onderzoek toont aan dat bijna **49% van de zorgverleners kampt met een hoge werkdruk**, mede veroorzaakt door personeelstekorten en de toenemende vergrijzing [Hoge werkdruk in rusthuizen | Beswic. (n.d.). https://beswic.be/nl/blog/hoge-werkdruk-rusthuizen]. In Vlaanderen voldoet bovendien **21% van de instellingen niet aan de wettelijke personeelsnormen**, wat de druk op bestaande medewerkers verder verhoogt. 

De voorbereiding van medicatie is een cruciaal maar tijdrovend onderdeel van het zorgproces in WZC. Elk pilletje komt in een individueel verpakt zakje binnen en moet handmatig verdeeld worden in de medicatiekar. Dit vereist het raadplegen van verschillende formulieren, visuele controle en het handmatig toevoegen van extra medicatie. Na deze stappen kan de verpleging met deze medicatiekar, op het juiste tijdsstip en bij de juiste persoon de medicatie toedienen. Dit proces is niet alleen arbeidsintensief, maar ook foutgevoelig, wat leidt tot onnodige vertragingen en frustratie bij het verplegend personeel. Het risico op fouten heeft bovendien grote gevolgen voor de veiligheid en het welzijn van de bewoners.

Het doel van dit project is het ontwikkelen van een verbetering die de efficiëntie en nauwkeurigheid van **medicatievoorbereiding** verbetert, zonder dat er een compleet nieuw systeem geïmplementeerd hoeft te worden. De oplossing moet betaalbaar, eenvoudig te integreren, en gebruiksvriendelijk zijn.  

  
## Methodologie
Max 400 woorden. Beschrijf je methodologie (enkel SEM1, zie les methodologie). Maak hierbij gebruik van een afbeelding om je tijdlijn weer te geven. Op deze tijdlijn moeten minimaal een tijdsincatie te zien zijn, moeten fasen te zien zijn en moeten activiteiten te zien zijn.
![image](https://github.com/user-attachments/assets/5ac7e321-7b09-46eb-8382-fa2c81e23f1e)


#### **Doel van de methodologie:**  
  Beschrijf wat je met deze methodologie wilt bereiken. 
  - Wat zijn de belangrijkste onderzoeksvragen? 
  - Welke aspecten wil je testen (bijv. efficiëntie, foutreductie, gebruiksvriendelijkheid)?  
  - Hoe dragen de verschillende fasen van dit project bij aan het beantwoorden van deze vragen?

---

#### **1. Discovery Fase**
- **Beschrijving:**  
  Deze fase richtte zich op het begrijpen van de problemen en behoeften van de gebruikers.  
  - Hoe heb je gebruikersonderzoek uitgevoerd? (bijv. interviews, observaties)  
  - Welke inzichten heb je hieruit gehaald?  
  - Welke knelpunten of behoeften kwamen naar voren uit de interviews met verpleegkundigen?  

- **Vragen om in te vullen:**  
  - Hoeveel respondenten heb je geïnterviewd?  
  - Welke vragen zijn tijdens het interview gesteld?  
  - Welke methoden heb je gebruikt om data te analyseren (bijv. transcriptanalyse, thematische codering)?  

---

#### **2. Prototyping en Testing – Eerste Iteratie**
- **Beschrijving:**  
  Deze fase richtte zich op het ontwikkelen en testen van de eerste groep prototypes.  
  - Wat was het doel van deze prototypes? (bijv. haalbaarheid, gebruiksvriendelijkheid, integratie in de werkomgeving)  
  - Welke aspecten zijn getest? (bijv. bedieningstype, fysieke grootte)  
  - Welke resultaten leverden deze tests op?  

- **Vragen om in te vullen:**  
  - Hoeveel prototypes zijn er getest?  
  - Hoe zijn de prototypes getest (bijv. gesimuleerde workflows, observaties in het WZC)?  
  - Wat waren de belangrijkste resultaten per test?  
  - Welke inzichten hebben geleid tot de pivot?  

---

#### **3. Prototyping en Testing – Tweede Iteratie**
- **Beschrijving:**  
  Deze fase richtte zich op het ontwerpen van prototypes die de verpleegkundige ondersteunen in plaats van taken volledig te automatiseren.  
  - Wat was het doel van deze iteratie? (bijv. verbeteren van samenwerking, minimaliseren van werkdruk)  
  - Welke aspecten zijn aangepast ten opzichte van de eerste prototypes?  

- **Vragen om in te vullen:**  
  - Hoe is dit nieuwe concept getest?  
  - Welke metrics zijn gemeten (bijv. tijdsbesparing, foutreductie, feedback van gebruikers)?  
  - Welke feedback is verzameld van verpleegkundigen?  

---

#### **4. Analyse en Conclusies**
- **Beschrijving:**  
  Deze fase omvatte het analyseren van de resultaten van beide iteraties en het trekken van conclusies.  
  - Hoe zijn de gegevens geanalyseerd? (bijv. kwantitatieve analyse, kwalitatieve feedback)  
  - Wat waren de belangrijkste conclusies uit de tests?  

- **Vragen om in te vullen:**  
  - Welke verbeteringen zijn aangetoond door de iteraties?  
  - Hoe hebben gebruikers gereageerd op de oplossing?  
  - Wat zijn de resterende vragen of uitdagingen?  

---

#### **5. Tijdlijn**
Maak een overzichtelijke tijdlijn met de volgende elementen:  
- **Fasen:** Discovery, Eerste Iteratie, Tweede Iteratie, Analyse.  
- **Tijdsaanduidingen:** Vermeld de periode per fase.  
- **Activiteiten:** Benoem specifieke activiteiten per fase (bijv. interviews, prototyping, testen).  

---

#### **6. Conclusie van de Methodologie**
- **Beschrijving:**  
  Vat samen hoe de methodologie heeft bijgedragen aan het verbeteren van het concept.  
  - In hoeverre zijn de doelen van efficiëntie, foutreductie en gebruiksvriendelijkheid bereikt?  
  - Hoe goed sluit het eindresultaat aan bij de behoeften van de gebruikers?  

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

## Bronnen
Voeg je volledige bibliografie toe van bronnen naarwaar je verwees.

## Bijlagen
