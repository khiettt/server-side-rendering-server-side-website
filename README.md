# Milledoni's categorie pagina

In sprint 8 hebben wij kennis gemaakt met een nieuwe opdrachtgever. De afgelopen twee weken heb ik een website kunnen bouwen voor [Milledoni](https://milledoni.com/gb/en), zij wilde graag een nieuwe categorie waarop er gefiltert kan worden. 
<hr>

## Wat voor website is milledoni? 
Milledoni is een cadeau-inspiratieplatform / verzamelwebsite voor cadeaus en is opgericht door **Federica Foroni Lo**. Zij wilde graag mensen helpen die opzoek waren naar een perfecte cadeau. Op Milledoni vindt je niet zomaar cadeaujes, maar originele cadeau-ideeën die verzameld worden door spotters. Milledoni verkoopt zelf geen producten maar is een tussenplatform die je kan verwijzen naar webshops als bol.com, amazon en noem maar op. 


## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)

## Beschrijving

Milledoni wilde een vernieuwede categorie pagina met de nieuwe huisstijl/design die wij van hun hebben gekregen. Om een mooie categorie-pagina te maken ben ik begonnen met het ophalen van de data uit de [database](https://fdnd-agency.directus.app/items/milledoni_products). En heb ik designs, een [wireflow](https://github.com/khiettt/server-side-rendering-server-side-website/issues/2#issue-4028042986) en een [sitemap](https://github.com/khiettt/server-side-rendering-server-side-website/issues/2#issuecomment-4004859093) gemaakt 

<hr>

**Dit is de homepage van [Milledoni's](https://milledoni.com/gb/en) nieuwe website en zij wilde een categorie pagina die hierbij past.**

<img width="1495" height="856" alt="Scherm­afbeelding 2026-04-02 om 17 11 57" src="https://github.com/user-attachments/assets/b58cf19a-dd18-4ec7-9ebd-05193acba5ae" />


## Gebruik

Hieronder zie je mijn designs voor de categorie-pagina. Milledoni heeft meer dan 10 soorten categorieën dus ben ik mij gaan focussen op 1 cadeaus voor moeders. Het is de bedeoling dat je op de pagina kan filteren en sorteren om verschillende ideeen, zoals boeken, kleding, huishoudelijke producten, beauty producten ect. Ook willen ze dat je kan filteren de prijsklasse en cadeautjes wwaarmee je iets kan hebben of doen. 

<img width="919" height="581" alt="Scherm­afbeelding 2026-04-02 om 16 06 41" src="https://github.com/user-attachments/assets/a8ac7469-da2a-474b-80ea-be7a2acf6ca7" />


## Kenmerken
Voor dit project heb ik gebruik gemaakt van HTML, CSS, JavaScript, Node.js, JSON en Liquid. Samen zorgen deze technologieën ervoor dat de website zowel visueel goed werkt als dynamische content kan tonen.

Om [data op te halen](https://github.com/khiettt/server-side-rendering-server-side-website/blob/f9a55b8e5972d63f8905c55d78dbbd4d728b0031/server.js#L52) en te verwerken heb ik Node.js gebruikt. Hierbij heb ik [JSON-bestanden](https://github.com/khiettt/server-side-rendering-server-side-website/blob/f9a55b8e5972d63f8905c55d78dbbd4d728b0031/server.js#L54-L57) ingelezen, waarin de data is opgeslagen. Deze data heb ik vervolgens met behulp van [Liquid](https://github.com/khiettt/server-side-rendering-server-side-website/blob/f9a55b8e5972d63f8905c55d78dbbd4d728b0031/views/index.liquid#L16-L26) in mijn HTML-templates geplaatst, zodat de content automatisch gegenereerd wordt op de pagina’s.

HTML vormt de basisstructuur van de website, en met CSS heb ik de vormgeving en layout verzorgd. Hiermee heb ik onder andere mijn categoriepagina gestyled en overzichtelijk gemaakt voor de gebruiker.

<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

## Installatie
volg de volgende stappen m aan deze repository te werken:

Stap 1: instaleer de [NodeJS ontwikkelomgeving](https://nodejs.org/) en kies voor NodeJS 24.13.0 (LTS, long-term support), download het installatiebestand en doorloop het installatieproces.

Stap 2: fork deze repository en clone deze naar een code editor. 

Stap 3: Open de _Terminal_ in VSCodium door de toetscombinatie `` ^` `` (control + `) te gebruiken. Er opent een terminalscherm in de hoofdmap van jouw project. Voer in de terminal het commando npm install uit, door het in te typen en op enter te drukken. 

Stap 4: Na de installatie is de map `node_modules` aangemaakt, en gevuld met allerlei _packages_. Start de website door in de terminal het comando `npm start` uit te voeren. Als het goed is, komt hier een melding te staan over het opstarten van de server: Application started on http://localhost:8000 — Open deze URL in je browser
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->

## Bronnen
[FDND Prototype](https://milledoni.dev.fdnd.nl)

[Milledoni's figma designs](https://www.figma.com/design/tHCHwBm3Ujv7wR28VU2BSu/Milledoni?node-id=0-1&p=f&t=69YSfcg8ISRmhixV-0)

[FDND Directus Milledoni Database](https://fdnd-agency.directus.app/items/milledoni_products)







De instructie van sprint 8: [INSTRUCTIONS.md](https://github.com/fdnd-task/server-side-rendering-server-side-website/blob/main/docs/INSTRUCTIONS.md)
