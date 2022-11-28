# Opdrachten modules

## Mappen aanmaken

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`
Uit de vorige les!
3. Maak een map `eindopdrachtweb`
4. Open de `eindopdrachtweb` folder in visual studio code


## files opzetten

1. Kopieer files van het `les1` naar 
 `eindopdrachtweb`

 * `index.html`
 * `app.js`

2. open de directory `modules` in visual studio code

## javascript fetch! 

we gaan de fetch api gebruiken van javascript. Deze moderne library zit in alle browsers. 
Deze gebruiken we om web content op te halen naar onze pagina of javascript toe.

* denk aan API calls
* data files ophalen
* stukken html ophalen
* etc

1. lees je in de API in:
![fetch api](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)


we gaan pokemon ophalen vanuit de site `https://pokeapi.co/` die biedt een `REST-api` aan
Dat is een manier om data op te halen

1. probeer de data van ditto op te halen met de voorbeeld url `https://pokeapi.co/api/v2/pokemon/ditto`
2. als je data terug gekregen hebt haal dan de `naam` en 1 van de `sprite` urls (plaatjes) eruit
3. zet deze in losse `variabelen`

## voorbereiden voor het tonen in html

1. maak voor de naam een `<p>` tag aan in je html
2. maak voor het plaatje een `<img>` tag aan. zet de src niet!
3. geef beide nieuwe tags een `uniek id`

## terug naar javascript

1. haal de `<p>` en de `<img>` tag op met `document.getElementById` en bewaar deze in variabelen
2. zet de waarde van de naam op de `textContext` van de `<p>` tag
3. zet de `src` van de `<img>` tag op de waarde van de sprite (dit zijn urls)

## verander nu de pokemon eens

1. maak ipv ditto er nu mew van.
2. wat gebeurt er?

## meer data ophalen

1. in het resultaat uit de api zit ook een `species` stuk, met een `url` naar de species.
2. haal de species op met de `fetch-api` en `display` de informatie die je krijgt
3. zie je hoe je zo door de api heen kan gaan? net als een website kan je links volgen

## dynamisch op user input reageren

1. maak een `text input` aan en een `button` in je `html`
2. als je op de knop clicked moet je de `text input` lezen.
3. die waarde geef je als pokemon naam mee naar de api
4. als het goed is verandered nu de pokemon als je op de knop clicked


## pokemon toevoegen

1. verander `button` code, zorg dat je pokemon kan toevoegen aan je collectie
2. nu moet je ook html kunnen toevoegen als je een nieuwe pokemon toevoegd

* maak je html zo dat je meerdere pokemon kan laten zien, zonder de html te herhalen in je index.html. Maak deze dynamisch aan (bv met een template of in code)

TIP!: zoek `.querySelector` en `.querySelectorAll` eens op en wat die doet (deze kan je ook op een eerder geselecteerd element gebruiken!), dat kan je een hoop helpen!

## Extra:

* sla je toegevoegde pokemon op met de `local storage api` (![storage api](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage))
* style je pagina en pokemon `cards`
* gebruik een externe style `.css` file (![rel link](https://www.w3schools.com/tags/att_link_rel.asp))
* heb je al flexbox css gehad? gebruikt dat (zie ook flexbox froggy voor oefeningen)


## klaar?

1. commit & push je werk naar github





fetch is erg sexy, geen onreadystate meer via AJAX haha.

Maar 2x fetch lijkt mij prima 🙂Hieronder heb ik wat vette api's opgesomd:

https://swapi.dev/ 

SWAPI - The Star Wars API
What is this? The Star Wars API, or "swapi" (Swah-pee) is the world's first quantified and programmatically-accessible data source for all the data from the Star Wars canon universe!
swapi.dev
https://github.com/Dchane06/Family-Guy-Quotes-API 
 
Dchane06/Family-Guy-Quotes-API: An API filled with quotes from the television show Family Guy. - GitHub
A tag already exists with the provided branch name. Many Git commands accept both tag and branch names, so creating this branch may cause unexpected behavior.
github.com

https://digimon-api.com/ 
DAPI
Get digimon Endpoint: digi-api.com/api/v1/digimon/{id} or {name} This will return a digimon and all its information. You can use the following path parameter:
digimon-api.com
https://thecatapi.com/ 
