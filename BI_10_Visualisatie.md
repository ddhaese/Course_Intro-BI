# Intro BI (32321/1700/1920/1/27)

## Visualisatie

Visualisatie van de Business data is typisch één van de laatste mijlpalen in het opzetten van een *datawarehousing solution*. Er zijn ook hier hele bibliotheken over geschreven. Enkel de belangrijkste principes zullen hier aan bod komen.

### Regels

Herbekijk de [levenscyclus](BI_01_Intro_BI.md#lifecycle). Het creëren van inzichten over de data is een cruciaal onderdeel van BI. Het komt er dan ook op neer om een zo goed mogelijk overzicht te geven van de data zodat de eindgebruiker zijn vragen beantwoord ziet. Maar wat is 'zo goed mogelijk' en hoe bereik je dat? Dit is natuurlijk geen exacte wetenschap maar er zijn een aantal regels die we in acht kunnen nemen:

- **Vetrek vanuit de vraagstelling** - Zoals in de BI levenscyclus te zien is, staat de visualisatie niet op zichzelf. Het heeft als doel om de vragen van de eindgebruiker te beantwoorden. Als gevolg is het ten zeerste aan te raden te vertrekken vanuit de vraag en niet vanuit de beschikbaarheid van de data. Elk element van de visualisatie moet onder de loep genomen worden.
- **Begrijp de data** - Spendeer voldoende tijd in het grondig begrijpen van de data door zelf de juiste vragen te stellen en er een antwoord op te vinden. Het is niet voldoende enkel de omschrijvingen van de tabellen te lezen (hoewel dat uiteraard een goed begin is).
- **Plaats de eindgebruiker eerst** - Maak abstractie van wat je zelf graag wil beantwoord zien en denk aan de eindgebruiker, wat wil die zien en wat is die zijn of haar expertise?
- **Gebruik het juiste medium** - Denk na of er nood is aan interactiviteit, kent de gebruiker het platform of is het zo gebruiksvriendelijk dat er niet aan valt te leren? Wil de eindgebruiker via de smartphone de data oproepen?
- **Gebruik de juiste grafiek** - Dit werd eerder reeds besproken. Elke data type en combinaties ervan heeft een bepaalde ideale grafiektype. Denk hier eerst grondig over na want het kost enige tijd om een dashboard te maken.
- **Wees eerlijk** - Zorg ervoor dat de gemaakte keuzen naar data behandeling en visualisatie niet tot de verkeerde conclusies kunnen leiden. Wees eerlijk in waar de data precies vandaan komt en hoe betroubaar de data werkelijk is en zorg dat de eindgebruiker hiervan op de hoogte wordt gebracht.
- **Wees volledig** - Kijkt de gebruiker naar slechts een deel van de data of is er (zoals vaak het geval) een snapshot genomen, zorg er dan opnieuw voor dat de eindgebruiker hiervan op de hoogte wordt gebracht.
- **Benoem** - Benoem grafieken (i.e. voorzie grafieken van bondige titels), en assen. Voorzie assen van een logische schaal en de juiste maateenheid. Voeg legendes toe zodat elk element in de grafiek of tabel begrijpbaar zijn voor de eindgebruiker.
- **Wees zuinig** - Elementen in de visualisatie die niet bijdragen tot het bekomen van de nodige inzichten moeten onherroepelijk worden verwijderd
- **Pipeline** - Zorg ervoor dat alle visualisaties automatisch gegenereerd kunnen worden vanuit de datamarts zonder enige handmatige tussenkomst.
- **Consistent** - Gebruik dan gelijkaardige visualisaties voor gelijkaardige problemen
- **Feedback** - Zorg ervoor dat de eindgebruiker de kans heeft om de BI architect te contacteren met vragen of commentaren. Wat de architect als logisch ervaart is niet per sé hetzelfde dan wat de eindgebruiker als logisch en eenvoudig ervaart.

> Opdracht: Lees [dit Wikipedia artikel](https://en.wikipedia.org/wiki/Cherry_picking) rond cherry-picking.

### Tekst versus Beeld

Oftewel: tabellen versus grafieken. Laten we beiden vergelijken:

Tabellen zijn nuttig wanneer:

- Wanneer de brondata in zijn ruwe vorm bekeken moeten worden
- Wanneer de data te complex is en er geen goede visualisatie gevonden wordt of te complex zou worden
- Wanneer de exacte numerieke waarden van belang zijn, bijvoorbeeld om aan te tonen dat er een patroon zit in de cijfers 'achter de komma' of wanneer de absolute aantallen (bijv aantal klachten, financiële cijfers) exact moet kloppen
- Wanneer de hoeveelheid (geagreggeerde) data beperkt is
- Wanneer de ontbrekende gegevens onderzocht moeten worden

Grafieken zijn nuttig wanneer:

- Focus op trends en numerieke relaties
- Vereenvoudiging nodig want de data is volumineus en/of complex
- Wanneer patronen ontdekt dienen te worden
- Wanneer distributies van belang zijn
- Wanneer het overzicht belangrijker is dan de individuele waarden
- Wanneer niet alle data die getoond moet worden even belangrijk is en er aan elk data-element een gewicht moet worden toegekend

### Statisch versus Dynamisch

Zowel tabellen als grafieken kunnen interactief worden gemaakt. Denk goed na alvorens te investeren in interactieve grafieken. Meestal vergt interactiviteit meer tijd om te maken en vereist het maak input van de architect. Dus alvorens je begint moet je ervan overtuigd zijn dat het een meerwaarde biedt voor de eindgebruiker.
