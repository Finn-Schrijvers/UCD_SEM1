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

In woonzorgcentra (WZC) is medicatieverdeling een tijdrovende en foutgevoelige taak die direct bijdraagt aan de hoge werkdruk van verpleegkundigen. Onderzoek toont aan dat bijna **49% van de zorgverleners kampt met een hoge werkdruk**, mede veroorzaakt door personeelstekorten en de toenemende vergrijzing [Hoge werkdruk in rusthuizen | Beswic. (n.d.). https://beswic.be/nl/blog/hoge-werkdruk-rusthuizen]. In Vlaanderen voldoet bovendien **21% van de instellingen niet aan de wettelijke personeelsnormen**, wat de druk op bestaande medewerkers verder verhoogt. 

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
  - Contextual inquiries
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EbsFMVmtLS9PsmruQO7G164BsZ5_j9Fu6Rl854Qa3qWmYQ?e=QRkYSC)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/Eas4YG_7SpxApFeq5h0TQsYBoihKIDYJINAHUwYjbGnJOA?e=orFrf5)
  - Focus groups
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EWh6baFsMMRGoy3ka52hPG4BzbzurMG2UVsQyipgFQgmfw?e=gE4W8u)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EcaQ1q157GFNu4digImXqBoBSc3dnoYHoLg65hIQWaBKaA?e=4kcSHy)
  - Benchmarking
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EXawcWpXBVpEt_lIMpMp_2ABLn8YT56Gweo287PCzCVebw?e=ohLtQk)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/ES47CYFbTF1EnaaEx6L9F90BNoMAPfkbhsjLT51bKq1DlA?e=dMLCQ5)
- Definition
  - Dial
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EXA8tLux91JJgyoZDhd7l8EBiHgo0lbct7zmwVrcxtyVpQ?e=EAw8CV)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/ES0ZpXk9lqNEglcTKWC2yTYBzBOITMq5B5F91GWfasvyiA?e=wBfrfh)
  - User interface
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EZTgPm-nd4pIsmm8usEYeBUBz1gfDapTBei-XWnFm_MZ7g?e=bN2sFI)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EeAsWolB5e9JmBZqcdCANsUBhkX-JtqDsruhD6Gw2MzLAQ?e=icrMtT)
- Develop 1
  - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/Ed5Cw6uYuAREtow-HiDa7TQBSTC7YIpYGRGnOxcfrB0F6w?e=EO4oEH)
  - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/ETyGm0r8TDZHsSQlNxfRxxwBqzdG42B0hlqhnKxVS78oCg?e=2yokI9)
- Develop 2
  - Expert review
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/ETqsrg_xHrBOkA1brbJ3t2IBkXsYxzCnGieAo1CWaPYekw?e=dK0oaT)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EfVC145y3KxDvudC-U4TsT8BUycW9wZWifMW9NHYxgdx_A?e=c0tfIG)
  - Usability test
    - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EV5OZfwtGPBFrt3uwZXcVNcBihPvPzmzFxCDzjzQltVrZA?e=9NACFB)
    - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EeRQD4A97TdJoxIuUXeTQNYBUtt4XM00AD7CwpS1mvPMRg?e=ToBzBb)
- Develop 3
  - [protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EXClvOz8INdJgKvF5UcQUhIBYpvQ8Hyk5CacbJ5YMebfbQ?e=SSEOhn)
  - [report](https://ugentbe-my.sharepoint.com/:b:/g/personal/korneel_verraes_ugent_be/EdHE8VL7fB5EkfIlp2sKCNsBZ6HWYYmyrerdYaaHGuqJ-A?e=hXYgPn)

## Bronnen
[^1]: Beeckman, H. (2021, 11 maart). *Aanraakschermen in je auto bedienen drie keer gevaarlijker dan rijden onder invloed: “Europese regels nodig”.* VRTNWS. https://www.vrt.be/vrtnws/nl/2021/03/11/aanraakschermen-in-je-auto-bedienen-drie-keer-gevaarlijker-dan-r/
[^2]: TRL (2019, 15 april). *Distracted Driving Evidence Has Fallen Behind the Latest Technological Changes.* TRL. https://www.trl.co.uk/news/distracted-driving-evidence-has-fallen-behind-the-latest-technological-changes
[^3]: Rotmans, M. (2005). *DINBelg 2005* [Dataset]. https://www.dinbelg.be/DINBelg%202005%20antropometrie%20tabel.PDF


## Bronnen
Voeg je volledige bibliografie toe van bronnen naarwaar je verwees.

## Bijlagen
