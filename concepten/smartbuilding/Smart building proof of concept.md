# Opdracht: Smart building proof of concept


### Achtergrondinformatie
Het innovatieteam van SSC-ICT doet onderzoek naar toekomstige ICT dienstverlening voor de Rijksoverheid. Hierbij wordt een jaarlijkse innovatieagenda gehanteerd, welke bestaat uit een aantal innovatie thema’s.
Voor het innovatiethema ‘Smart building’ onderzoeken we trends en ontwikkelingen aangaande werk en werkomgevingen in slimme gebouwen van de Rijksoverheid. De afgelopen periode zijn er in dit kader gesprekken geweest met diverse leveranciers van Smart Building en IoT oplossingen, in navolging waarvan we een aantal proof of concepts (PoC’s) gaan uitvoeren. Hierbij vragen we alle leveranciers een werkende oplossing voor dezelfde use case op te leveren. De use cases zijn in samenspraak met de facilitaire organisatie FMH en het Rijksvastgoedbedrijf (RVB) opgesteld, die als mede-Rijksorganisaties betrokken zijn bij het onderzoek naar Smart building concepten binnen de Rijksoverheid.


### Doelstelling
In de architectuur die het SSC-ICT innovatieteam voor ogen heeft, is een Smart building opgebouwd uit een aantal lagen, vanaf de stenen (het gebouw) tot aan de voor de ambtenaar bruikbare use case. De lagen daartussenin zijn wellicht niet altijd even zichtbaar, maar minstens zo belangrijk.

Voor ICT dienstverlener SSC-ICT hebben de PoC’s als primair doel kennis op te doen van de hierboven in oranje aangegeven lagen. Hierbij gaat het met name om het vinden van een generiek platform waarop:

* sensoren en actuatoren van diverse leveranciers en organisaties gemakkelijk kunnen worden aangesloten,
* sensordata kan worden opgeslagen en toegankelijk kan worden gemaakt voor zowel intern als extern gebruik (realtime import/export) en externe databronnen kunnen worden gekoppeld (gebouw management systeem, weer, verkeer, etc.),
* toepassingen als applicaties, apps en websites gebruik kunnen maken van de aanwezige databronnen en functionaliteiten middels API’s.

De aangeboden oplossing zal in principe als PoC volledig los komen te staan van de reeds aanwezige infrastructuur binnen SSC-ICT of het pand, een internetverbinding is echter wel aanwezig. Voor de PoC is om deze reden een cloud-oplossing gewenst, alhoewel hosting in een overheidsdatacenter (ODC) voor de definitieve keuze op lange termijn de voorkeur heeft.
Het staat de aanbieders vrij om de use case naar eigen inzicht te realiseren (type sensoren, infrastructuur, platform en gebruikersinterface), zolang deze gericht is op het zo flexibel mogelijk kunnen inzetten van de oplossing. De Rijksoverheid heeft hierbij voorkeur voor het gebruik van Open Source en Open Standaarden.

### Use cases
Om de platformen van de diverse aanbieders zo goed mogelijk te kunnen beoordelen, wordt gevraagd een werkende werkplekbezetting use case te leveren voor de duur van 3 maanden, met de optie voor een eventuele verlenging. Hierbij blijft de scope per aanbieder van de PoC beperkt tot 1 verdieping (ca.50 werkplekken) van het pand van SSC-ICT en FMH aan de Koningskade 4 in Den Haag.

#### Gevraagde use case 1: Werkplekbezetting

<table>
  <tr>
   <td><em>Omschrijving</em>
   </td>
   <td>Het is in een flexwerkconcept soms even zoeken naar een vrij bureau of vergaderruimte. Daarmee ontstaat het gevoel dat het gebouw vol is terwijl er mogelijk nog ruimte is. Daarbij kiest men vaak uit routine voor dezelfde werkplek of verdieping, terwijl er elders in het pand ruimte is. Deze use case zal specifiek uitgevoerd worden op de volgende verdiepingen aan de Koningskade 4: verdieping 7, 11, 12 en 13.
<p>
Per leverancier zal een specifieke verdieping toegewezen worden om de use case te implementeren.
<p>
   </td>
  </tr>
  <tr>
   <td><em>Verwacht resultaat PoC</em>
   </td>
   <td>Het real-time kunnen meten van actuele werkplek- en vergaderruimte-bezetting en dat visueel te presenteren via een dashboard.
   </td>
  </tr>
</table>

Daarnaast heeft SSC-ICT samen met het RVB en FMH een aantal use cases opgesteld die als doel hebben een beeld te geven van de (mogelijke) toekomstige dienstverlening op het gebied van Smart buildings. Deze use cases (2,3 en 4) worden door het SSC-ICT innovatieteam samen met FMH en het RVB uitgevoerd op basis van het in de PoC geleverde platform, waarbij de leverancier desgevraagd ondersteuning biedt tbv de aansluiting.

#### Use Case 2: Bevrijd de data uit het gebouw
<table>
  <tr>
   <td><em>Omschrijving</em>
   </td>
   <td>Bestaande gebouwbeheersystemen bevatten veel bruikbare data. SSC-ICT wil deze data kunnen ophalen en analyseren voor onder andere energiekostenbesparing.
   </td>
  </tr>
  <tr>
   <td><em>Verwacht resultaat PoC</em>
   </td>
   <td>Middels connectoren en API’s in staat zijn data uit de bestaande systemen (van bijv. het pand aan de Koningskade 4) in een smart building platform krijgen, zodat het vervolgens kan worden bewerkt, geanalyseerd  en gepresenteerd via een dashboard.
   </td>
  </tr>
</table>

#### Use Case 3: Gezonde werkomgeving
<table>
  <tr>
   <td><em>Omschrijving</em>
   </td>
   <td>Voor een gezonde en prettige werkomgeving voor alle medewerkers wil SSC-ICT in staat zijn de volgende omgevingsfactoren te meten en te analyseren:
<p>
Geluid, temperatuur, waterkwaliteit, CO<sub>2</sub>, luchtvochtigheid en luchtkwaliteit. Bij waterkwaliteit gaat het bijvoorbeeld om het detecteren van een mogelijk legionella risico.
   </td>
  </tr>
  <tr>
   <td><em>Verwacht resultaat PoC</em>
   </td>
   <td>Diverse omgevings sensoren aan kunnen sluiten op een smart building platform, middels connectoren en API’s, zodat SSC-ICT in staat is de sensoren uit te lezen en te analyseren vanuit een dashboard omgeving.
   </td>
  </tr>
</table>


#### Use Case 4: Inzet voice assistant
<table>
  <tr>
   <td><em>Omschrijving</em>
   </td>
   <td>Voice assistants zoals Amazon Alexa of Apple Siri worden gezien als de toekomstige interactie van gebruikers met smart homes en smart buildings. We willen kunnen experimenteren met de combinatie van een voice assistant en een smart building platform met actoren.
   </td>
  </tr>
  <tr>
   <td><em>Verwacht resultaat PoC</em>
   </td>
   <td>Inzicht krijgen in de functionele en technische werking van een voice assistant met smart building toepassingen. Denk hierbij aan inzicht te verkrijgen in de functionele en technische complexiteit, data aggregatie en presentatie en welke toepassingen mogelijk zijn met die data.
   </td>
  </tr>
</table>


### De procedure & planning
Omdat SSC-ICT snel van start wil gaan en tot resultaten wil komen binnen het project ‘Smart building’, is de planning vrij strak. De precieze invulling van fases en belangrijke data zal na gunning in gezamenlijk overleg plaatsvinden. Belangrijke richtdata zijn in elk geval:

* Deadline offerte: 28 juni 2019
* Berichtgeving besluit gunning: 1 juli 2019
* Deadline oplevering werkende usecase: 1 augustus 2019
* Einde PoC: 3 maanden na oplevering werkende usecase

Als eerste vervolgstap verwachten we een offerte met daarin:

* Conceptvoorstel met aanpak
* Beoogde tijdsplanning
* Begroting / totale kostenplaatje
* Eventuele opties

Concreet en samenvattend vraagt SSC-ICT een aanbieding met daarin:
* Use case 1 ‘Werkplekbezetting’ werkend op te leveren voor een periode van 3 maanden (met de optie voor een eventuele verlenging) op basis van een generiek IoT platform.
* Ondersteuning en advies te bieden bij de aansluiting op het te leveren platform van de PoC’s van use cases 2, 3 en 4, welke als losse projecten door het SSC-ICT innovatieteam worden uitgevoerd. 

### Randvoorwaarden
* Toegang tot alle bestaande en eventueel nieuw te ontwikkelen API’s (en potentieel data query laag), waarmee we in staat moeten zijn om diverse typen hardware, databronnen en applicaties te ontsluiten.
* Beschikbaarheid van een real-time dashboard voor data die door het platform verzameld wordt.
* Gebruik kunnen maken van verschillende communicatieprotocollen zoals: LoRa, LTE, WiFi en Bluetooth.
* Ownership en (te allen tijde) vrije toegang tot de data, tijdens en na de PoC.
* Technische ondersteuning van de leverancier tijdens de looptijd van de PoC.

### Contact
Contactpersonen voor het project zijn:
* Organisatie: Ramon Fiedler
* Techniek: Victor Gevers



