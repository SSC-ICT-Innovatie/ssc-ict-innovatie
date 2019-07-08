# Voice assistant
Voice control is sterk in opkomst. Dat is op zich geen nieuws, want digitale assistenten als Siri bestaan al jaren. Toch begint het kantoorgebruik van stemtechnologie nu pas echt door te breken. Hier in Nederland is het nog even afwachten, maar er is absoluut geen reden om stil te zitten. Wat kunnen wij met deze voice assistants wanneer ze de [Nederlandse taal](https://www.smarthomemagazine.nl/2018/07/nederlandse-google-assistant-home/) gaan beheersen?

## Aanleiding
Algemene informatie over onze organisatie is voor een groot deel vervat in intranet en FAQ.
Dat heeft twee problemen:
 1. Het is soms best een zoektocht om de juiste info te vinden (ook met de zoekfunctie)
 2. Niet altijd heb je toegang tot intranet als je een vraag hebt.
Daarnaast worden vanuit veel invalshoeken voice assistenten gezien als volgende interactie met gebruikers. Goed om op een niet al te complexe manier hier mee te gaan experimenteren om ervaring op te doen bij het maken en de interactie met de gebruikers.

De opdrachtgever geeft deze [video](https://youtu.be/ViB3XhsTLuo) als voorbeeld voor een concept.

## Hypothese
Met het ontsluiten van de geisoleeerde informatie via een voice assistent bijdragen aan een nieuwe gebruikerservaring.

## Wat wil de opdrachtegever bereiken met het concept?
 1. Ervaring opdoen met
   a. Het ontsluiten van informatie uit bestaande bronnen (intranet) voor voice assistenten
   b. Gebruikers feedback ophalen op deze manier van informatie aanbieden en deze wijze van interactie
 2. Opdoen van ideeen voor meer usecases.

## Technologische verkenning


### 2019

* 07-07: [Voorstel](voorstel-digibeter2019-challlenge.md) voor DigiBeter2019 [innovatie challenge] is [afgewezen](https://trello.com/c/DSMZMxvS/3-het-nieuwe-werken#comment-5d231ef5a0ab05474f051fce)
* 30-05: [Voorstel](voorstel-digibeter2019-challlenge.md) voor DigiBeter2019 [innovatie challenge](https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/innovatie/innovatiebudget/challenges/) ingediend.
* 29-05: [Eten bestellen via Thuisbezorgd met behulp van de Google Assistent](https://www.nu.nl/gadgets/5913870/thuisbezorgd-laat-klanten-eten-bestellen-met-google-assistent.html)
* 10-04: Motivatie om *geen* gebruik te maken van Google Assistant en Google Home in de toekomst is vanwege de [reclame boodschappen](https://www.nu.nl/internet/5831655/google-voegt-advertenties-toe-aan-stemassistent.html) die er straks er door heen kunnen gaan komen.


#### Concept ontwikkeling
- [KanBan board](https://github.com/SSC-ICT-Innovatie/ssc-ict-innovatie.nl/projects/2)

### 2018
Op het moment heeft aleen Google Home een ondersteuning voor de Nederlandse taal (in BETA). Daarom gaan we de eerste prototype bouwen boven op [DialogFlow](https://dialogflow.com) en met [Actions](https://developers.google.com/actions/) met dit Smart Home [voorbeeld in Node.js](https://github.com/vgevers/smart-home-nodejs). Het voorbeeld is hier [gebouwd](https://ssc-ict-innovatie.slack.com/messages/CDJA596DQ).

Open source project [MyCroft](https://community.mycroft.ai/t/how-to-get-mycroft-to-speak-and-understand-dutch/4963) maakt gebruik van Google services voor een Nederlandse taal ondersteuning. De [On Premise](https://mycroft.ai/enterprise/) Enterprise oplossing heeft nog geen eigen ondesteuning voor de Nederlandse taal. Het bedrijf [AmberScript](https://www.amberscript.com/nl/home#we-are-revolutionizing-transcription-services) heeft Nederlandse spraakherkenning voor het transcriberen van Nederlands gesproken geluidsopnames naar tekst en draaien deze services op hun eigen servers.
