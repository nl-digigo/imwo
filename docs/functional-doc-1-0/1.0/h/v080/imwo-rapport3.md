## Inleiding

### Achtergrond

De ketenpartners die in het Bestuursakkoord Digitale Gebouwde Omgeving afspraken gemaakt hebben over digitaal samenwerken hebben geconstateerd dat gegevens over woningen en woongebouwen veelal niet goed uitwisselbaar zijn doordat iedere ketenpartner eigen definities en informatiemodellen heeft. Daarom hebben ze besloten een woongebouwinformatiemodel te ontwikkelen dat een brug slaat tussen hun eigen architectuur en definities en die van hun ketenpartners. Hierdoor wordt het makkelijk om elkaars begrippen te vertalen, informatie uit te wisselen en uiteindelijk het hergebruik van informatie en samenwerking tussen ketenpartners te bevorderen. 

### Projectgroep

| Naam                    | Organisatie                                | Rol                  |
| ----------------------- | ------------------------------------------ | -------------------- |
| Robert Versteeg         | digiGO                                     | Projectleider        |
| Hein Corstens           | digiGO                                     | Informatiemodelleur  |
| Martijn van Glabbeek    | digiGO                                     | Product Owner GEBORA |
| Paul Strokap            | Neprom                                     |                      |
| Henk Nijstad            | Aedes                                      |                      |
| Willem Pel              | Ketenstandaard                             |                      |
| Gert Koutstaal          | Ketenstandaard                             |                      |
| Ruud Kathmann           | Waarderingskamer                           |                      |
| Rolf Jonker             | Geonovum / gemeente Rotterdam              |                      |
| Wiechert Eschbach       | Windesheim                                 |                      |
| Gerlof de Haan          | Vereniging van Nederlandse Gemeenten (VNG) |                      |
| Marco Witschge          | Techniek Nederland                         |                      |
| Jan Brinkkemper         | Aedes                                      |                      |
| Aydemir Çetin           | NL Ingenieurs / BuildingSmart              |                      |
| Joppe Duindam           | Bouwend Nederland                          |                      |
| Daniël Carree           | Rijksvastgoedbedrijf                       |                      |
| Jan Hendrik Nieuwenhuis | Rijksvastgoedbedrijf                       |                      |
| Martijn Nijkamp         | BNA                                        |                      |
| Jeroen Pat              | Bouwend Nederland                          |                      |

Ontologische ondersteuning: Marcel Krassenburg - MKidee

### Doel

Het doel van BM20 is een uitwerking tot begrippenkader en conceptueel informatiemodel van de begrippen woning en woongebouw, die ketenpartners kunnen (her-)gebruiken binnen hun eigen context. Het informatiemodel heeft de functie van referentiemodel en kan als ‘canoniek model’ – als centraal vertaalhulpmiddel – ingezet worden.

### Scope

Het informatiemodel heeft betrekking op informatie, die door meerdere ketenpartners wordt hergebruikt. Informatie die uitsluitend relevant is voor één ketenpartner valt daarmee buiten de scope van deze maatregel.

### Uitgangspunten

Het IMWO is een onderdeel van de GEBouwde Omgeving Referentie Architectuur (GEBORA).IMWO is een uitwerking van het Bedrijfsobjectenmodel (domein Bouwwerk).

Het IMWO is een conceptueel informatiemodel, dat de betekenis en de structuur van de relevante informatie beschrijft, onafhankelijk van het ontwerp van en de implementatie in systemen. Het is gericht op communicatie tussen domein- en IT-experts. 

De huidige versie van IMWO beperkt zich tot de specificatie van  objecttypen en relaties. Attribuutsoorten en kardinaliteiten komen nog niet of nauwelijks aan de orde: de prioriteit is gelegd bij het grip krijgen op de breedte van het domein. Pas bij de uitwerking per subdomein zal er dieper gegaan worden.

Het IMWO heeft betrekking op woningen en woongebouwen als fysieke objecten, aangevuld met aan die objecten klevende gegevens over gebruik, eigendom, bestemming, etc. Het wordt gezien als een onderdeel van een breder model van de gebouwde omgeving. Daartoe worden de specifieke onderdelen over woningen en woongebouwen 'opgehangen' aan een algemene kapstok, een 'topmodel' voor de gebouwde omgeving.

Het model is primair ontwikkeld op basis van de internationale standaarden IFC en CityGML en de nationale standaarden NEN 2660 en NEN 3610. Voor specifieke onderdelen is gebruik gemaakt van specifieke standaarden. Zo wordt bijvoorbeeld als het gaat om zakelijke rechten uitgegaan van het informatiemodel Kadaster (IMKAD).

## Methodologie

### Richtlijnen

Voor de definities heeft de projectgroep IMWO richtlijnen opgesteld. Op 27 januari 2026 zijn die door de stuurgroep IMWO vastgesteld. Doelstelling ervan is het bieden van een praktische handreiking voor het toepassen van NL-SBB binnen IMWO. Bij eventuele tegenstrijdigheden heeft NL-SBB voorrang op basis van het principe pas-toe-of-leg-uit. De richtlijnen zijn hier <link> te vinden.

### Semantiek

Het IMWO is in deze fase een **semantisch** informatiemodel. Dat houdt in dat begrippen en relaties gebaseerd zijn op **betekenis**. Begrippen worden, uitgaande van een aantal niet nader te definiëren begrippen, gedefinieerd in termen van elkaar. Hierdoor worden de relaties bepaald door de definities. Er is bijvoorbeeld een relatie tussen een Bouwwerk en een Gebouw: ieder Gebouw is een Bouwwerk (generalisatie). Een Gebouw wordt gedefinieerd als een Bouwwerk, waaraan iets toegevoegd wordt (zoals dat het afsluitbaar is en een verblijfsfunctie heeft). 

Het op deze wijze definiëren is geen triviale zaak en de definities in de huidige versie van IMWO dienen als een eerste aanzet gezien te worden, waaraan nog veel denk- en doewerk besteed zal moeten worden om tot een nauwkeurige versie 2.0 te komen.

<figure id="fig-sem-driehoek">
  <img src="images/SemiotischeDriehoek.png" alt="Semiotische driehoek">
  <figcaption>Semiotische driehoek</figcaption>
</figure>

Een bekend beeld kan het belang van semantisch modelleren verduidelijken. In figuur ... is de zogenaamde ‘semiotische driehoek’ afgebeeld. Daarin betekenen de hoekpunten:
  -	dingen in de – fysieke of mentale – werkelijkheid, bijvoorbeeld een lantaarnpaal;
  -	begrippen van dingen in de werkelijkheid in ons hoofd, ontstaan door verwerking van observaties door de hersenen;
  -	vastlegging van begrippen in symbolen en termen, taalelementen, deze termen moeten de dingen in de werkelijkheid representeren.

De uitdaging van de informatiemodelleur is te komen tot een zo nauwkeurig mogelijke terminologie: het zo klein mogelijk maken van het verschil tussen begrippen en termen. Dit zal nooit voor 100% lukken: er is altijd een afweging tussen precisie en deugdelijkheid. Misschien ben je tevredener met een vaag beeld dat op een lantaarnpaal lijkt dan met een precies beeld dat helaas geen lantaarnpaal, maar een kapstok is!

### MIM

Het Metamodel voor Informatie Modellering ([MIM](https://docs.geostandaarden.nl/mim/mim/)) beschrijft de grondslagen voor informatiemodellering zodanig dat afstemming tussen en uitwisseling van informatiemodellen mogelijk wordt. MIM hanteert vier beschouwingsniveaus:
1.	Model van Begrippen (of ‘Begrippenkader’)

    Een model van begrippen wordt opgesteld voor gebruik door mensen, het bevat een lijst termen met definities van die termen en de relaties tussen de termen in natuurlijke taal. Doel is dat mensen binnen een domein elkaar beter begrijpen.
2.	Conceptueel informatiemodel

    Het conceptuele informatiemodel specificeert – nog steeds in natuurlijke taal - precies de betekenis van data en hun onderlinge betekenisrelaties, onafhankelijk van het ontwerp van en de implementatie in systemen. Dit informatiemodel dient als taal waarmee domeinexperts kunnen communiceren met informatieanalisten en verschaft een eenduidige interpretatie van die werkelijkheid ten behoeve van deze communicatie. Met conceptueel wordt niet bedoeld abstract of hoog over, de beschrijvingen van de informatie die beschikbaar is zijn heel precies en concreet.
3.	Logisch gegevensmodel

    Het logisch gegevensmodel is een model van de representatie van informatie over de werkelijkheid in digitale registraties en in de uitwisseling daartussen. Het slaat de brug tussen werkelijkheid en systemen maar beschrijft nog niet de implementatie in die systemen. Een dergelijk model wordt in een formele taal beschreven en wordt waar mogelijk gegenereerd vanuit het conceptueel model. Ook het logisch model is implementatieonafhankelijk en kan in meerdere technische modellen of formaten worden geïmplementeerd.
4.	Technisch gegevensmodel

    Het technisch gegevensmodel specificeert de structuur en eigenschappen van de technologie waarin de gegevens worden vastgelegd of uitgewisseld. Deze specificatie is sterk afhankelijk van de gebruikte opslagtechnologie zoals een specifieke database of de servicetechnologie zoals [xml], [gml], [SOAP], REST, [GeoJSON], [Linked-Data] e.d. De technische specificaties worden over het algemeen zoveel mogelijk gegenereerd uit het logisch informatiemodel. Deze specificaties worden opgesteld voor ‘machines’, te gebruiken door softwareontwikkelaars.

Het IMWO is primair een Conceptueel informatiemodel. Aan de specificatie van  objecttypen en relatiesoorten worden echter meer informele beschrijvingen toegevoegd, welke samen input voor een begrippenkader opleveren.

Het IMWO is nog geen volledig Conceptueel Informatiemodel: in deze fase is de beperking van de scope in de diepte gezocht teneinde een informatiemodel te verkrijgen dat het domein van de gebouwde woonomgeving zo breed mogelijk af te dekken. In concreto betekent dit dat het model zich beperkt tot specificatie van de objecttypen en de relaties ertussen en dat attributen van objecttypen en kardinaliteiten van relaties (betreft die relatie 0, 1 of veel objecttypen?) later nog uitgewerkt moeten worden.

### Federatief samenwerken - DSGO - DDD

<figure id="fig-dsgo">
  <img src="images/DSGO.png" alt="DSGO">
  <figcaption>DSGO</figcaption>
</figure>

Het Digitaal Stelsel Gebouwde Omgeving (DSGO) richt zich op partijen uit de gebouwde omgeving die in een digitale ketensamenwerking gegevens met elkaar uitwisselen Het DSGO is een federatief datastelsel (FDS): een stelsel van juridische, technische en semantische afspraken. gericht op het gemakkelijk, veilig en verantwoord kunnen delen en combineren van data tussen verschillende organisaties, zonder dat die data centraal hoeven te worden opgeslagen. De bronhouder blijft verantwoordelijk voor de beschikbaarheid en de kwaliteit van de data. Het is van belang dat deelnemers aan een FDS weten wat voor data beschikbaar zijn en of deze data in hun behoefte voorzien. Er is met andere woorden een datacatalogus nodig. Aan deze catalogus ligt een specificatie van de data ten grondslag, ofwel de te zoeken data zijn beschreven in een informatiemodel. Dit model is opgebouwd rond een semantische kern, waarin de relevante gegevens gespecificeerd worden als termen met betekenis. Deze termen worden gerelateerd aan de gegevensspecificaties van de bronnen, waarbij rekening gehouden wordt met betekenisverschillen: waar nodig worden gegevensspecificaties vertaald, immers in het ene domein wordt een andere taal gesproken dan in het andere domein. Zo heeft men het in het domein van de overheidsbasisregistratie over ‘panden’, terwijl men elders over ‘gebouwen’ spreekt. Veel panden zijn gebouwen, maar niet allemaal. Komt nog bij dat er in subdomeinen weer verschillend gedacht wordt over wat een gebouw is. Dus: je kunt (of jouw systeem kan) een beeld in je eigen taal vormen van mogelijke combinaties van beschikbare gegevens in verschillende bronnen. Na juridische en technische afhandeling kun je ze naar je toe halen. Op analoge wijze kun je gegevens in andere bronnen ter mutatie aanbieden. Op deze wijze worden de kernfuncties van de semantische laag van het DSGO – toevoegen van betekenis, standaardisatie, federatieve ontsluiting en interoperabiliteit – ingevuld.

NB het semantisch datamodel plus de vertalingen wordt als service aangeboden; het is geen verplichting. Op veel datadiensten is het model niet van toepassing, immers DSGO kan voor álle soorten data gebruikt worden.

Door toepassing van het canonieke model is ook domain driven design mogelijk: per domein kunnen eigen terminologieën en gegevensmodellen aangehouden worden. Deze worden via de centrale voorziening met elkaar compatible gemaakt.

In figuur ... wordt het voordeel van federatief samenwerken nog eens op een andere manier verduidelijkt: in een situatie zonder centrale vertaling moeten standaarden en andere schema's bilateraal aan elkaar gerelateerd worden. In een situatie mét centrale vertaling worden de gegevens per paar standaarden wel twee keer vertaald, maar over het geheel is het aantal vertalingen sterk gereduceerd (bij n schema's van orde n2 tot orde n)

<figure id="fig-federatief-samenwerken">
  <img src="FederatiefSamenwerken.png" alt="Federatief Samenwerken">
  <figcaption>Federatief Samenwerken</figcaption>
</figure>

### Mapping en matching

‘Mapping’ is letterlijk zoiets als het afbeelden van iets op iets anders (zoals het afbeelden van bebouwing op een landkaart). Als het gaat om informatiemodellen betreft dit het afbeelden van elementen van het ene model op het andere, ofwel het leggen van een – zo mogelijk – eenduidige relatie tussen objecttypen, attribuutsoorten en relaties in het ene model en het andere.

Een voorbeeld: in het ene model wordt een typologie van gebouwen opgezet door het objecttype Gebouw te voorzien van subtypen Woongebouw, Bijeenkomstgebouw, etc. In het andere model is er slechts één objecttype, Gebouw, dat een attribuutsoort gebouwType heeft, die verwijst naar een enumeratie van gebouwtypen als Woongebouw, Bijeenkomstgebouw, etc. De mapping van model 1 naar model 2 is dan dat ieder subtype van Gebouw uit model 1 verwijst naar een enumeratie-element in de enumeratie gebouwType van Gebouw uit model 2. In dit geval is de mapping symmetrisch, dus ook geldig in omgekeerde richting.

‘Matching’ gaat iets verder dan mapping, het voegt aan de mapping een oordeel toe, namelijk of het domein en het bereik van de afbeelding op elkaar ‘passen’. Zo kan het zijn dat er in één van beide typologieën bepaalde subtypes ontbreken. 
Voor de term ‘matching’ is ook de term ‘alignment’ (afstemming, harmonisatie) in zwang. De connotatie is wellicht iets anders: vaak wordt ‘wishful thinking’ toegepast door gelijkstelling van termen met ongeveer dezelfde betekenis. Dat is zeer gevaarlijk en de oorzaak van veel storingen in het huidige digitale tijdperk, waarin de toepassing van koppelingen op basis van ‘ongeveer’ leidt tot oncontroleerbare softwarekluwens. 

Een mapping is de basis voor een transformatie Als het gaat om informatiemodellen wordt een bredere interpretatie gehanteerd: het gaat om het transformeren van het ene model in het andere, zowel syntactisch als semantisch. Syntactische transformatie wordt ook wel conversie genoemd, semantische transformatie wordt ook wel translatie genoemd. Aan een transformatie kan een proces toegevoegd worden, dat de vertaling geautomatiseerd verzorgt.

Naast matching is er een andere vorm van interoperabiliteitsverhoging, de uitbreiding (‘extension’) van informatiemodellen (c.q. ontologieën). Daarbij wordt een element uit een model gerelateerd aan een element uit een ander model. Bijvoorbeeld kan het Objecttype Gebouw in een zekere gebouwregistratie, waarin per gebouw alle ruimten worden benoemd met hun functie, uitgebreid worden met de oppervlakte per ruimte. Het moge duidelijk zijn dat er vóór deze afstemming een mapping en een matching dienen plaats te vinden.

Voorbeeld van een mapping

| Kenmerk          | Model 1           | Mapping                         | IMWO              | Mapping                | Model 2 |
| ---------------- | ----------------- | ------------------------------- | ----------------- | ---------------------- | ------- |
| taal             | Space             | Space ↔ Ruimte                  | Ruimte            | Ruimte ↔ Ruimte        | Ruimte  |
| dimensionaliteit | 2D of 3D          | 2D → 3D (z=0), 3D ↔ 3D          | 3D                | 3D ↔ 3D                | 3D      |
| afbakening       | reëel of virtueel | reëel/virtueel ↔ reëel/virtueel | reëel of virtueel | reëel/virtueel ← reëel | reëel   |


De verzameling triples, die gezamenlijk een mapping (in de tabel de elementen van de kolom ‘mapping’) tussen twee modellen representeren wordt ‘linkset’ genoemd.

In het voorbeeld is te zien dat er informatie verloren kan gaan: in model 2 worden alleen reëel afgebakende ruimten geregistreerd. In IMWO en via IMWO in model 1 is iedere reëel afgebakende ruimte ‘reëel of virtueel’ afgebakend, dus je weet niet meer hoe een ruimte is afgebakend, terwijl bekend was dat de afbakening reëel was. Dit is op twee manieren op te lossen:
1.	IMWO zodanig uitbreiden dat duidelijk is wanneer een ruimte reëel, virtueel of ‘virtueel of reëel’(‘onbekend’) is afgebakend
2.	een domeinregistratie die daar behoefte aan heeft uitbreiden met een kenmerk ‘reëel’ voor de ruimten die vanuit model 2 komen.

Los hiervan bevat model 2 überhaupt geen virtueel afgebakende ruimten, dus die kunnen in ieder geval niet gedeeld worden. Wellicht is het handig aan ruimten die uit model 2 komen het metagegeven ‘reëel’ mee te geven.

Op het niveau van het begrippenkader mogen de relaties zwak zijn, op het niveau van het conceptuele en zeker het logische model dienen ze sterk te zijn. Pragmatiek is op dat niveau uit den boze.

Om betrouwbare koppelingen te realiseren dienen er in ieder geval adequate metadata te worden toegevoegd.

Bij de uitwerking kan voortgebouwd worden op voorwerk van [CROW](https://docs.crow.nl/ontology-alignment/whitepaper/). Verder zouden AI tools ingezet kunnen worden om mappings te analyseren en transformaties te definiëren. Hiertoe is nader onderzoek en experiment nodig.

### Canoniek informatiemodel

Een canoniek informatiemodel fungeert als een centraal model, waarnaar gegevens uit verschillende domeinen vertaald worden en vice versa. Hierdoor kan er communicatie tussen alle domeinen plaatsvinden zonder koppeling van elk domein aan elk ander domein. Belangrijkste kenmerken en doelen:

- Standaardisatie: Het definieert een vaste structuur, formaat en betekenis (semantiek) van objecttypen en hun relaties, onafhankelijk van een specifieke applicatie.
- Vermindering van complexiteit: In plaats van 'point-to-point'-integraties (waarbij elk systeem met elk ander systeem praat), vertaalt elk systeem zijn eigen data naar het centrale, canonieke formaat.
- Eén 'bron van waarheid': Het creëert een uniforme weergave over een compleet domein, hetgeen zorgt voor consistente communicatie.
- Herbruikbaarheid: de gespecificeerrde objecttypen zijn herbruikbaar en generiek. 

Voordelen

- Makkelijker schalen: Nieuwe systemen toevoegen is eenvoudiger, omdat ze alleen hoeven te koppelen aan het centrale model.
- Consistentie: Minder fouten door verschillende definities van dezelfde data.
- Onderhoudbaarheid: Wijzigingen in één systeem hebben minder impact op andere systemen. 
    
## Methode

De ontwikkeling van het IMWO vindt plaats in een iteratief proces van:
-	creatie: ontwikkeling van (deel-)modellen; daarbij kunnen uitwerkingen, bijvoorbeeld in de vorm van BIM-modellen beproefd worden;
-	verificatie: nagaan of uitwerkingen (bijvoorbeeld BIM-modellen) kunnen voldoen aan het informatiemodel;
-	validatie: nagaan of het model daadwerkelijk voldoet aan de behoeften van de gebruikers, enerzijds businessadviseurs, anderzijds IT-specialisten; dit kan leiden tot aanpassingen van het model en de werkwijze, maar vindt vooral aan het eind plaats in een marktbrede review.

### Opbouw van het informatiemodel

IMWO is opgebouwd deelmodellen op drie abstractieniveaus
1. Topmodel
2. Bouwwerken
3. Woonobjecten

De eerste twee niveaus betreffen de gebouwde omgeving als geheel en hebben ten doel de woonobjecten te zien als onderdeel van een groter geheel. Omgekeerd kunnen het Topmodel en het model Bouwwerken later in andere richtingen uitgebouwd worden, met name richting utiliteitsbouw, infrastructuur en  ruimten. Ook is er een uitbouw mogelijk richting aspectmodellen, denk aan modellen voor installaties, systems engineering en energie. 

<figure id="fig-drieniveaus" class="ol-figure-small">
  <img src="images/drieNiveaus.png" alt="drieNiveaus">
  <figcaption>drie niveaus</figcaption>
</figure>

In de diagrammen wordt de volgende legenda gehanteerd:
<figure id="fig-legenda" class="ol-figure-smallx">
  <img src="images/Legenda.png" alt="Legenda">
  <figcaption>Legenda</figcaption>
</figure>

## Inventarisatie

De volgende schema’s zijn betrokken in de inventarisatie:

|  |  |  |  |
| :--- | :--- | :--- | :--- |
| Aedes Informatiemodel Vastgoed 0.9 | Geometrie  | Inspire                       | NEN3610                           |
| Bbl                                | GeoSPARQL  | ISO 15288                     | NEN-EN 15221-6                    |
| BIM Basis ILS                      | GGM        | ISO 19117                     | NEN-EN-15804                      |
| BIM Legal                          | GIR        | Ketenstandaard (KIS?)         | NLBE-SfB                          |
| BOT ontology                       | IDS        | LADM                          | NPR 4660                          |
| BRICK                              | IFC        | LandInfra                     | OmniClass                         |
| CPR-2024                           | ILS O&E    | LVG                           | OTL B&U                           |
| CIM                                | ILS Spaces | materiaalpaspoort             | Paspoorten: CB23, GABC NEN18216 … |
| CIMOW                              | ILS Woco   | meetinstructies voor taxaties |                                   |
| CityGML                            | IMBAG      | MiniBIM                       | RVB IM                            |
| COBIE                              | IMBOR      | MiniGIM                       | SAREF                             |
| CORA                               | IMGEO      | FM-standaarden                | STABU                             |
| DBL                                | IMIBRO     | NAA.KT                        | Unuclass                          |
| DiCon                              | IMKAD      | NEN2580                       | Unieke ObjectCodering             |
| DICO                               | IMX-Geo    | NEN2660-1                     | VERA                              |
| Dossier Bevoegd Gezag              | IMVG       | NEN2660-2                     | VIVET                             |
| ETIM                               | IMWOZ      | NEN2699                       | VTH-flo                           |
| GEBORA 1.0                         | IndoorGML  | NEN2767                       | Wkb-dossier                       |
|                                    |            |                               | WWS                               |


***Bijlage 1*** bevat per standaard een korte beschrijving.

***Bijlage 2*** bevat (delen van) geïnventariseerde informatiemodellen als UML-bestand en bijbehorende definities.

## Globaal model

Het informatiemodel wordt behandeld in hoofdstuk 5. Voorafgaaande daaraan wordt in dit hoofdstuk een globaal overzicht verschaft. Daarin wordt eerst een globaal overzicht gegevens van de belangrijkste objecttypen en hun relaties, gevolgd door een iets uitgebreider overzicht van de drie abstractieniveaus van IMWO: (1) Topmodel, (2) Model Bouwwerken en (3) Model Woonobjecten.

<figure id="fig-indelingimwobeschrijving" class="ol-figure-small">
  <img src="images/ImwoIndeling.png" alt="IndelingImwoBeschrijving">
  <figcaption>Indeling beschrijving IMWO</figcaption>
</figure>

### Globaal globaal model

<figure id="fig-alt-text">
  <img src="images/IMWO-GlobaalModel.png" alt="alt text">
  <figcaption>globaal globaal model text</figcaption>
</figure>

Het IMWO beschrijft de woningen en woongebouwen op drie abstractieniveaus:
1. Fysieke objecten

   Woningen en woongebouwen zijn fysieke objecten. Daarop kunnen een aantal algemene kenmerken en relaties gedefinieerd worden, die verder als patroon voor alle fysieke objecten toegepast kunnen worden. Zo heeft een fysiek object een geometrie, waarmee alle specifieke fysieke objecten, zoals woningen en woongebouwen, een geometrie hebben.
2. Bouwwerken

   Woongebouwen zijn gebouwen en ieder gebouw is een bouwwerk. Zoals ieder fysiek object heeft een bouwwerk een ruimtelijke component, het geheel van ruimten, die de functie van het bouwwerk mogelijk maken, en een reële component, het samenstel van bouwdelen, installaties en inventaris, dat ervoor zorgt, dat het bouwwerk op de plaats, waar het staat als constructief zelfstandig object blijft staan, zodat de functie ervan ondersteund blijft worden. Iedere bouwwerkcomponent kan onderverdeeld worden in bouwwerkcomponenten totdat een elementaire bouwwerkcomponent bereikt is.

3. Woonobjecten

   Woonobjecten zijn (BAG-)verblijfsobjecten met een woonfunctie. Het kunnen zelfstandige woningen zijn dan wel wooneenheden in een woongebouw.Een woonobject bestaat uit woonobjectruimten.
   

### Fysieke objecten

<figure id="fig-alt-text">
  <img src="images/IMWO-FysiekeObjecten.png" alt="alt text">
  <figcaption>globaal model Fysieke objecten</figcaption>
</figure>

Alle fysieke objecten hebben een aantal kenmerken: ze hebben een functie, een geometrie en een toestand, en ze bevatten materie. In de gebouwde omgeving worden fysieke objecten altijd als een eenheid gezien van een ruimtelijk object en een reëel object. Als ruimtelijk object biedt het ruimte aan functies als verblijven en verplaatsen van mensen, goederen en voertuigen, als reëel object verzorgt het de begrenzing van ruimtelijke objecten met 'harde' materie. Als we deze twee typen fysieke objecten relateren aan het aardoppervlak spreken we van ruimtelijke resp. reële geo-objecten.

De fysieke objecten kunnen diverse onderlinge relaties hebben:
-	plan/realisatie
- deel/geheel ((de)compositie)
- raakvlak
- topologie (onderlinge nabijheid/ bereikbaarheid)
- functioneel/technisch (implementatie)

### Bouwwerken

<figure id="fig-alt-text">
  <img src="images/IMWO-Bouwwerken.png" alt="alt text">
  <figcaption>globaal model Bouwwerken</figcaption>
</figure>

Een bouwwerk is een gebouwd fysiek geo-object en bedoeld om ter plaatse te functioneren. Een bouwwerk ligt op een terrein. Omdat een bouwwerk een fysiek object is valt het ook uiteen in een ruimtelijke en een reële component. Deze componenten kunnen weer verder gedecomponeerd worden. Dit leidt tot ruimtelijke en reële subtypen. De reële componenten worden onderscheiden in bouwcomponenten (balken, vloeren, etc.), installatiecomponenten en (vaste) inventariscomponenten.

De bouwwerkcomponenten hebben onderlinge raakvlakken. Dit betreft uiteraard de begrenzing van ruimten door reële objecten zoals wanden en vloeren, maar ook kunnen ruimten onderling een ('virtueel') raakvlak hebben en hetzelfde geldt voor reële componenten (zoals een afdekking op een vloer). 

Een gebouw is een bouwwerk met enkele bijzondere kenmerken, en wel: het is overdekt en geheel of gedeeltelijk met wanden omsloten, betreedbaar en afsluitbaar, primair bedoeld voor het bieden van een afgeschermde omgeving voor het verblijf, gebruik, onderbrengen of beschermen van mensen, dieren of voorwerpen, of voor de productie van goederen.

### Woonobjecten

<figure id="fig-alt-text">
  <img src="images/IMWO-woonobjecten.png" alt="alt text">
  <figcaption>globaal model woonobjecten</figcaption>
</figure>

Een woongebouw is een gebouw, dat primair geschikt is voor woningen en/of wooneenheden. Het bevat woonobjecten, verblijfsobjecten met een woonfunctie. Er worden twee soorten woonobjecten onderscheiden: woningen (zelfstandige woonobjecten) en wooneenhedenobjecten (een zelfstandig geheel, bestaande uit onzelfstandige wooneenheden). 

Een woonobject is opgebouwd uit ruimtelijke componenten, te onderscheiden naar verblijfsruimten, verkeersruimten, technische ruimten en functieruimten (zoals bergruimten).

## Model

### Inleiding

***Toelichting***

In een tiental submodellen wordt hierna het informatiemodel weergegeven in een diagram en toegelicht. Per objecttype is er een specifcatie plus een beschrijving van de relaties ervan met andere objecttypen.

De objecttypespecificatie ziet er als volgt uit:

| Onderwerp | Specificatie |
| :----- | :----- |
| Schema | Aanduiding van de standaard of het model. In dit geval is dat altijd ‘IMWO’ |
| Model | Subschema van IMWO |
| Identificatie | <url>..... |
| Term | Naam van de term |
| Formele definitie | Exacte beschrijving van het begrip, waarbij alle termen, behalve de niet nader gedefinieerde, worden gespecificeerd in een formele relatie tot andere termen |
| Bron | Bron, waarop de formele definitie gebaseerd is |
| Eigenaar | Eigenaar van de formele definitie, in dit geval steeds digiGO |
| Synoniemen | Eventuele synoniemen |
| Begrip | Naam van het concept zoals dat in de praktijk gebruikt wordt |
| Begripsdefinitie | Informele definitie (door mensen redelijkerwijs te bevatten definitie) |
| Bronterm | Term, zoals in de bron gehanteerd |
| Brondefinitie | Definitie, zoals in de bron gebruikt |
| Bron | Bron waarop de brondfinitie gebaseerd is |
| Eigenaar | Veronderstelde eigenaar van de brondefinitie. |
| Bijzonderheden | Bijzonderheden, die bij de bron vermeld zijn|
| Voorbeelden | Voorbeelden bij de definitie van IMWO|
| Commentaar | Commentaar en vraagpunten vanuit IMWO |

De relaties worden als volgt gespecificeerd:

| Term | Relatiesoort | Relatienaam | Model | Objecttype| 
| :--- | :--- | :--- | :--- | :--- | 
| naam van het objecttype | generalisatie, aggregatie, etc. | nadere specificatie | indien van toepassing: ander submodel of ander schema | naam van het gerelateerd objecttype |
| | | | | |

NB Vaak komt het voor dat een objecttype in IMWO gezien zou kunnen worden als een subtype of equivalentietype van een objecttype in een standaard. Bijvoorbeeld zou een fysiek object in IMWO een subtype- of equivalentierelatie kunnen hebben met een fysiek object in NEN 2660. Dit is niet gebeurd, omdat eerst in aangetoond moet worden dat het inderdaad om precies dezelfde objecttypen gaat. Bovendien willen we de vrijheid hebben nuanceringen aan te brengen, gecombineerd met geschikte mappings.

### Topmodel

<figure id="fig-topmodel" class="ol-figure-large">
  <img src="images/Topmodel.png" alt="Topmodel">
  <figcaption>Topmodel</figcaption>
</figure>

De top is hoofdzakelijk gebaseerd op de ‘regels voor informatiemodellering van de gebouwde omgeving’ \[NEN 2660-1\] en \[NEN 2660-2\], alsmede het basismodel geo-informatie \[NEN 3610\|. Er wordt een aantal abstracte begrippen gedefinieerd, die wel heel algemeen zijn, maar toch belangrijk, omdat ze als patroon toegepast worden bij concrete objecttypen. Zo kan een gebouw – bijvoorbeeld om vluchtroutes te bepalen – gepresenteerd én geregistreerd worden als een netwerk, een topologisch model.

<figure id="fig-voorbeeld-indoor-gml">
  <img src="VoorbeeldIndoorGml.png" alt="Voorbeeld Indoor GML">
  <figcaption>Voorbeeld Indoor GML _Bron: OGC: IndoorGML v 1.1, 2020_</figcaption>
</figure>

<figuur Topmodel>

In het topmodel staat staat het objecttype FysiekObject centraal. Een FysiekObject is een verbijzondering van het algemenere objecttype Entiteit, waarvan het belangrijk is dat die een aantal specifieke relaties kan hebben met andere Entiteit, met name de transitie van functionele naar technische entiteit.

In het kader van de gebouwde omgeving wordt (in NEN 2660) onderscheid gemaakt tussen functionele en technische entiteiten. Een functionele entiteit wordt beschreven in termen van haar werking, haar functies, het WAT. Deze wordt geïmplementeerd door één of meer technische entiteiten, die beschreven worden in termen van de interne structuur, het HOE. De tweeling functionele entiteit-technische entiteit lijkt erg op een tweeling uit de filosofie, waarin de essentie en de existentie van dingen tegenover elkaar gesteld worden.

Een ruimte heeft op grond van het bovenstaande een functionele en een technische component. Je kunt ook zeggen: je hebt functionele ruimten en technische ruimten, waarbij de functionele ruimten rollen spelen van de technische ruimten. Functionele ruimten vervullen functies. Een voorbeeld:

•	functionele ruimte wachtkamer k in gebouw g

•	voertUit: functie wachten (of wellicht beter:’wachten faciliteren’)

•	isRolVan: technische ruimte kamer k in gebouw g; isRolVan (of: isGespeeldDoor) is synomiem met isGeïmplementeerdDoor 

Er zijn verschillende typen functies, zoals:

•	gebruiksdoel

•	registratieve functie

•	juridische functie

•	geografische functie.

Het begrip functie kan dus breder opgevat worden dan alleen gebruiksdoel. Een functie van een kadastraal perceel zou bijvoorbeeld kunnen zijn: ‘zakelijke rechten faciliteren’. De functie van een WOZ-object: ‘belastingheffing faciliteren’.

Het is wenselijk voor IMWO en beter nog: voor de gebouwde omgeving, een meer uitgebreide functietaxonomie uit te werken. Hiernaast kunnen ook functiedecomposities voorkomen, immers er zijn ook samengestelde functies.

**Hamburgermodel**

Een technische entiteit is een ‘functievervuller’. Dit wordt toegepast in de GARM Hamburgermodel–methodiek (GARM: General AEC Reference Model; AEC: Architecture, Engineering, and Construction), ontwikkeld door Wim Gielingh. In die methodiek wordt een object (Product Definition Unit (PDU)) gedefinieerd door zowel functionele eisen als technische oplossingen. Zo’n object kan vergeleken worden met een hamburger, met een functionele top en een technische bodem. In het functionele object worden functionele, technische en operationele eisen gekoppeld die nodig zijn om te komen tot een keuze (bijvoorbeeld door afweging) voor een technische oplossing. Een technische oplossing heeft kenmerken die getoetst moeten worden aan de eisen van het functionele object. Een technische oplossing kan op haar beurt weer (met decompositie) worden opgedeeld in nieuwe functionele objecten.  Het hamburgermodel speelt een belangrijke rol in de systems engineeringmethodiek. [Leidraad SE 2013] 

<figure id="fig-alt-text">
  <img src="images/Hamburgermodel.png" alt="alt text">
  <figcaption>Hamburgermodel</figcaption>
</figure>

In de gebouwde omgeving worden fysieke objecten altijd als een eenheid gezien van een ruimtelijk object en een reëel object. Als ruimtelijk object biedt het ruimte aan functies als verblijven en verplaatsen van mensen, goederen en voertuigen, als reëel object verzorgt het de begrenzing van ruimtelijke objecten met 'harde' materie.

Er wordt nadrukkelijk een onderscheid gemaakt tussen fysieke objecten sec en geo-objecten: een GeoObject wordt gezien als een FysiekObject met een vaste plaats ten opzichte van het aardoppervlak. Hiermee komen we in het domein van de geo-informatie, waarvoor in Nederland het basismodel voor geo-informatie (NEN 3610) de centrale standaard is. Hieraan is het IMWO-topmodel dan ook gekoppeld.  

### Objecttypen en relaties

### Bouwwerken

<figure id="fig-bouwwerken" class="ol-figure-large">
  <img src="images/Bouwwerken.png" alt="Bouwwerken">
  <figcaption>Bouwwerken</figcaption>
</figure>


Een Bouwwerk wordt gedefinieerd als een door mensen vervaardigd ruimtelijk afgebakend fysiek samenhangend constructief zelfstandig object, verbonden met en steun vindend in de grond, samengesteld uit constructieve onderdelen, aangevuld met bouwkundige en/of installatietechnische onderdelen met een ter plaatse uit te oefenen functie. 

**Toelichting**

- ‘door mensen vervaardigd’, afgeleid uit diverse definities; dit kenmerk sluit natuurlijke objecten uit.

-	‘ruimtelijk afgebakend’: dit is wat in wetenschappelijke literatuur ‘discreet’ genoemd wordt

-	‘samenhangend’ (ook wel: ‘aaneengesloten’): de vorm bestaat uit één geheel. Je kunt elk punt in de figuur bereiken vanuit elk ander punt zonder de figuur te verlaten. [Wikipedia]

-	‘constructief zelfstandig’: het bouwwerk blijft binnen bepaalde normen onder alle omstandigheden in stand

-	Het in diverse Nederlandse definities voorkomende kenmerk ‘van enige omvang’ is weggelaten. Immers: wat is de minimale omvang? Een stenen in de grond verankerd bankje in een plantsoen kun je gevoeglijk een bouwwerk noemen.

-	‘verbonden met en steun vindend in de grond’: dit sluit verplaatsbare constructies uit; in Bbl en NEN 3610 staat "…direct of indirect met de bodem verbonden of daarin steun vindt". De ‘of’ is in een ‘en’ veranderd, immers een constructie die zonder steun met de grond is verbonden zou toch geen bouwwerk genoemd mogen worden. En de term ‘bodem’ is door ‘grond’ vervangen, omdat met ‘bodem’ veelal alleen de toplaag van de grond wordt bedoeld. Juist de ondergrond is natuurlijk van belang voor de fundering.

-	‘samengesteld uit bouwkundige en constructieve en installatietechnische onderdelen’: 

    •	Bouwkundige onderdelen zijn onderdelen die het bouwwerk vormgeven, indelen, beschermen of bruikbaar maken, maar niet primair bedoeld zijn om het bouwwerk te dragen of stabiliteit te geven, zoals binnenwanden die geen dragende functie hebben, kozijnen en binnen- of buitendeuren. De functie daarvan is gebruik, comfort, indeling, afwerking, uitstraling

    •	Constructieve onderdelen: dit zijn onderdelen die belastingen moeten opnemen en afvoeren naar de fundering of andere dragende elementen. Ze zorgen voor veiligheid, sterkte en stabiliteit. Voorbeelden zijn fundering en dragende wanden. Functie: het bouwwerk overeind houden en zorgen dat het veilig is.
    •	Installatietechnische onderdelen: dat zijn de met de bouwkundige en of constructieve onderdelen verbonden installaties.
-	‘met een ter plaatse uit te oefenen functie’: dit kenmerk komt in bijna alle geïnventariseerde definities voor (in het algemeen als ‘bedoeld om ter plaatse te functioneren’).

-	weggelaten: ’Of een ruimtelijk af te bakenen deel daarvan’; dit zou modellering van een deel van een groter bouwwerk (vleugel, segment, bouwdeel) als afzonderlijk bouwwerk mogelijk maken; een nieuwe term is dan toch te prefereren, bijvoorbeeld ‘deelbouwwerk’, en wel omdat de zelfstandigheid van het object een essentieel kenmerk van een bouwwerk is.

Belangrijke uitwerkingen in het submodel Bouwwerken zijn verder:

- bepaaling van de geometrie en de bepaling van oppervlake en inhoud daarvan op basis van NEN 2580;
- de rubricering van de reële BouwwerkComponenten tot BouwwComponenten, InsgtallatieComponenten en InventarisComponenten
- de decompositie van het Bouwwerk in  Ruimtelijke Bouwwerk Componenten. De uitwerking daarvan gebeurt alleen voor woonobjecten (hierna). Bijzondere Ruimtelijke Componenten  zijn Verdiepingen en BrandCompartimenten.
- en uiteraard de specialisatie naar Gebouw.

Een Gebouw wordt gedefinieerd als een overdekt en geheel of gedeeltelijk met wanden omsloten, betreedbaar en afsluitbaar  Bouwwerk, primair bedoeld voor het bieden van een afgeschermde omgeving voor het verblijf, gebruik, onderbrengen of beschermen van mensen, dieren of voorwerpen, of voor de productie van goederen.

Toelichting:

-	Overdekt en omsloten: in lijn met Aedes IMV, NEN 3610 en BAG varianten.

-	Betreedbaar en afsluitbaar: overgenomen uit de BAG/Pand definitie (IMBAG).

-	Doelgericht gebruik: overeenstemming tussen alle bronnen (verblijf, opslag, productie, bescherming).

Voorbeelden zijn: woonhuis, appartementsgebouw, kantoorgebouw, school, ziekenhuis, winkelpand, fabriek, schuur, loods.

### Bouwcomponenten

<figure id="fig-bouwcomponenten" class="ol-figure-large">
  <img src="images/Bouwcomponenten.png" alt="Bouwcomponenten">
  <figcaption>Bouwcomponenten</figcaption>
</figure>

De BouwComponenten worden in 14 klassen verdeeld. Daarbij wordt nauw aangesloten bij de ILS O&E en IFC.

### Woonobjecten

<figure id="fig-woonobjecten" class="ol-figure-large">
  <img src="images/Woonobjecten.png" alt="Woonobjecten">
  <figcaption>Woonobjecten</figcaption>
</figure>


Een Woongebouw wordt gedefinieerd als Gebouw dat primair geschikt is voor woningen en/of wooneenheden. Een grondgebonden woning wordt veelal niet als een woongebouw gezien. Om die reden wordt een woonobject direct als onderdeel van een Bouwwerk gespecificeerd. 

Een WoonObject is een Verblijfsobject (á la BAG) met een woonfunctie. Er worden twee soorten woonobjecten onderscheiden: woningen (zelfstandige woonobjecten) en wooneenhedenobjecten (een zelfstandig geheel, bestaande uit onzelfstandige wooneenheden). De Woningen worden verder onderverdeeld in een aantal subtypen. Er bestaan diverse typologieën, waarvan het gewenst is deze nader te analyseren en vervolgens te trachten op een systematische wijze tot een eenduidige typologie te komen.

Voor de Wooneenheden is geen typologie opgesteld, maar ze zijn gerubriceerd naar doelgroep.

Een woonobject is opgebouwd uit WoonObjectRuimten, te onderscheiden naar BuitenRuimten en BinnerRuimten, die verder verdeeld worden in Verblijfsruimten, Bedruimten, Verkeersruimten, TechnischeRuimten, Functieruimten, SanitaireRuimten en LegeRuimten. Deze ruimtetypen kunnen worden tot Bbl-gebieden.

Een WoonObjectRuimte heeft een Functie (in de BAG een 'gebruiksdoel' en in het Bbl 'bouwkundige bestemming' genoemd). Deze kan afwijken van de feitelijke Functie (in de BAG: het 'geconstateerde gebruiksdoel'), vandaar dat er twee relaties tussen WoonObjectRuimte en Functie opgenomen zijn.

### Woonobjectruimten

<figure id="fig-woonobjectruimten" class="ol-figure-large">
  <img src="images/Woonobjectruimten.png" alt="Woonobjectruimten">
  <figcaption>Woonobjectruimten</figcaption>
</figure>

De WoonObjectRuimten zijn verder geklassificeerd. Het gaat hier om een voorlopige oplossing, die aansluit bij ILS-Woco en MiniBIM, maar die nog niet geheel en al consistent is.

### Installaties

<figure id="fig-installaties" class="ol-figure-large">
  <img src="images/Installaties.png" alt="Installaties">
  <figcaption>Installaties</figcaption>
</figure>


Het submodel voorInstallaties sluit aan bij het Gebouwinstallatieregister (GIR) en de daarin toegepaste standaarden. Verder is het objecttype Nutsaansluiting opgenomen om een relatie te leggen met de NutsSystemen. 

De Installaties zijn verder geklassificeerd volgens de NL-SfB-standaard.

### Slimme woningen en bouwwerken

<figure id="fig-slimmewoning" class="ol-figure-large">
  <img src="images/SlimmeWoning.png" alt="SlimmeWoning">
  <figcaption>SlimmeWoning</figcaption>
</figure>

Het submodel Slimme woning/slim bouwwerk sluit aan bij de Saref-standaard.

### Binnenruimtenetwerk

<figure id="fig-binnenruimtenetwerk" class="ol-figure-large">
  <img src="images/Binnenruimtenetwerk.png" alt="Binnenruimtenetwerk">
  <figcaption>Binnenruimtenetwerk</figcaption>
</figure>

Het subnodel Binnenruimtenetwerk sluit aan bij IndoorGML 2.0. Het gaat hier om een eerste schets, die nog getoets moet worden en waarbij de aansluiting bij IndoorGML nog gespeicificeerd moet worden.
Oorzaak: in eerste instantie was alleen IndoorGML 1.0 bekend, en dat wijkt af van IndoorGML 2.0.

### Juridische objecten

<figure id="fig-juridische-objecten" class="ol-figure-large">
  <img src="images/Juridische objecten.png" alt="Juridische objecten">
  <figcaption>Juridische objecten</figcaption>
</figure>

In het submodel Juridische objecten wordt vooral verwezen naar objecttypen in de relevante standaarden. Dit submodel is van belang voor de ontwikkeling van het LVG, dat gebaseerd zal worden op een view op het IMWO.

## Inhoud van model: objecttypen en relaties

[[ol:include id="imwo_modellen"]]

## Beheer, toepassing en onderhoud

- Het IMWO komt onder beheer van de GEBORA product-owner
Stuurgroep IMWO

- Permanente werkgroep IMWO

- Aanhakend bij Architectuurboard GEBORA?

- Implementatie m.b.v projecten/ Beleidsmaatregelen/digiDeals

## vervolgaanpak

Nog uit te werken punten:
* standaardisatie conform BOMOS?
* technische-organisatorische inrichting 
* ontwikkel- en testomgeving opzetten en beheren
* implementatie m.b.v. DSGO (implementatie IMWO als canoniek model)
* onderzoek van alternatieve implementatie-opties
* verdere ontwikkeling van het informatiemodel (begrippenkader en ontologie) door verbreding tot uiteindelijk het Innformatiemodel Gebouwde Omgeving IMGO; Europese opschaling
* specifieke aansluitingen:
  * LVG
    * logisch model
    * implementatie (DSGO)
  * ILS'n
  * miniBIM en miniGIM
  * gemeenten: IMIBRO, GGM
  * OTL'n 
* verder onderzoek en verdere ontwikkeling
  * woning als 'system of systems'
  * parametrisch ontwerpen
  * toestanden en gebeurtenissen
  * inventaris
  * Facility Management
  * vergunningverlening
  * digitale paspoorten
  * functietaxonomie
  * systematisering van klassificaties
* inbreng leveren bij alla Beleidsmaatregelen (als semantische laag)

## Bronnen
| Referentie          | Titel, auteur, datum                                                                                                                                                                                                                | link                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Aedes-IMV]         | AEDES Informatiemodel vastgoed, versie 0.9, 2025?                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Bbl]               | Besluit bouwwerken leefomgeving https://wetten.overheid.nl/BWBR0041297                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Bbl-Praktijk]      | Ministerie van BZK,'Praktijkboek Besluit bouwwerken leefomgeving', Vakmedianet, 2001                                                                                                                                                | https://open.overheid.nl/overheid/openbaarmakingen/api/v0/attachment/ronl-1a2b0036-d4b1-4f7d-89b8-149fb26976c2                                                                                                                                                                                                                                                                                                                                                                         |
| [BIM Basis ILS]     | Beheerorganisatie BIM Basis ILS, 'BIM Basis ILS'                                                                                                                                                                                    |  https://www.digigo.nu/ilsen-en-richtlijnen/bim-basis-ils/                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [BIM Legal]         | Stichting platform BIM Legal, 'BIM Legal afsprakenset v1.0', 2025                                                                                                                                                                   | https://bimlegal.nl/wp-content/uploads/2026/01/2025-Afsprakenset-BIM-Legal-v1.1.pdf                                                                                                                                                                                                                                                                                                                                                                                                    |
| [BOT]               | Linked Building Data Community Group'Building Topology Ontology', 2021                                                                                                                                                              | https://w3c-lbd-cg.github.io/bot/                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [BRK]               | Kadaster,'Catalogus Basisregistratie Kadaster', 10-12-2020                                                                                                                                                                          | https://www.kadaster.nl/-/catalogus-brk                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [CBS]               | Begrippen                                                                                                                                                                                                                           | https://www.cbs.nl/nl-nl/onze-diensten/methoden/begrippen                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [CB23-lexicon]      | Platform CB'23,'Lexicon Circulaire bouw', versie 3.0, 24 april 2024                                                                                                                                                                 | https://platformcb23.nl/                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [CB23-pp]           | Platform CB'23,'Leidraad Paspoorten voor de bouw. Deel 1+2', juni 2023 (Public Draft)                                                                                                                                               | https://platformcb23.nl/                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [CIMOW]             | Geonovum,'Conceptueel Informatiemodel Omgevingswet', 9 januar 2026                                                                                                                                                                  | https://docs.geostandaarden.nl/dso/dso-cim-ow/                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [CityGML]           | OGC City Geography Markup Language (CityGML) Part 1: Conceptual Model Standard                                                                                                                                                      | https://docs.ogc.org/is/20-010/20-010.html#toc0                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [COBIE]             |                                                                                                                                                                                                                                     | https://nibs.org/nbims/v3/cobie/                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [digiGO e.a. 2025]  | Ketenstandaard, digiGO, Geonovum, CROW,'Naar een betrouwbaar <br>virtueel digitaal bouwwerkdossier', 2025?                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [EMSO]              | Geonovum,'DiS Geo : Eisen aan model samenhangende objectenregistratie', 16 juni 2021                                                                                                                                                | https://docs.geostandaarden.nl/disgeo/emso/                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [EMSO]              | Geonovum,'DiS Geo : Eisen aan model samenhangende objectenregistratie', Versie ter vaststelling 16 juni 2021                                                                                                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [EP-Online]         | Rijksoverheid,'EP-online'; officiële landelijke database met energielabels en energieprestatie-indicatoren                                                                                                                          | www.ep-online.nl                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [ETIM]              | ETIM International                                                                                                                                                                                                                  | https://www.etim-international.com/                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [Gebora]            | digiGO: 'GEBORA: GEBouwde Omgeving Referentie Architectuur', https://www.digigo.nu/wat-is-gebora/                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [GeboraCim 2025]    | digiGO,’GEBORA Conceptueel informatiemodel’, versie 1.0, 30-04-2025: https://www.digigo.nu/wp-content/uploads/2025/06/GEBORA-Conceptueel-Informatiemodel-1.0-ter-publicatie.pdf                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [GeoSemantiek 2022] | Geonovum, 'Whitepaper semantische interoperabiliteit van geo-informatie', 2022                                                                                                                                                      | https://geonovum.github.io/semigeo/                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [GGM]               | Gemeentelijk Gegevensmodel                                                                                                                                                                                                          | https://www.gemeentelijkgegevensmodel.nl/v2.5.0/                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [GIR-0]             | Installatiedata delen via GIR', presentatie digiGO, 2025                                                                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [GIR-1]             | GIR Documentatie                                                                                                                                                                                                                    | https://ketenstandaard.semantic-treehouse.nl/docs/api/GIR/                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [GIR-2]             | GIR Documentatie                                                                                                                                                                                                                    | https://ketenstandaard.semantic-treehouse.nl/docs/TNL/GIR/                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [IBRO-begrip]       | Geonovum,'Begrippenkader Integrale Bronregistratie Objecten', ;                                                                                                                                                                     | https://definities.geostandaarden.nl/ibro/id/begrippenkader/Samenhangende+Objectenregistratie+Gebouwen; https://definities.geostandaarden.nl/ibro/nl/index                                                                                                                                                                                                                                                                                                                             |
| [IBRO-LM 0.9.1]     | Geonovum.'Logische gegevensmodel Integrale brondregistratie objecten v 0.9.1.'                                                                                                                                                      | https://docs.geostandaarden.nl/ibro/vv-im-ibro-lm-20251105/#domein-gebouwen                                                                                                                                                                                                                                                                                                                                                                                                            |
| [IDS]               | BuildingSmart,'Information Delivery Specification (IDS)', https://www.buildingsmart.org/standards/bsi-standards/information-delivery-specification-ids/; https://github.com/buildingSMART/IDS/tree/development/Documentation        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [IFC 4.3.2]         | BuildingSmart,'IFC 4.3.2.0 specification', 2025: https://ifc43-docs.standards.buildingsmart.org/  (inhoud is conform ISO 16739-1:2024)                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [ILS-O&E-1]         | digiGO,'ILS Ontwerp & Engineering',                                                                                                                                                                                                 | https://www.digigo.nu/ilsen-en-richtlijnen/ils-ontwerp-en-engineering/                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [ILS-O&E-2]         | digiGO, 'Handboek ILS Ontwerp & engineering 2.0 - Bouwproducten                                                                                                                                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [ILS-Spaces]        | Gemeente Rotterdam e.a., 'ILS voor ruimten in de Omgevingswet', maart 2025                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [ILS-woco 3.0]      | Aedes, 'ILS-woco 3.0', 16 juli 2025                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [IMBAG 2018]        | Ministerie van BZK,'Catalogus Basisregistratie Adressen en Gebouwen',  2018'                                                                                                                                                        | https://imbag.github.io/catalogus/                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [IMIBRO 1.0.0]      | Geonovum,'Conceptueel Informatiemodel Integrale Bronregistratie Objecten (IMIBRO) 1.0.0', vastgestelde versie 29 september 2025                                                                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [IMIBRO]            | Geonovum,'Conceptueel Informatiemodel Integrale Bronregistratie Objecten (IMIBRO). Een overzicht', 28 mei 2025, https://www.geonovum.nl/uploads/documents/Conceptueel-Informatiemodel-IMIBRO%20voor%20consultatie.pdf               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [IMKAD]             | Kadaster,'Catalogus conceptueel model: IMKAD', 30 januari 2020                                                                                                                                                                      | https://developer.kadaster.nl/schemas/imkad/20200130/cat/index.html                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [IMVG]              | Geonovum,Ínformatiemodel vastgoedgebruik', werkversie 25 maart 2026                                                                                                                                                                 | https://geonovum.github.io/IMVG/                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [IMWOZ]             | Waarderingskamer,'Informatiemodel WOZ', ter vaststelling 01 januari 2026                                                                                                                                                            | https://www.waarderingskamer.nl/documenten/imwoz-models/IMWOZ-model-03.12/cat/index.html                                                                                                                                                                                                                                                                                                                                                                                               |
| [IMX-Geo]           | https://geonovum.github.io/IMX-Geo/                                                                                                                                                                                                 | zie nog meer documenten hierover op: https://www.geonovum.nl/geo-standaarden/imx-geo-semantisch-model-basis-en-kernregistraties                                                                                                                                                                                                                                                                                                                                                        |
| [IndoorGML]         | OGC,'IndoorGML 2.0 Part1-Conceptual Model, 2025                                                                                                                                                                                     | http://www.opengis.net/doc/IS/indoorgml/2.0                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [ISDE]              | RVO,'ISDE:meldcodelijsten', 2025                                                                                                                                                                                                    | www.rvo.nl/sunsidies-financiering/isde/meldcodelijsten                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [MIM 2024]          | Geonovum,’Metamodel Informatiemodellering (MIM)’, versie 1.2, 13 juni 2024                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [MiniBIM A]         | MiniBIM ILS deel A: Toelichting', v3.1-deel A', Comissie digitalisering Neprom/ Pim van Meer, Paul Strokap, 2025?                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [MiniBIM B]         | MiniBIM ILS ', v3.1-deel B', Comissie digitalisering Neprom/ Pim van Meer, Paul Strokap, 2025?                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [NAA.K.T.1]         | NAA.K.T. Eenduidige materiaalbenaming', toelichting                                                                                                                                                                                 | https://www.digigo.nu/wp-content/uploads/2023/11/EenduidigeMateriaalbenaming_toelichting.pdf                                                                                                                                                                                                                                                                                                                                                                                           |
| [NAA.K.T.2]         | NAA.K.T. Eenduidige materiaalbenaming', infographic                                                                                                                                                                                 | https://www.digigo.nu/wp-content/uploads/2023/11/EenduidigeMateriaalbenaming_infographic.pdf                                                                                                                                                                                                                                                                                                                                                                                           |
| [NAA.K.T.3]         | NAA.K.T. Eenduidige materiaalbenaming', lijst                                                                                                                                                                                       | https://www.digigo.nu/wp-content/uploads/2024/07/EenduidigeMateriaalbenaming_lijst-v2.4.xlsm                                                                                                                                                                                                                                                                                                                                                                                           |
| [NEN 2580]          | NEN, 'NEN 2580:2007 nl. Oppervlakten en inhouden van gebouwen - Termen, definities en bepalingsmethoden', mei 2007                                                                                                                  | https://connect.nen.nl/Standard/Detail/113982?compId=14489&collectionId=0                                                                                                                                                                                                                                                                                                                                                                                                              |
| [NEN 2660-1]        | NEN,'Regels voor informatiemodellering van de gebouwde omgeving - Deel 1: Conceptuele modellen', 2022                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [NEN 2660-2]        | NEN,'Regels voor informatiemodellering van de gebouwde omgeving - Deel 2: Praktische configuratie, extensie en implementatie van NEN 2660-1', 2022                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [NEN 2699]          | NEN,'NEN 2699:2017. Investerings- en exploitatiekosten van onroerende zaken', 2017                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [NEN 3610]          | NEN,'Basismodel geo-informatie - Termen, definities, relaties en algemene regels voor de uitwisseling van informatie over aan de aarde gerelateerde ruimtelijke objecten', 1 juni 2022;  https://www.nen.nl/nen-3610-2022-nl-296137 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [NEN4660]           | Nederlandse praktijkrichtlijn<br>NEN, 'NPR 4660 (nl). Modellering van gebouwde omgeving en procesindustrie - Praktijkvoorbeelden voor toepassing van NEN 2660-1 en -2', januari 2026                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [NL/SfB]            | NL/SfB 2005, versiedatum 2019-12-23                                                                                                                                                                                                 | https://www.stabu.nl/standaarden/profile.aspx; https://ketenstandaard.nl/nlbe-sfb-facts/viewer/                                                                                                                                                                                                                                                                                                                                                                                        |
| [NTA8800:2025]      | NEN, 'Energieprestaties van gebouwen - Bepalingsmethode', 2025                                                                                                                                                                      | www.nen.nl/nya-8800-2025-nl-344705                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [OTL-B&U]           | digiGO/BIMW en Gobar Adviseurs,'Draaiboek OTL voor B&U sector. Randvoorwaarden en handleiding', 2024                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [OTL-richtlijnen]   | digiGO,'Richtlijnen voor OTL'en. digiGO technische documentatie', werkdocument 17 maart 2025                                                                                                                                        | https://nl-digigo.github.io/kadersinformatiemodellen/kader/                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [RBS]               | RVB BIM Specificatie, versie 1.1-c, april 2019                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [RVB]               | Rijksvastgoedbedrijf,'Harmonisatie begrippen """"nstandhouden vastgoed v.1.0', MEMO 15-9-2022                                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [RVB-mode]          | UML-modellen 2024                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [SAREF]             | ETSI, 'SAREF: the Smart Applications REFerence ontology', 31-10-2024                                                                                                                                                                | https://saref.etsi.org/core/v4.1.1/                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [S4BLD]             | ETSI, 'SAREF4BLDG ontology and semantics', 24-04-2025                                                                                                                                                                               | https://saref.etsi.org/saref4bldg/v2.1.1/                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [SAREF-BLD]         | ETSI,' 103 410-3 V1.1.2 (2020-05). SmartM2M; Extension to SAREF; Part 3: Building Domain'                                                                                                                                           | https://www.etsi.org/deliver/etsi_ts/103400_103499/10341003/01.01.02_60/ts_10341003v010102p.pdf                                                                                                                                                                                                                                                                                                                                                                                        |
| [SEMIC Location]    | SEMIC Community,'Core Location Vocabulary'                                                                                                                                                                                          | https://semiceu.github.io/Core-Location-Vocabulary/releases/2.1.0                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [VTH-FLo]           | Ministerie van Infrastructuur en Waterstaat, 'Conceptueel Informatiemodel VTH Fysieke Leefomgeving', versie 1.0.0                                                                                                                   | https://digitaliseringvth.nl/bibliotheek/handlerdownloadfiles.ashx?idnv=3194110                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Windesheim 2024]   | Lectoraat Energietransitie Windesheim', Energetisch beter met BIM', 22-05-2024                                                                                                                                                      | https://objectstore.surf.nl/live/objectstore/9dacb26f-e9c1-47ad-9c15-44d09591d415/100610983_10074454_Rapport_Energetisch_Beter_met_BIM_20240522_met_bijlagen.pdf?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=8ea577ad65394dfeb2d62886e3056a36%2F20251227%2FNL%2Fs3%2Faws4_request&X-Amz-Date=20251227T201107Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Signature=75b8513a461aba2c0a38a1b8fa041d24384e2a26c7a90592d474064f5de53cfb |
| [Wws]               | Woningwaarderingsstelsel                                                                                                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |


## Bijlage 1: Overzicht schema's

| Schema | Beschrijving | 
| :----- | :----- |
| Aedes IM Vastgoed |conceptueel informatiemodel volgens MIM |
| Bbl | Besluit bouwwerken leefomgeving: regels voor veiligheid, gezondheid, bruikbaarheid en duurzaamheid van bouwwerken. Een bouwwerk moet altijd voldoen aan die regels. |
| BIM Basis ILS | Specificatie van eenduidige afspraken over informatieuitwisseling over bouwwerken op basis van IFC. |
| BIM Legal | 3D-weergave van de juridische situatie van een gebouw en maken van splitsingstekeningen daaruit. |
| BOT ontology| ontologie voor Linked Data BIM-modellen |  
| BRICK |  open standaard voor semantische beschrijvingen van fysieke, logische en virtuele assets in gebouwen |
| CPR-2024 | Construction Products Regulation (Verordening Bouwproducten), EU 2024/3110, regelt de eisen, CE-markering en milieu-informatie voor alle bouwmaterialen die in de EU worden verhandeld, met een sterke nadruk op duurzaamheid en circulariteit. |
| CIM | Common Information Model, raamwerk voor beheerde elementen in een systeem. CIM betreft (1) informatietechnologie (2) elektriciteits-  en energiesystemen. 3. cybersecurity & data analytics |
| CIMOW | Conceptueel Informatiemodel Omgevingswet, de basis voor het Informatiemodel Omgevingswet (IMOW), dat weer de basis is voor het Digitaal Stelsel Omgevingswet (DSO), gekoppeld aan de Standaard officiële publicaties en Toepassingsprofielen voor omgevingsdocumenten (STOP/TPOD) |
| CityGML | City Geography Markup Language, standaard voor het opslaan en uitwisselen van virtuele 3D-stadsmodellen. |
| COBie | Construction-Operations Building information exchange, open dataformaat voor de publicatie van een subset van bouwinformatiemodellen (BIM) die zich richt op het leveren van gegevens over objecten, in tegenstelling tot geometrische informatie. |
| CORA | Corporatie Referentie Architectuur, met onder meer gegevensdomeinmodellen |
| DBL | EU Digital Building Logbook, integreert het Energielabel (EPC), het Building Renovation Passport, slimme paraatheid (Smart Readiness Indicator) en duurzaamheidsdata. |
| DiCon | Digital Construction Ontologies: Terminologie voor de weergave van gedigitaliseerde bouw- en renovatieprocessen |
| DICO | set afspraken met spelregels voor de elektronische uitwisseling van informatie tussen fabrikanten, groothandels, bouw-, onderhouds- en installatiebedrijven en woningcorporaties. | 
| Dossier Bevoegd Gezag | Wkb-opleverdossier |
| ETIM | nternationale standaard voor rubricering en classificatie van technische producten |
| GEBORA 1.0 | GEBouwde Omgeving Referentie Architectuur |
| Geometrie | Geometriestandaarden: IFC (IfcGeometryResource), veelal afgeleid van ISO 10303-42: geo-standaarden: ISO 19107 e.a.) …
| GeoSPARQL |  ontologie voor geo-informatie als uitbreiding op SPARQL met functionaliteit voor ruimtelijke vragen |
| GGM | Gemeentelijk Gegevensmodel | 
| GIR | Gebouwinstallatieregister |
| IDS | Information Delivery Specification, standaard voor het specificeren van objecten, classificaties, materialen, eigenschappen en waarden in een IFC-model |
| IFC | Industry Foundation Classes (ISO 16739), open standaard voor BIM | 
| ILS O&E | informatieleveringsspecificatie Ontwerp & Engineering |
| ILS Ruimten | informatieleveringsspecificatie voor ruimten in de Omgevingswet | 
| ILS Woco | informatieleveringsspecificatie voor woningcorporaties | 
| IMBAG | Informatiemodel Basisregistratie Adressen en Gebouwen |
| IMBOR | Informatiemodel Beheer Openbare Ruimte |
| IMGEO | Informatiemodel geo-informatie, uitbreiding op de BGT-inhoud |
| IMIBRO | Informatiemodel Integrale Bronregistratie Objecten, een integrale registratie van objecten in de fysieke ruimte | 
| IMKAD | Informatiemodel Kadaster |
| IMX-Geo | Semantisch model basis- en kernregistraties |
| IMVG | Informatiemodel Vastgoedgebruik |
| IMWOZ | Informatiemodel waardering onroerende zaken (WOZ) |
| IndoorGML | ***DE REST VAN DE TABEL WORDT NOG AANGEVULD*** |
| Inspire | 
| ISO 15288  
| ISO 19117
| Ketenstandaard (KIS?)
| LADM
| LandInfra
| LVG
| materiaalpaspoort
| meetinstructies voor taxaties
| MiniBIM
| MiniGIM
| FM-standaarden
| NAA.KT
| NEN2580
| NEN2660-1
| NEN2660-2
| NEN2699
| NEN2767
| NEN3610
| NEN-EN 15221-6
| NEN-EN-15804
| NLBE-SfB
| NPR 4660
| OmniClass
| OTL B&U
| Paspoorten: CB23, GABC NEN18216 …
| RVB IM
| SAREF
| STABU
| Uniclass
| Unieke ObjectCodering
| VERA
| VIVET
| VTH-flo
| WWS | Woningwaarderingsstelsel van de Huurprijzenwet |


## Bijlage 2: Inventarisatie

### Diagrammen

<figure id="fig-aedes-im-vastgoed" class="ol-figure-large">
  <img src="images/Aedes-IM-Vastgoed.png" alt="Aedes IM Vastgoed">
  <figcaption>Aedes IM Vastgoed</figcaption>
</figure>

<figure id="fig-bbl" class="ol-figure-large">
  <img src="images/Bbl.png" alt="Bbl">
  <figcaption>Bbl</figcaption>
</figure>

<figure id="fig-bot" class="ol-figure-large">
  <img src="images/BOT.png" alt="BOT">
  <figcaption>BOT</figcaption>
</figure>

<figure id="fig-citygml" class="ol-figure-large">
  <img src="images/CityGML.png" alt="CityGML">
  <figcaption>CityGML</figcaption>
</figure>

<figure id="fig-etim" class="ol-figure-large">
  <img src="images/ETIM.png" alt="ETIM">
  <figcaption>ETIM</figcaption>
</figure>

<figure id="fig-gir" class="ol-figure-large">
  <img src="images/GIR.png" alt="GIR">
  <figcaption>GIR</figcaption>
</figure>

<figure id="fig-gs1" class="ol-figure-large">
  <img src="images/GS1.png" alt="GS1">
  <figcaption>GS1</figcaption>
</figure>

<figure id="fig-ifc" class="ol-figure-large">
  <img src="images/IFC.png" alt="IFC">
  <figcaption>IFC</figcaption>
</figure>

<figure id="fig-ifc-elementen" class="ol-figure-large">
  <img src="images/IFC-Elementen.png" alt="IFC Elementen">
  <figcaption>IFC Elementen</figcaption>
</figure>
<figure id="fig-ils-oene-algemeen" class="ol-figure-large">
  <img src="images/ILS-OenE-Algemeen.png" alt="ILS OenE Algemeen">
  <figcaption>ILS OenE Algemeen</figcaption>
</figure>

<figure id="fig-ils-oene" class="ol-figure-large">
  <img src="images/ILS-OenE.png" alt="ILS OenE">
  <figcaption>ILS OenE</figcaption>
</figure>

<figure id="fig-imbag" class="ol-figure-large">
  <img src="images/IMBAG.png" alt="IMBAG">
  <figcaption>IMBAG</figcaption>
</figure>

<figure id="fig-imibro" class="ol-figure-large">
  <img src="images/IMIBRO.png" alt="IMIBRO">
  <figcaption>IMIBRO</figcaption>
</figure>

<figure id="fig-imkad" class="ol-figure-large">
  <img src="images/IMKAD.png" alt="IMKAD">
  <figcaption>IMKAD</figcaption>
</figure>

<figure id="fig-imwoz" class="ol-figure-large">
  <img src="images/IMWOZ.png" alt="IMWOZ">
  <figcaption>IMWOZ</figcaption>
</figure>

<figure id="fig-inspire" class="ol-figure-large">
  <img src="images/INSPIRE.png" alt="INSPIRE">
  <figcaption>INSPIRE</figcaption>
</figure>

<figure id="fig-ketenstandaard-ruimte" class="ol-figure-large">
  <img src="images/Ketenstandaard-Ruimte.png" alt="Ketenstandaard Ruimte">
  <figcaption>Ketenstandaard Ruimte</figcaption>
</figure>

<figure id="fig-lvg" class="ol-figure-large">
  <img src="images/LVG.png" alt="LVG">
  <figcaption>LVG</figcaption>
</figure>

<figure id="fig-minibim" class="ol-figure-large">
  <img src="images/MiniBIM.png" alt="MiniBIM">
  <figcaption>MiniBIM</figcaption>
</figure>

<figure id="fig-minibim-elementen" class="ol-figure-large">
  <img src="images/MiniBIM-Elementen.png" alt="MiniBIM Elementen">
  <figcaption>MiniBIM Elementen</figcaption>
</figure>

<figure id="fig-minibim-beng" class="ol-figure-large">
  <img src="images/MiniBIM-BENG.png" alt="MiniBIM BENG">
  <figcaption>MiniBIM BENG</figcaption>
</figure>
<figure id="fig-naa-k-t" class="ol-figure-large">
  <img src="images/NAA.K.T.png" alt="NAA.K.T">
  <figcaption>NAA.K.T</figcaption>
</figure>

<figure id="fig-nen2580-gebouw" class="ol-figure-large">
  <img src="images/NEN2580-Gebouw.png" alt="NEN2580 Gebouw">
  <figcaption>NEN2580 Gebouw</figcaption>
</figure>

<figure id="fig-nen2580-terrein" class="ol-figure-large">
  <img src="images/NEN2580-Terrein.png" alt="NEN2580 Terrein">
  <figcaption>NEN2580 Terrein</figcaption>
</figure>


<figure id="fig-nen2660-1" class="ol-figure-large">
  <img src="images/NEN2660-1.png" alt="NEN2660 1">
  <figcaption>NEN2660 1</figcaption>
</figure>

<figure id="fig-nen2660-2" class="ol-figure-large">
  <img src="images/NEN2660-2.png" alt="NEN2660 2">
  <figcaption>NEN2660 2</figcaption>
</figure>

<figure id="fig-nen2699" class="ol-figure-large">
  <img src="images/NEN2699.png" alt="NEN2699">
  <figcaption>NEN2699</figcaption>
</figure>

<figure id="fig-nen2767" class="ol-figure-large">
  <img src="images/NEN2767.png" alt="NEN2767">
  <figcaption>NEN2767</figcaption>
</figure>

<figure id="fig-nen3610" class="ol-figure-large">
  <img src="images/NEN3610.png" alt="NEN3610">
  <figcaption>NEN3610</figcaption>
</figure>

<figure id="fig-nl-sfb-woonvoorziening" class="ol-figure-large">
  <img src="images/NL-SfB-Woonvoorziening.png" alt="NL SfB Woonvoorziening">
  <figcaption>NL SfB Woonvoorziening</figcaption>
</figure>

<figure id="fig-nl-sfb" class="ol-figure-large">
  <img src="images/NL-SfB.png" alt="NL SfB">
  <figcaption>NL SfB</figcaption>
</figure>

<figure id="fig-npr4660-voorbeeld" class="ol-figure-large">
  <img src="images/NPR4660-voorbeeld.png" alt="NPR4660 voorbeeld">
  <figcaption>NPR4660 voorbeeld</figcaption>
</figure>

<figure id="fig-npr4660" class="ol-figure-large">
  <img src="images/NPR4660.png" alt="NPR4660">
  <figcaption>NPR4660</figcaption>
</figure>

<figure id="fig-otl-benu" class="ol-figure-large">
  <img src="images/OTL-BenU.png" alt="OTL BenU">
  <figcaption>OTL BenU</figcaption>
</figure>

<figure id="fig-paspoortcb23" class="ol-figure-large">
  <img src="images/PaspoortCB23.png" alt="PaspoortCB23">
  <figcaption>PaspoortCB23</figcaption>
</figure>

<figure id="fig-rvb" class="ol-figure-large">
  <img src="images/RVB.png" alt="RVB">
  <figcaption>RVB</figcaption>
</figure>

<figure id="fig-saref" class="ol-figure-large">
  <img src="images/SAREF.png" alt="SAREF">
  <figcaption>SAREF</figcaption>
</figure>

<figure id="fig-vth-flo" class="ol-figure-large">
  <img src="images/VTH-FLo.png" alt="VTH FLo">
  <figcaption>VTH FLo</figcaption>
</figure>

## X IMIBRO

Figuur

| Onderwerp | Specificatie |
| :----- | :----- |
| Schema | IMIBRO |
| Term | Panddeel |
| Identificatie | .... |
| Definitie | Een Panddeel is een niet vrijstaand deel van (de constructie) van een Pand dat wordt onderscheiden omdat het op een ander moment onderdeel is geworden van dat Pand dan andere panddelen of omdat de aard van de bouwkundige constructie voldoet aan bepaalde criteria. |
 Bron | [IMIBRO] |
 | Context | Basisregistratie |
 | Bijzonderheden | Een Panddeel kan intern (inpandig) of extern (aan de buitenzijde van een Pand) zijn. Interne Panddelen zijn later aangebouwde delen (afwijkend bouwjaar) of fysiek onderscheidend. Een Pand kent altijd een verplicht Panddeel type Basisconstructie (zie bij Pand).|
 | Voorbeelden | |
 | Commentaar | |


***Toelichting***

| Onderwerp | Specificatie |
| :----- | :----- |
| Schema | Aanduiding van de standaard of het model |
| Term | Termnaam |
| Identificatie | .... |
| Definitie | Originele definitie, zodanig aangepast, dat alleen een zo beknopt mogelijke definiërende uitdrukking resteert. |
 Bron | [Verwijzing naar de bron] |
 | Context | Domein, waarbinnen de term gehanteerd wordt met de aangehaalde definitie |
 | Bijzonderheden | In de bron vermelde bijzonderheden. Soms is de definitie ingekort en wordt het verwijderde deel uit de definitie hier vermeld.|
 | Voorbeelden |In de bron genoemde voorbeelden|
 | Commentaar |Commentaar en vraagpunten vanuit IMWO|


1.  Hieraan wordt in een later stadium nog aandacht besteed


