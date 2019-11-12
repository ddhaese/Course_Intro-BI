## Richtlijnen voor het schrijven van de blueprint

Hieronder volgen een aantal richtlijnen voor het schrijven van de blueprint:

### Lees de Theorie

De theorie is niet al te veel maar je moet het wel grondig bekijken. Zonder die kennis kan je de blueprint niet tot een goed einde brengen.

### Consultancy

Jullie moeten het scenario volgen dat jullie als consultant een blueprint moeten opleveren voor het bedrijf. Het bedrijf is dus jullie klant en het doel van de blueprint is om een functionele en technische analyse voor te leggen. Dit zijn dus zinnen die in de blueprint niet thuis horen:

*De reden dat we deze [primaire] dataset willen gebruiken is&hellip;* (omdat je die in het scenario gekregen hebt) of nog : *Dit past binnen Business Intelligence omdat...*

Om dit scenario concreet te maken wordt je gevraagd om de klant te schetsen: uit welke industrietak komen ze en wat is hun core business.

### Afnemersgroep of doelgroep

Zorg ervoor dat het duidelijk is welke twee groepen de afnemers zijn van de voorgestelde BI solutions, voorbeeld Financiën en data miners van Marketing, Het management en de wetenschappers, ...

### Op te leveren

Wat je zal moeten opleveren heeft te maken met visualisaties (tabellen of grafieken) en oplossingen (lettelijk bijvoorbeeld een Visual Studio Solution) die de vragen van de klanten moeten helpen beantwoorden. Het gaat om wat je zal opleveren tegen het einde van het project. Dus, analyse hoort daar niet bij!

### Persoonlijke en bijvoeglijke voornaamwoorden

Probeer deze te vermijden, vervang bijvoorbeeld:

*Eerst en vooral hebben we opgemerkt dat er wat problemen zijn met de data&hellip;*

door:

*Er zijn problemen met de data&hellip;*

en:

*Enorm veel..*

door:

*De meerderheid van...*

### Versionering

Zorg ervoor dat de versie in de bestandsnaam overeenkomt met de versie aangegeven ín het versiebeheer.

## BI project versus ML project

Opgelet: Het doel van een BI project is om de data te centraliseren en te structureren alsook het aanleveren/voorstellen van een BI tool zodat eindgebruiker is staat is *zelf* op zoek te gaan naar antwoorden op zijn vragen. Binnen een ML project, daarentegen, houdt men zich gewoonlijk niet bezig met  data opslag en moet een *ML algoritme* helpen om patronen in de data te ontdekken waarvan de resultaten aan de eindgebruiker worden meegedeeld.

## Wikipedia

Alles wat de lezer kan terugvinden op Wikipedia moet ook op Wikipedia blijven. In een Blueprint als dit moet je specifiek jullie case bespreken en niet in algemeenheden vervallen. Het is natuurlijk wel OK om Wikipedia te citeren, maar geef dan enkel een korte uitleg (paar woorden) + een link. Ook voor schema's: zorg dat de schema's van toepassing zijn voor jullie specifieke case!

## Reproduceerbaarheid

Een blueprint is in feite een plan van aanpak. Voor deze blueprint moet je ervoor zorgen dat het voldoende reproduceerbaar is. Dit betekent dat:

1. De minder-technische lezer in staat moet zijn te begrijpen wat precies de functionele vereisten zijn. Zo moet de klant kunnen controleren of jullie opvattingen van de vereisten stroken met hun verwachtingen.
2. Technische profielen moeten in staat zijn om op basis van jullie technische omschrijving zelf aan de slag te gaan en zulke systemen op te zetten. Jullie moeten er dus voor zorgen dat alle informatie om dit te doen beschikbaar is.
