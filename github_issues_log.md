## Ref #130: [CityGML] - CityGML in eerstvolgende versie expliciete aandacht geven

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 0.0, Paragraaf algemeen

**Commentaar:**
Bij aanvang van de quickscan is gevraagd om ook de aansluiting op de standaard CityGML mee te nemen. Zowel in de UML-schema’s (hoofdstuk 6) als de relatietabellen bij de concepten (hoofdstuk 7) zien wij geen
relaties met CityGML gemodelleerd. Hierom hebben wij de koppeling met CityGML verder buiten beschouwing gelaten.

**Reactie digiGO:**
klopt: (1) ivm tijdgebrek, (2) wel geïnventariseerd en meegenomen in de definitievorming en (3) in NEN 3610 wordt aanbevolen in 3D-situaties aan te sluiten op CityGML Indirect ligt er dus wel een lijn, maar ik geef toe: die moet nog uitgewerkt worden voor de relevante onderdelen van het model


**Acceptatiecriteria / To-do:**
- [ ] CityGML in eerstvolgende versie expliciete aandacht geven. Toegesneden project IMWO-CityGML definiëren, gericht op logische modellering en testen.
- [ ] invulling CityGML

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #100: [Algemeen] - logisch model IMWO, gerelateerd aan corporatiesector CORA-VERA-IM Aedes - ILS...

**Beschrijving:**
**Indiener:** Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Vraag: is dit model bruikbaar voor de corporatiesector?

**Reactie digiGO:**
dat lijkt er wel op. Bij de ontwikkeling van IMWO zijn nadrukkelijk corporatieproducten, met name het informatiemodel van Aedes en ILS-Woco, als input gebruikt. Via IMWO kunnen corporatiedata gerelateerd worden aan andere data.


**Acceptatiecriteria / To-do:**
- [ ] logisch model IMWO, gerelateerd aan corporatiesector CORA-VERA-IM Aedes - ILS/Woco

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #1: [algemeen] - invulling IFC

**Beschrijving:**
**Indiener:** Ben Huijskes (JP van Eesteren)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
•	Ik vraag mij af of IMWO niet opnieuw het wiel probeert uit te vinden.
o	Ik zie dat de structuur van het data-model in hoofdlijnen overeenkomen met de structuur van IFC, maar als je meer de diepte in gaat matchen ze net niet. Dat is zonde.
o	Ik deel hierin de mening van Lex. Als de structuur al bestaat in IFC, we die beter kunnen aanhouden. IFC zal immers de data-drager worden, toch?

**Reactie digiGO:**
- het informatiemodel volgt niet één structuur; wel is het topmodel, gebaseerd op NEN 2660 en NEN 3610, van grote invloed op de structuur
- IFC is niet voor alle gegevens de drager; uiteraard wel voor de fysieke bouwwerkdata in het ontwrp- en bouwproces.


**Acceptatiecriteria / To-do:**
- [ ] invulling IFC

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #2: [algemeen] - doel en doelgroep IMWO verduidelijken

**Beschrijving:**
**Indiener:** Ben Huijskes (JP van Eesteren)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Voor wie is deze standaard geschreven, en wat verwacht men van de feedback? Documentatie is zeer (data-)technisch en hoog over. In de projectorganisatie herkennen wij maar weinig collega's die uit de praktijk komen.De gemiddelde BIMmer zou hier, zoals de documentatie nu is, niet goed op kunnen reageren. Menno geeft ook al aan: is dit enkel een mapping, en verwijs je naar de individuele standaarden, of gaat de IMWO ook eigenschappen (o.i.d.) verplichten?

**Reactie digiGO:**
- de doelgroep zijn businessprofessionals en IT-specialisten, geen BIM-modelleurs; het gaat om de bevordering van interoperabiliteit; inderdaad komen er te weinig deelnemers van de projectorganisatie uit de (bouw-)praktijk; ondanks vele inspanningen is het niet gelukt bouwers te interesseren voor dit project
- dit is niet 'enkel een mapping', maar een basis voor mappings, alsnede voor de semnatische laag van het DGSO. IMWO gaat niets verplichten, alleen faciliteren.


**Acceptatiecriteria / To-do:**
- [ ] doel en doelgroep IMWO verduidelijken
- [ ] vervolgactiviteiten mét deelnemers uit de praktijk

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #5: [algemeen] - toelichting verbeteren

**Beschrijving:**
**Indiener:** Ben Huijskes (JP van Eesteren)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Al met al, de intentie tot harmonisatie lijkt mij goed, maar ik twijfel enorm over de aanvliegroute, en of jullie wel tot een gewenst resultaat kunnen komen.

**Reactie digiGO:**
Wij hebben minder twijfel: door te werken aan het verwerken van overeenkomsten en verschillen tussen het grote en diverse aantal standaarden kunnen we komen op goede mappings óf tot overeenstemming over termen en begrippen in bepaalde situaties. Dat laatste geldt met name voor allerlei classificaties (bouwwerken, woningen, installaties, bouwcomponenten, ruimten, etc. etc.). Dit wordt niet in een achternamiddag opgelost, maar door gestadig doorwerken op basis van het geschetste - niet dwingende - algemene kader.


**Acceptatiecriteria / To-do:**
- [ ] toelichting verbeteren

**Labels:** `documentation`
**Prioriteit:** `Laag`

---

## Ref #92: [Conclusie] - topmodel op basis van NEN 2660 en NEN 3610 logisch uitwerken

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
IMWO bevat een herkenbare structuur welke aansluit op reeds bekende standaarden binnen de informatiemodellering van woongebouwen. De belangrijkste aanscherping ligt naar onze mening in de positionering van IMWO ten opzichte van bestaande bovenliggende standaarden. Wij adviseren om NEN 2660 en NEN 3610 zo veel mogelijk rechtstreeks als stabiel topmodel te hergebruiken en binnen IMWO vooral de domeinspecifieke concepten te modelleren. Daarnaast adviseren wij om relaties waar mogelijk explicieter en semantisch scherper te modelleren, en zien wij een aantal verbeteringen in de koppeling met NEN 2660, NEN 3610 en IFC. Bovendien zijn er een aantal klassen welke mogelijk geherpositioneerd kunnen worden, of waarvan de definitie scherper gemaakt kan worden. 
 
Aanbeveling voor vervolg en beheer 
Wij adviseren om IMWO niet alleen als document of statisch model te beheren, maar ook als linkeddatamodel/OTL te publiceren en te beheren. Door het model als OTL te hosten, kunnen concepten, relaties, definities en koppelingen met externe standaarden eenduidig via URI’s worden ontsloten. Dit ondersteunt hergebruik, versiebeheer, verwijzingen vanuit andere modellen en automatische verwerking door software. 
 
Daarnaast adviseren wij om een laagdrempelige beheerprocedure in te richten waarbij gebruikers, modelleurs en andere stakeholders opmerkingen of wijzigingsvoorstellen kunnen indienen. Deze opmerkingen kunnen periodiek worden verzameld en beoordeeld door een commissie bestaande uit expert(s) en informatiemodelleur(s), en vervolgens worden verwerkt in de IMWO. Hiermee ontstaat een beheerproces waarbij IMWO inhoudelijk kan ontwikkelen tot een brede industriestandaard. 
 
Verder is de IMWO op dit moment enkel gericht op woongebouwen, terwijl het informatiemodel ook relevant kan zijn voor utiliteitsgebouwen. Een mogelijke uitbreiding van het model kan dan ook zijn om het informatiemodel uit te breiden met specifieke concepten voor de utiliteitsbouw.

**Reactie digiGO:**
Conclusie: over gebruik van NEN 2660  en NEN 3610 als stabiel topmodel zijn we het eens. Die dienen wel eerst met elkaar in overeenstemming gebracht te worden, Verder dient er bij de uitwerking in de komende jaren ruimte te bestaan voor het preciseren van de mappings. Niet voetstoots aannemen dat als in een norm gesproken wordt over een Building dat dan hetzelfde is als een Pand in de BAG! 

Publicatie als LD/OTL-document: helemaal mee eens en dat was en is ook de bedoeling





laagdrempelige beheerprocedure: akkoord!





verbreding IMWO met utiliteitsgebouwen: mee eens. Sterker nog: ook de infra en de openbare ruimte horen erbij. Op naar een IMGO: Informatiemodel Gebouwde Omgeving.


**Acceptatiecriteria / To-do:**
- [ ] topmodel op basis van NEN 2660 en NEN 3610 logisch uitwerken
- [ ] beheerprocedure inrichrten

**Labels:** `documentation`
**Prioriteit:** `Hoog`

---

## Ref #127: [Algemeen] - inventarisatie en analyse oplossingsrichtingen Canoniek model en varianten (V...

**Beschrijving:**
**Indiener:** Daoud Urdu (Geonovum/ NEN3610/ Zicht op nederland)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
1. Er is keuze gemaakt voor een ‘ontologische’ vorm van interoperabiliteitsverhoging. In 2.5 wordt er gesproken over een linkset waarin informatiemodellen naar elkaar verwijzen.
1. In 2.6 wordt er gesproken over een canoniek model, dit suggereert dat er een (centraal) model is waarin alle waarheid bestaat. Dit lijkt tegenstrijdig met het idee van federatieve samenwerking, hergebruik van bestaande modellen. Suggestie om nog eens goed te heroverwegen of de term en, daarmee het idee van, canoniek gepast is.
2. Het kopje van 5.1 bevat twee keer globaal
3. Toon eventueel in plaatje 7, dat bepaalde objecttypen worden hergebruikt: bijv. Fysiekobject uit NEN3610 en woonobjecten uit BAG. Zelfde geldt voor figuur 8. Dit kan ook met verschillende kleuren en een legenda. Dit is in figuur 11 (topmodel) overigens wel terug te zien. Modelmatig betekent dit ook dat objecttypes niet worden ‘gedupliceerd’ maar hergebruikt met enkel een verwijzing
4. Afgeleid uit figuur 11, voor het model geldt: mogelijk hergebruik van W3C standaarden, zoals bijvoorbeeld skos:exactMatch in plaats van heeftRelatieMet. Dit heeft mogelijk ook invloed op 2.5 Mapping en Matching. Dit geldt ook voor relaties binnen het model: bijv. imwo: installatieComponent – imwo:gerelateerdAan – imwor:Installatie
5. Voor het object Terrein (en mogelijk andere objecttypen) is het wellicht goed om hergebruik te maken van IMGEO
6. Notities voor het informatiemodel Funderingen: in Figuur 15, bouwcomponenten is te zien dat Fundering en Funderingspaal een subklasse zijn van een Bouwwerk:Bouwcomponent
7. Verdere beschrijving van Fundering: https://nl-digigo.github.io/imwo/functional-doc-1-0/1.0/h/v082/imwo-rapport.html#fundering
8. Wat betreft definities voor Fundering:  In de begripsdefinitie wordt gesproken over ‘onderdeel van de fundering van een constructie…”. Dit leest als dat fundering ook weer onderdeel is van de fundering. Lijkt daarnaast ook niet overeen te komen met brondefinitie (daar wordt gesproken over een funderingselement).
9. Wat betreft definities Funderingspaal:  In de formele definitie wordt gesproken over dat funderingspaal onderdeel is van een Fundering. Dit lijkt niet zo terug te komen in Figuur 15, bouwcomponenten. Of is Figuur 15 niet bedoelt om deze relaties te weergeven?
10. 7.10 titel lijkt niet te kloppen
11. In het model lijken de termen materiele- en formele historie, alsook levensduur van objecten (tijdlijn geldigheid en registratie), niet terug te komen. Dit zou conform NEN 3610 mogelijk een aandachtspunt kunnen zijn.
12. Tabel 12.2.2. (Tabel) lijkt een overzicht van alle (relevante?) begrippen uit meerdere informatiemodellen weer te geven. Dit lijkt overbodig, aangezien dit nu een lange tabel is met begrippen en definities uit andere modellen. Veel begrippen komen overigens ook meerdere keren voor. Een compacter tabel, met een stukje toelichting welke begrippen en definities uit welke modellen specifiek zijn overgenomen zou mogelijk de leesbaarheid en gebruik van het model verbeteren.
13. In de turtle bestand zie ik imwo, imwos, imwom, imwor. Deze worden verder niet in het informatiemodel toegelicht. Uitleg en toelichting hierover is gewenst. Bij voorkeur een ‘base’ schema, en zo nodig refereren naar hulp schema’s, zoals bijvoorbeeld begrippen (begrippenkader).

**Reactie digiGO:**
ad 1. Bedoeld is dat er federatief samengewerkt kan worden en dat vertalingen lopen via een centraal model. Het lijkt inderdaad noodzakelijk de terminologie nog eens te verduidelijken en ook de keuzemogelijkheden op een rijtje te zetten (ontology alghnment, vocabulary hub, canocial model, etc.) 
ad 2. Klopt. 5.1 t/m 5.4 is het globale model. Daarbinnen is 5.1 globaal model, dus globaal globaal model.
ad 3. De plaatjes 7 en 8 zijn globaal, ook nog de gerefereerde objecttypen opnemen levert wellicht een te druk geheel op.
ad 4. Op het niveau van het conceptuele model kan nog niet beoordeeld worden of er sprake is van een exactMatch. Dat gaan we bij de uitwerking van logische modellen bekijken.
ad 5. Akkoord  
ad 6. Klopt
ad 7. Afstemming IMWO-IMFUN is een mooi vervolgproject. 
ad 8. Klopt: fout moet hersteld worden
ad 9. Figuur 15 niet bedoeld om deze relaties weer te geven. Figuur 15 geeft overigens op globaal niveau de bouwcomponenten weer. In de praktijk worden de componenten vergaan gedecomponeerd (zie bijvoorbeeld ILS O&E)
ad 10. Ja, moeten we bekijken
ad 11. Inderdaad  belangrijk om nog uit te werken, het tijdsaspect.
ad 12.Tabel 12.2.2.  bevat de inventarisatie van alle rlevante begrippen met definities en is essentieel voor de aanpak. De bedoeling is wel  de weergave van de brongegevens te vervangen door een URI-verwijzing. . Niettemin is het te overwegen een compacte tabel toe te voegen die alleen de begrippen bevat waarnaar in IMWO echt verwezen wordt.
ad 13. Het ttl-bestand zal beter toegeicht worden.


**Acceptatiecriteria / To-do:**
- [ ] inventarisatie en analyse oplossingsrichtingen Canoniek model en varianten (Vocabulary Hub, Data Mesh, etc.) in relatie tot DSGO
- [ ] inventarisatie uitbreiden met IMGEO, relateren aan Terrein e.a.
- [ ] vervolgproject IMWO-IMFUN

**Labels:** `documentation`
**Prioriteit:** `Laag`

---

## Ref #128: [Algemeen] - Conformiteitstoets NEN 3610

**Beschrijving:**
**Indiener:** Daoud Urdu (Geonovum/ NEN3610/ Zicht op nederland)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Mocht het nog niet zijn gebeurd, wellicht goed om het Geonovum NEN3610 Conformiteitstoets uit te voeren voor IMWO

**Reactie digiGO:**
Goed idee. Nemen we in overweging.


**Acceptatiecriteria / To-do:**
- [ ] Conformiteitstoets NEN 3610

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #126: [Algemeen] - bekijken of figuren in vectorformaat mogelijk zijn

**Beschrijving:**
**Indiener:** Erwin Lazet (Syndetho BV)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Afbeeldingen schalen niet; scaled vector formaat zou handiger zijn voor leesbaarheid.

**Reactie digiGO:**
klopt


**Acceptatiecriteria / To-do:**
- [ ] bekijken of figuren in vectorformaat mogelijk zijn.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #111: [algemeen] - Uitbreiding IMWO met begrippen uit volkshuisvesting, leegstand, industrieel b...

**Beschrijving:**
**Indiener:** Jesse van de Wal (VNG)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
1. Wordt er bewust niet gerefereerd aan woningbouwplannen?
2. Koppeling met de Basisset 2.0 die wordt uitgevraagd in de Landelijke Monitor Voortgang Woningbouw: Verschillende typen ouderenwoningen (nultredenwoningen, geclusterde woningen, zorggeschikte woningen), betaalbaarheidsklassen (NHG-grens, betaalbaarheidsgrens, sociale huur, middenhuur, vrije sector).
3. Koppeling met gegevensverzameling volgens Besluit Versterking Regie Volkshuisvesting artikel 11.74 (https://www.internetconsultatie.nl/besluitregievolkshuisvesting2/document/13942).
4.  Leegstand: energieverbruik, eigenaar.
5.  Industrieel bouwen en EKV's
6.  Realisatiestimulans: Bouw gestart

**Reactie digiGO:**
ad 1. Nee. Een Woonobject kan de status 'gepland'hebben. Of is dit niet bedoeld?
ad 2. Moet straks meegenomen worden in de verbetering van de klassificatie van WoonObjecten
ad 3. Goede aanvulling, moet in vervolgtraject meegenomen worden.
ad 4. Idem
ad 5. Idem
ad 6. Meenemen in uitwerking Toestanden/Gebeurtenissen


**Acceptatiecriteria / To-do:**
- [ ] Uitbreiding IMWO met begrippen uit volkshuisvesting, leegstand, industrieel bouwen, erkende kwaliteitsverklaringen, toestanden/ gebuertenissen

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #113: [toegevoegde waarde van het model] - Vervolgproject gericht op afstemming IMWO-IMIBRO (logsch model)

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
De IBRO en BAG kennen andere begrippen. Er is wel een specialisatie en generalisatie opgenomen maar 1 op 1 is er weinig van terug te vinden. Dat betekent dat er toch met verschillende talen wordt gesproken en vertaling nodig is.

**Reactie digiGO:**
Dit klopt, er wordt wel minimalisatie nagestreefd.


**Acceptatiecriteria / To-do:**
- [ ] Vervolgproject gericht op afstemming IMWO-IMIBRO (logsch model)

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #114: [toegevoegde waarde van het model] - Review item omtrent toegevoegde waarde van het model

**Beschrijving:**
**Indiener:** Niek Pluijmert (VNG)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Als koepel voor de gemeenten gebruikt VNG de begrippen bij vergunningverlening en kwaliteitsborging in de bouw


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #115: [toegevoegde waarde van het model] - In versie 1

**Beschrijving:**
**Indiener:** Paul Oude Luttighuis (project Landelijke Voorziening Gebouwgegevens)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Deze reactie is namens het project Landelijke Voorziening Gebouwgegevens (LVG), in haar huidige staat van ontwikkeling. De LVG betrekt gebouwgegevens uit verschillende bronnen, integreert ze en ontsluit voor uiteenlopende handelingsperspectieven.

Het belang van een gezamenlijk informatiemodel daarvoor is evident, maar het model voor LVG groeit mee met de haar achtereenvolgende ontwikkelstappen van LVG. De eerste ontwikkelstap is in voorbereiding, maar nog niet zover dat de gebruikersbehoefte, integratiebehoefte en de bronmodellen daarvoor al als testcasus voor IMWO kunnen worden gebruikt. Daarom kunnen wij nog amper inhoudelijke feedback geven.

Wel is duidelijk dat, wanneer de eerste ontwikkelstap daarvoor scherp genoeg is, daarvoor een zeer scherp en gedetailleerd model nodig zal zijn, gedetailleerder dan IMWO nu (begrijpelijkerwijs) is. De integratie van LVG zal namelijk (maximaal) geautomatiseerd moeten plaatsvinden.

Voor LVG zou het bevorderlijk zijn een werkrelatie met IMWO te organiseren, die meedraait met de casus-gewijze ontwikkeling van de LVG. Dat biedt IMWO zeer concrete testcasussen en biedt LVG onmiddellijke relevantie. Hoe meer handelingsperspectieven via LVG worden afgewikkeld, hoe waardevoller de testcasussen ook voor IMWO worden, omdat de handelingsperspectieven niet alleen per stuk, maar ook onderling samenhangende modellen zullen vragen.

De score van vier sterren betekent: score nog niet van toepassing.

**Reactie digiGO:**
Eens met de voorgestelde werkrelatie.


**Acceptatiecriteria / To-do:**
- [ ] In versie 1.0 is het submodel LVG geactualiseerd.
- [ ] Werkrelatie opzetten en operationaliseren.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #112: [toegevoegde waarde van het model] - Review item omtrent toegevoegde waarde van het model

**Beschrijving:**
**Indiener:** Ralph Knol (VNG)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Het model zoals het er nu staat gaat op bepaalde vlakken zeer gedetailleerd terwijl het op andere vlakken niet gedetailleerd genoeg gaat. Hiermee is de match met het WOZ-domein niet goed te maken omdat dit niet aansluit bij de uitgangspunten/werkwijzen.

**Reactie digiGO:**
De nadruk in deze versie van IMWO ligt op woningen en woongebouwen als fysieke objecten.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #117: [Algemeen] - Review item omtrent algemeen

**Beschrijving:**
**Indiener:** Ralph Knol (VNG)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Deze vraag is moeilijk te beantwoorden omdat er binnen het WOZ-domein inmiddels een brede discussie loopt over welke gegevens benodigd zijn voor de WOZ en op welk detailniveau

**Reactie digiGO:**
?


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #122: [Algemeen] - Review item omtrent algemeen

**Beschrijving:**
**Indiener:** Ralph Knol (VNG)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Betrek de uitvoering/mensen uit de praktijk om zo de aansluiting te houden en er anderzijds voor te zorgen dat het beheersbaar en daarmee betaalbaar blijft.

**Reactie digiGO:**
Akkoord


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #6: [algemeen] - geen aanpassingen; meenemen voor het vervolg

**Beschrijving:**
**Indiener:** Siham el Yamani (machine leesbare regelgeving VNG/ TU Delft / OGC)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Thanks for sharing, Gerlof! This is really concrete and inspiring 🙏 I see the results are structured in a similar way to  what we discussed about aligning our deliverables in the same format. It actually feels very practical and helpful, even if we don’t have all the results ready yet!

**Reactie digiGO:**
De relatie IMWO-OGC-standaarden (met name CityGML) zouden in een vervolgtraject uitgediept kunnen/  moeten worden.


**Acceptatiecriteria / To-do:**
- [ ] geen aanpassingen; meenemen voor het vervolg
- [ ] invul,ing CityGML

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #7: [algemeen] - geen aanpassingen; meenemen voor het vervolg

**Beschrijving:**
**Indiener:** Siham el Yamani (machine leesbare regelgeving VNG/ TU Delft / OGC)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
As we discussed thursday, That could be interesting for the working gorup to share such insight with OGC in this event :  the Helsinki OGC meeting next week ( bit late 🙂 )  https://events.ogc.org/OGCConnectHelsinki#/?lang=enand the OGC iDays in November https://events.ogc.org/iDays2026will be very much related to their topic, so if they have the opportunity to attend, it would be interesting to bring such standard result to inernational standarizaiton organisation.

**Reactie digiGO:**
Laten we om te beginnen snel een gesprek op NL-niveau arrangeren!


**Acceptatiecriteria / To-do:**
- [ ] geen aanpassingen; meenemen voor het vervolg
- [ ] bijdrage leveren aan OGC Connect iDays  https://events.ogc.org/iDays2026 23/24 november a.s. voorstel indienen vóór 15 juli 2026

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #109: [algemeen] - Vervolgproject gericht op afstemming IMWO-IMIBRO (logsch model)

**Beschrijving:**
**Indiener:** Theo de Smidt (Gemeente Rotterdam / GIN)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Goed om in een breder perspectief in te zoomen op de modellering van woningen. Er is dan meteen de vraag bij mij, waarom niet-woningen niet. Afgezien daarvan goed om dat nog scherper te maken. Wat ik hierin mis is de uitgetekende samenhang naar IBRO - WOZ - BAG - BGT - KAD. En met de ontwikkeling van de IBRO zou ik voorstander zijn om de mapping / relaties juist vanuit dit model ook met een paar voorbeelden / platen te duiden.

Daarnaast is het goed iets te zeggen over de logica van bestaande objectafbakenings-definities in de basisregistraties. Dat is dan vooral voor WOZ en BAG. Zou het niet verstandig zijn dat het subjectieve element in WOZ: "naar omstandigheden beoordeeld samenvoegen" wordt verwijderd. En daar waar BAG geen objecten "ziet" volgens de definitie (olietanks, overkappingen, enz.) dat die in lijn worden gebracht met WOZ definities en de definities hier.

Ofwel wanneer je op enige plek in de fysieke ruimte staat: zie je fysieke objecten. Alle fysieke objecten zouden dus ook in de voorgestelde logica gemodelleerd moeten zijn. Dat betekent dat WOZ - BAG - BGT daarop eenduidig gemodelleerd moeten zijn. Het juridische object zal natuurlijk nooit zichtbaar zijn. Dat blijft dan een uitzondering, maar is in het veld wel aanwijsbaar.


**Acceptatiecriteria / To-do:**
- [ ] Vervolgproject gericht op afstemming IMWO-IMIBRO (logsch model)

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #108: [zie github] - Review item omtrent zie github

**Beschrijving:**
**Indiener:** Wouter Lubbers, (NEN2660 beheercommissie Semmtech)
**Locatie:** Hoofdstuk 0.0

**Commentaar:**
Ik heb een paar opmerkingen toegevoegd, verder kan ik me vinden in de review van Rik.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #91: [Linked data-versie van IMWO] - OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader u...

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 1.0, Paragraaf 1.6

**Commentaar:**
Het linked-datamodel is nu vooral opgezet als SKOS-model. Dat is geschikt voor termen, labels, definities, bronverwijzingen en begrippenhiërarchieën, maar minder geschikt voor het vastleggen van de formele modelstructuur. Relaties zoals skos:broader en skos:related zijn relatief zwak en maken onvoldoende expliciet of sprake is van een subtype, eigenschap of inhoudelijke relatie. Wij adviseren daarom om SKOS te blijven gebruiken voor de terminologie, maar de feitelijke modelstructuur te modelleren met RDFS en/of OWL. Gebruik bijvoorbeeld rdfs:subClassOf voor specialisatie-relaties en expliciete RDF/OWL-properties voor relaties tussen klassen. Verwijs daarnaast waar mogelijk met URI’s naar concepten uit externe standaarden, in plaats van met tekstuele strings. Tot slot adviseren wij om eigen relaties zoals imwor:gerelateerdAan, imwor:relatieSoort, imwor:relatieNaam en imwor:bronterm waar mogelijk te vervangen door relaties uit standaarden zoals SKOS, RDFS, OWL, NEN 2660 en NEN 3610, en deze te modelleren conform de principes van linked data zodat deze machine-readable zijn.

**Reactie digiGO:**
helemaal mee eens.De LD-versie heeft in feite alleen betrekking op het begrippenniveau (de informele definities). De strakke RDF/OWL- of SHACL-uitwerking zal moeten gebeuren in het vervolgtraject. Alsdan dient er ook direct verwezen te worden naar de URI's van de bronmodellen (zoals NEN 2660 en IFC).


**Acceptatiecriteria / To-do:**
- [ ] OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader uitwerken en consolideren

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #131: [Model als Linked Data] - Volledige realisatie van de LD-versie

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 1.0, Paragraaf 1.6

**Commentaar:**
MWO leunt zwaar op NEN 2660, IFC, NEN 3610 en IMBAG. Echter, in plaats van standaard Linked Data-koppelingen te maken (zoals skos:exactMatch, skos:broadMatch of owl:equivalentClass naar de URI's van die standaarden), gebruikt IMWO platte tekst en custom properties: imwor:bronterm "TopConcept"@nl imwor:parentPackage "NEN2660" Dit breekt het hele idee van Linked Data. Een computer kan de string "TopConcept" niet automatisch koppelen aan https://w3id.org/nen2660/term#TopConcept. Het gebruik binnen IMWO van skos:exactMatch nen2660-term:TopConcept ; zou toch wel erg handig zijn. Ik denk te weten waarom dit is, maar zeg het toch even.

**Reactie digiGO:**
Het IMWO-project was er in eerste instantie op gericht een eerste versie te ontwikkelen van een inhoudelijk semantisch model en niet op een technisch volwaardige implementatie. De gebruikte tools zijn Sparx Enterprise Architect (Sparx EA) en Excel. Als extra is het model (alsook de geïnventariseerde standaarden en andere schema's) vertaald naar LD. In de volgende versie dient de aansluiting op LD volledig gerealiseerd te worden.


**Acceptatiecriteria / To-do:**
- [ ] Volledige realisatie van de LD-versie
- [ ] OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader uitwerken en consolideren

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #132: [Model als Linked Data] - OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader u...

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 1.0, Paragraaf 1.6

**Commentaar:**
SKOS is bedoeld voor thesauri en begrippenlijsten (zachte semantiek). OWL is voor harde logica en datamodellen. IMWO probeert UML-achtige datamodel-eigenschappen (zoals cardinaliteit en associatienamen) in een SKOS-bestand te stoppen via custom properties (imwor:relatieCode "R5").
Het maakt het SKOS-bestand onnodig complex en onbruikbaar voor standaard SKOS-viewers. NEN 2660 houdt dit veel schoner door SKOS puur voor de begrippenlijst te gebruiken, en de harde relaties in aparte OWL/SHACL bestanden te definiëren.
Ook hier denk ik te weten waarom dit is, maar zeg het toch even.

**Reactie digiGO:**
Het SKOS-bestand dient inderdaad alleen betrekking te hebben op de Begripsdefinities. We zullen proberen deze beperking in de 1.0 versie door te voeren.


**Acceptatiecriteria / To-do:**
- [ ] OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader uitwerken en consolideren

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #133: [Model als Linked Data] - Review item omtrent model als linked data

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 1.0, Paragraaf 1.6

**Commentaar:**
IMWO gebruikt skos:Collection (bijv. imwom:Bouwwerken) om concepten logisch te groeperen in modules/pakketten, zonder dat dit de hiërarchie (skos:broader) in de war schopt. Dit is een best practice.
Identifiers: IMWO kent aan elk concept een unieke UUID toe via dct:identifier (bijv. "7bf417f7-5234-11f1-a512-00ffdb61c323"). Dit is uitstekend voor versiebeheer en persistentie, mocht de naam (prefLabel) van een concept in de toekomst veranderen


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Laag`

---

## Ref #134: [Model als Linked Data] - OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader u...

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 1.0, Paragraaf 1.6

**Commentaar:**
Hierin zit "platte" reïficatie van relaties. Bijvoorbeeld:
skos:related imwo:Entiteit ; imwor:relatieCode "R3" ; imwor:relatieSoort "heeft relatie met"@nl ; imwor:relatieNaam "isImplementatieVan"@nl ; imwor:gerelateerdAan imwo:Entiteit ;
skos:related imwo:Entiteit ; imwor:relatieCode "R3" ; imwor:relatieSoort "heeft relatie met"@nl ; imwor:relatieNaam "isDeelVan"@nl ; imwor:gerelateerdAan imwo:Entiteit ;
RDF is een set van losse triples. Als een parser dit inleest, krijgt het subject imwo:Entiteit simpelweg twee keer de eigenschap skos:related, twee keer imwor:relatieNaam ("isImplementatieVan" en "isDeelVan"), enzovoort. De relatie tussen de specifieke naam en het specifieke doelobject gaat volledig verloren. Een machine weet niet meer of "isDeelVan" bij de eerste of de tweede skos:related hoort.

**Reactie digiGO:**
Ja, inderdaad. De huidige export was bedoeld als een eerste SKOS-representatie van het model, maar we kunnen dit aanpassen door relaties als afzonderlijke resources te modelleren. De relatie-metadata wordt dan gekoppeld aan die specifieke relatie-resource, waardoor de samenhang behouden blijft.


**Acceptatiecriteria / To-do:**
- [ ] OWL-versie van het conceptueel model  en SKOS-versie van het begrippenkader uitwerken en consolideren

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #94: [Inleidng] - stimulering van een wetenschappelijk onderzoek naar de gevolgen van het gebre...

**Beschrijving:**
**Indiener:** Lex Ransijn, Menno Mekes en Ben Huijskes/ Aydemir (Building SMART IFC)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
1. Toegevoegde waarde en businesscase
De belangrijkste vraag die terugkomt is: "Welke concrete problemen lost IMWO op die vandaag nog niet worden opgelost?"
De behoefte aan semantische samenhang wordt herkend, maar reviewers vragen om concrete use-cases waarin zichtbaar wordt:
- welke informatie-uitwisseling vandaag vastloopt;
- welke semantische verschillen opgelost worden;
- en welke meerwaarde IMWO daadwerkelijk toevoegt.

**Reactie digiGO:**
Er zijn vele voorbeelden van gebrekkige communicatie met als gevolg kosten, vertraging en risico's. Bijvoorbeeld geeft Heijmans in het VIS-project i.o. aan: Informatie versnipperd in systemen (veel communicatie
tussen personen en applicaties); Verschillende ‘talen’ (definities) per contract. Verschillende informatiebehoeften per contract. Data is niet uniform; niet accuraat en niet betrouwbaar. Steeds meer data, steeds minder uniformiteit. 
Een kernprobleem is dat de vele taalproblemen in de processen zelf worden opgelost, zodat de totale gevolgen voor financiën, kwaliteit en risico's niet zichtbaar zijn. Terzijde zij opgemerkt dat een wetenschappelijk onderzoek ter zake heel wenselijk is. Met een conceptueel model, gevolgd door uitwerking van logische modellen, kunnen voorwaarden geschapen worden voor semantische interoperabiliteit, waardoor samenwerking en communicatie daadwerkelijk verbeterd kunnen worden.


**Acceptatiecriteria / To-do:**
- [ ] stimulering van een wetenschappelijk onderzoek naar de gevolgen van het gebrek aan semantische interoperabiliteit

**Labels:** `enhancement`
**Prioriteit:** `Hoog`

---

## Ref #95: [Inleiding] - korte toelichting

**Beschrijving:**
**Indiener:** Lex Ransijn, Menno Mekes en Ben Huijskes/ Aydemir (Building SMART IFC)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
2. Relatie met IFC, bSDD en bestaande standaarden
Vanuit buildingSMART-perspectief wordt nadrukkelijk gevraagd hoe IMWO zich verhoudt tot:
IFC;
bSDD;
ILS'en;
OTL's;
en andere bestaande informatiemodellen.
Met name leeft de vraag of IMWO uiteindelijk een semantische harmonisatielaag ("Vocabulary Hub") wordt, zoals nu in de oplegnotitie wordt beschreven, of dat het zich ontwikkelt tot een zelfstandig nationaal informatiemodel. Dit onderscheid wordt als cruciaal gezien voor adoptie.

**Reactie digiGO:**
IFC: relatering van begrippen uit allerlei standaarden aan de IFC-begrippen, met als doel implementatie van adequate transformaties.
bsDD: bron voor de inventarisatie; integratie met de inventarisatie is een optie
ILS: fungeren als het informatiemodel op basis waarvan ILS'en gespecificeerd kunnen worden: bron voor de inventarisatie;
OTL: integratie van OTL's in (verbreed en verdiept)IMWO
IMWO is bedoeld als semantische harmonisatielaag.


**Acceptatiecriteria / To-do:**
- [ ] korte toelichting
- [ ] relaties met IFC, bsDD, ILS en OTL meenemen in uitwerkingsprojecten (logische modellen en usecases)

**Labels:** `documentation`
**Prioriteit:** `Hoog`

---

## Ref #96: [Beheer] - Review item omtrent beheer

**Beschrijving:**
**Indiener:** Lex Ransijn, Menno Mekes en Ben Huijskes/ Aydemir (Building SMART IFC)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
3. Governance en beheer
Reviewers zien governance als één van de belangrijkste succesfactoren.
Vragen die daarbij leven:
Wie beheert de mappings?
Wie beheert de semantiek?
Hoe worden wijzigingen in bronstandaarden verwerkt?
Hoe wordt voorkomen dat een nieuwe beheerlast ontstaat naast bestaande standaarden?

**Reactie digiGO:**
zie beheerplan. digiGO richt een beheerorganisatie in. De totale beheerlast voor de sector zal dalen, omdat point to point oplossingen vervangen worden door centralisatie van mappings ('canoniek'model).


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Hoog`

---

## Ref #97: [Inleiding - algemeen] - invulling relatie IMWO-IFC

**Beschrijving:**
**Indiener:** Lex Ransijn, Menno Mekes en Ben Huijskes/ Aydemir (Building SMART IFC)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
4. Praktische implementeerbaarheid
Vanuit BIM-praktijk en implementatieperspectief wordt aangegeven dat de huidige documentatie sterk conceptueel is.
Er is behoefte aan:
- praktijkvoorbeelden;
- referentie-implementaties;
- use-cases;
- voorbeeldmappings;
en concrete uitwerkingen richting BIM-processen.
Juist daar zal volgens de reviewers zichtbaar worden waar semantische verschillen daadwerkelijk optreden en welke harmonisatie nodig is.

**Reactie digiGO:**
Akkoord
Dit moet opgepakt worden in het kader van de ontwikkeling van de volgende versies van IMWO.


**Acceptatiecriteria / To-do:**
- [ ] invulling relatie IMWO-IFC

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #98: [inleiding & beheer] - Review item omtrent inleiding & beheer

**Beschrijving:**
**Indiener:** Lex Ransijn, Menno Mekes en Ben Huijskes/ Aydemir (Building SMART IFC)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
5. Scope en haalbaarheid
Een laatste aandachtspunt betreft de omvang van de ambitie.
De reviewers herkennen dat IMWO relaties wil leggen tussen een groot aantal standaarden, registraties en domeinen.
Daarbij wordt geadviseerd om:
- use-case gedreven te blijven werken;
- iteratief te ontwikkelen;
en de meerwaarde per stap aantoonbaar te maken.

**Reactie digiGO:**
Akkoord


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #99: [Samenvatting] - invulling relatie IMWO-IFC in samenwerking met de BIM-wereld, bijvoorbeeld do...

**Beschrijving:**
**Indiener:** Lex Ransijn, Menno Mekes en Ben Huijskes/ Aydemir (Building SMART IFC)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
Samenvattend
De algemene indruk vanuit de buildingSMART-community is positief ten aanzien van het streven naar meer semantische samenhang binnen de gebouwde omgeving.
De oplegnotitie helpt om de positionering van IMWO aanzienlijk beter te begrijpen.
De belangrijkste resterende vragen gaan niet meer over individuele definities, maar vooral over:
- toegevoegde waarde;
- positionering ten opzichte van IFC/bSDD;
- governance;
- implementatie;
- en adoptie in de praktijk.
Ik hoop dat deze eerste reflectie behulpzaam is voor de verdere reviewfase en doorontwikkeling richting versie 1.1.

**Reactie digiGO:**
Het is belangrijk dat bij de verdere ontwikkeling van het informatiemodel personen uit de BIM-wereld actief betrokken zijn, zowel de IFC-experts als de mensen uit de praktijk, zoals architecten, adviseurs, aannemers, installatateurs en opdrachtgevers.


**Acceptatiecriteria / To-do:**
- [ ] invulling relatie IMWO-IFC in samenwerking met de BIM-wereld, bijvoorbeeld door projecten waarin de relatie IMWO-ILS aan de orde gesteld wordt.

**Labels:** `documentation`
**Prioriteit:** `Hoog`

---

## Ref #123: [Algemeen] - Afstemming MIBRO-IMWO

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 1.0

**Commentaar:**
Het is natuurlijk niet mogelijk om in een wereld waar iedereen een andere taal spreekt om een taal te ontwikkelen die voor iedereen gelijk is maar ook gelijk is aan zijn eigen taal. Daarmee is de uitdaging van IMWO duidelijk. Onlangs is goed na gedacht over het IBRO model en het is opvallend dat het IMWO anders is opgebouwd en andere begrippen kent en dus niet 1,2,3 aansluit op het IBRO-model. Daar zou meer aandacht aan besteed mogen worden. Om te voorkomen dat twee gloednieuwe informatiemodellen in de gebouwde omgeving, niet met elkaar kunnen communciren.

**Reactie digiGO:**
Mee eens,


**Acceptatiecriteria / To-do:**
- [ ] Afstemming MIBRO-IMWO

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #146: [ruimten] - Review item omtrent ruimten

**Beschrijving:**
**Indiener:** Leon van der Zanden (CorpoNet, Woonbedrijf)
**Locatie:** Hoofdstuk 2.0, Paragraaf 2.5

**Commentaar:**
'ruimten'
ik neem aan dat hier 'fysieke ruimte' wordt bedoeld.

**Reactie digiGO:**
Klopt


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #147: [ruimten] - Terugkoppeling van tekortkomingen in de bestaande normen naar de betreffende ...

**Beschrijving:**
**Indiener:** Leon van der Zanden (CorpoNet, Woonbedrijf)
**Locatie:** Hoofdstuk 2.0, Paragraaf 2.5

**Commentaar:**
'functie'
En dan zijn dit functionele ruimtes.

**Reactie digiGO:**
Niet in de strikte zin van NEN 3610
Reactie LvdZ: Hier zit de kern van het probleem. We proberen goed te doen aan alle bestaande normen, maar die rammelen dus. Ik zou het graag omdraaien. Zet het goed neer, en geef aan waar de bestaande normen te kort schieten. BbL, Nen enzovoort. 
Rereactie digiGO: dit is precies waarmee we bezig zijn.


**Acceptatiecriteria / To-do:**
- [ ] Terugkoppeling van tekortkomingen in de bestaande normen naar de betreffende normcommissies

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #135: [Globaal model] - herstellen

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.

**Commentaar:**
Voorafgaaande': Typo

**Reactie digiGO:**
thx


**Acceptatiecriteria / To-do:**
- [ ] herstellen

**Labels:** `bug`
**Prioriteit:** `Medium`

---

## Ref #103: [Globaal model] - verduidelijken

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.1

**Commentaar:**
RuimtelijkObject heeft geen definitie (Ruimtelijk geo object wel), in het document is het gebruik daardoor niet eenduidig/duidelijk

**Reactie digiGO:**
RuimtelijkObject is een synoniem van FysiekeRuimte


**Acceptatiecriteria / To-do:**
- [ ] verduidelijken

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #105: [Globaal model] - Review item omtrent globaal model

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.1

**Commentaar:**
Hier wordt gesproken van ruimtelijke en reele "objecten"; in het globale model zijn het componenten. Een component is altijd deel van iets groters? Een component heeft een deelfunctie ten dienste van een bovenliggende functie.

**Reactie digiGO:**
In het globaal model wordt alleen de specialisatie aangegeven, nog niet de decompositie van reële en ruimtelijke componenten.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #151: [Woonobjecten] - opnemen van standplaatsen en ligplaatsen in IMWO

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.1

**Commentaar:**
Woonobjecten: kunnen toch ook objecten op stand- en ligplaatsen zijn? Ik neem aan dat die ook een onderdeel moeten zijn van de IMWO. zeker als je kijkt naar de opkomende tijdelijke woonunits die geen panden/gebouwen zijn.

**Reactie digiGO:**
Goede aanvulling. We zijn in IMWO natuurlijke gefocust op gebouwen. In de volgende versie van IMWO moeten we belijken hoe we standplaatsen en ligplaatsen inpassen.


**Acceptatiecriteria / To-do:**
- [ ] opnemen van standplaatsen en ligplaatsen in IMWO

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #103: [Fysieke objecten] - Review item omtrent fysieke objecten

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.2

**Commentaar:**
Het ruimtelijke object heeft niet per definitie materie in het model (5.2), hoe breng je het verband aan?

**Reactie digiGO:**
Een FysiekObject bevat materie, een RuimtelijkOnject ook, omdat dat een specialisatie is van FysiekObject.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #104: [Fysieke objecten] - Review item omtrent fysieke objecten

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.2

**Commentaar:**
Fysieke ruimte is niet in het model opgenomen, is wel beschreven en staat in detailmodel 6.2

**Reactie digiGO:**
FysiekeRuimte en RuimtelijkObject zijn synoniemen


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #106: [Globaal model] - Review item omtrent globaal model

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.2

**Commentaar:**
Beschrijving van ruimtelijk object ontbreekt

**Reactie digiGO:**
Synoniem van Fysiekeruimte


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #107: [Bouwwerken] - Uitbreiding van IMWO met Complexen en Gebieden in vervolgproject(en)

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.2

**Commentaar:**
Hierbij moet steeds bedacht worden dat een bouwwerk een onderdeel is van een groter geheel (complex, gebied) dat op zijn beurt gebruik(ers) kent en functies vervult, en dat zelf bestaat uit componenten (tot op het laagste niveau) en weer gebruik(ers) en functies kent, die worden ingevuld door technische oplossingen (producten, materialen).
Het bouwwerk en alle componenten waar deze uit bestaat, doorlopen gedurende hun gehele levenscyclus de vier hoofdtoestanden, mogelijk meerdere keren, met behoud van informatie
Hoe gaat met model hier mee om?

**Reactie digiGO:**
Het bouwwerk is inderdaad deel van een groter geheel. Het model kan later uitgebreid worden met Complexen en Gebieden.
Wat betreft de decompositie, daarvoor biedt het model een structuur aan, die uitgewerkt kan/moet worden in logische modellen c,q, gerelateerd worden aan bestaande logische modellen


**Acceptatiecriteria / To-do:**
- [ ] Uitbreiding van IMWO met Complexen en Gebieden in vervolgproject(en)
- [ ] Invulling van de levenscyclus in vervolgproject(en)

**Labels:** `enhancement`
**Prioriteit:** `Laag`

---

## Ref #152: [Gebouw] - nader preciseren

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.3

**Commentaar:**
Het geheel of gedeeltelijk omsloten met wanden maakt het onnodig ingewikkeld. Dat kan wel maar dan moet je ervoor zorgen dat er ook een object (gebouwdeel) is per kenmerk open of ontsloten zodat de relatie met bijvoorbeeld het BAG pand gelegd kan worden dat geheel omsloten is met wanden. Of voor andere doeleinden zoals isolatie vraagstukken enz.

**Reactie digiGO:**
De bron van 'geheel of gedeeltelijk omsloten met wanden' is NEN 3610:2022 (pag. 64). Dat behoeft inderdaad nadere precisering.


**Acceptatiecriteria / To-do:**
- [ ] nader preciseren

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #110: [woonobject] - Review item omtrent woonobject

**Beschrijving:**
**Indiener:** Theo de Smidt (Gemeente Rotterdam / GIN)
**Locatie:** Hoofdstuk 5.0, Paragraaf 5.4

**Commentaar:**
Par 5.4 De zin: Het bevat woonobjecten, verblijfsobjecten met een woonfunctie. Is cryptisch. Woonobject = verblijfsobject?
Idem voor deze: wooneenhedenobjecten (een zelfstandig geheel, bestaande uit onzelfstandige wooneenheden). Zit de verzameling van zelfstandigheid dan niet op het Woonobject?

Wat doe je met installatiecomponent en inventariscomponent per woning of wooneenheid. Op het laagste niveau vastleggen moet het naar boven toe over erven in de reële componenten. De vraag alleen is of het realistisch is dat je hier een systematische vastlegging van kunt krijgen. In een BIM model obv vergunningverlening zit het wellicht al wel en wordt het voor bijv. de IBRO er weer weggefilterd.
Later in fig. 18 wringt het daar ook. Installaties op woonobject niveau of op bouwwerkniveau. Een Nutsaansluiting zit in mijn beleving altijd op woonobject niveau.

Par. 6.2 – Bouwwerken: Bijzonder zin in relatie tot definitie van bouwwerk, wat is de ratio hiervan?
• weggelaten: ’Of een ruimtelijk af te bakenen deel daarvan’; dit zou modellering van een deel van een groter bouwwerk (vleugel, segment, bouwdeel) als afzonderlijk bouwwerk mogelijk maken; een nieuwe term is dan toch te prefereren, bijvoorbeeld ‘deelbouwwerk’, en wel omdat de zelfstandigheid van het object een essentieel kenmerk van een bouwwerk is.

Fig. 17 Woonobjectruimten: Binnenruimte – Verblijfsruimte – Woon/Keuken/Slaapruimte à Maak hier Mulitfunctionele ruimte van als het niet te duiden is.

Fig 21 Juridische objecten: Er worden relaties gelegd tussen IMWOZ – IMBAG – IMKAD objecten die nu losgekoppeld lijken te zijn.

**Reactie digiGO:**
zie nrs 8. 9 en 10


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `documentation`
**Prioriteit:** `Laag`

---

## Ref #101: [Globaal model] - Verduideliijkende tekst en verdere uitwerking in een volgende versie

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 5.0

**Commentaar:**
Begrip
In dit model wordt geen onderscheid gemaakt tussen fysieke en functionele objecten; alle fysieke objecten hebben een functie, behalve het object FysiekObject
Het onderscheid van de 3 abstractieniveaus lijkt een specialisatie/generalisatieketting te zijn; een specialisatie van fysieke objecten. Die specialisatie loopt langs functionele aspecten, die steeds specifieker worden
Het model bevat onder de abstractie fysieke objecten herbruikbare functionele clusteringen van fysieke objecten. 
Ieder fysiek object heeft een functie en kan een aanvullende functie krijgen in een specifieke context (wand dragend, wand scheidingsfunctie)
Zijn de concepten/abstracties voldoende duidelijk? In de gepubliceerde versie is geen uitleg van de concepten aanwezig

**Reactie digiGO:**
Ook het objecttype ysiekObject heeft een Functie. Dat specialisatie alleen langs functionele aspecten loopt is niet gezegd: ook niet-functionele aspecten kunnen tot specialisatie lopen. Functionele specialisatie in relatie tot technische specialisatie is overigens een interessant nader uit te ewrken onderwerp (zie ook het 'Hamburgermodel').


**Acceptatiecriteria / To-do:**
- [ ] Verduideliijkende tekst en verdere uitwerking in een volgende versie.
- [ ] Uitwerking Functies in relatie tot FunctioneleObjecten en TechnischeObjecten in samenhang

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #8: [topmodel figuur 7 en figuur 8] - proberen binnen de beperkte tijd de toelichting te verbeteren in de 1

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 5.0

**Commentaar:**
Goed om in een breder perspectief in te zoomen op de modellering van woningen. Er is dan meteen de vraag bij mij, waarom niet-woningen niet. Afgezien daarvan goed om dat nog scherper te maken. Wat ik hierin mis is de uitgetekende samenhang naar IBRO - WOZ - BAG - BGT - KAD. En met de ontwikkeling van de IBRO zou ik voorstander zijn om de mapping / relaties juist vanuit dit model ook met een paar voorbeelden / platen te duiden.

**Reactie digiGO:**
Er is voor gekozen om te starten met woongebouwen, maar verbreding tot gebouwen in het algemeen is zonder meer gewenst. Inderdaad zou de toelichting beter kunnen. Een uitwerking van IMWO-IMIBRO tot logisch model en beproeving van dat model in instantiaties zou een mooi  samenwerkingsproject van  digiGO, VNG en Rijk zijn. Gericht op afstemming van basisregistraties op geoBIM-standaarden en vice versa.


**Acceptatiecriteria / To-do:**
- [ ] proberen binnen de beperkte tijd de toelichting te verbeteren in de 1.0-versie. Als dit niet lukt in de 1.1-versie.
- [ ] Vervolgproject gericht op afstemming IMWO-IMIBRO (logsch model)

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #9: [topmodel figuur 7 en figuur 8] - geen aanpassingen

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 5.0

**Commentaar:**
Daarnaast is het goed iets te zeggen over de logica van bestaande objectafbakenings-definities in de basisregistraties. Dat is dan vooral voor WOZ en BAG. Zou het niet verstandig zijn dat het subjectieve element in WOZ: "naar omstandigheden beoordeeld samenvoegen" wordt verwijderd. En daar waar BAG geen objecten "ziet" volgens de definitie (olietanks, overkappingen, enz.) dat die in lijn worden gebracht met WOZ definities en de definities hier.

**Reactie digiGO:**
wat is de bron van het citaat "naar omstandigheden beoordeeld samenvoegen"? Dit komt niet voor in het IMWO-document. Verbetering van de onderlinge afstemming van BAG en WOZ definities lijkt ons geen overbodige luxe.


**Acceptatiecriteria / To-do:**
- [ ] geen aanpassingen
- [ ] Vervolgproject gericht op afstemming IMWO-IMIBRO (logsch model)

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #10: [topmodel figuur 7 en figuur 8] - geen aanpassingen

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 5.0

**Commentaar:**
Ofwel wanneer je op enige plek in de fysieke ruimte staat: zie je fysieke objecten. Alle fysieke objecten zouden dus ook in de voorgestelde logica gemodelleerd moeten zijn. Dat betekent dat WOZ - BAG - BGT daarop eenduidig gemodelleerd moeten zijn. Het juridische object zal natuurlijk nooit zichtbaar zijn. Dat blijft dan een uitzondering, maar is in het veld wel aanwijsbaar.

**Reactie digiGO:**
helemaal mee eens


**Acceptatiecriteria / To-do:**
- [ ] geen aanpassingen
- [ ] meenemen als thema in een vervolgproject dat betrekking heeft op afstemming IMWO-IMIBRO

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #11: [woonobjecten] - overwegen figuur 10 uit te breiden met VBO

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 5.0

**Commentaar:**
Par 5.4 De zin: Het bevat woonobjecten, verblijfsobjecten met een woonfunctie. Is cryptisch. Woonobject = verblijfsobject?

**Reactie digiGO:**
Woonobject is subtype van BAG-VerblijfsObject. Dit wordt later toegelicht (zie figuur 15)


**Acceptatiecriteria / To-do:**
- [ ] overwegen figuur 10 uit te breiden met VBO

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #12: [woonobjecten] - Review item omtrent woonobjecten

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 5.0

**Commentaar:**
Idem voor deze: wooneenhedenobjecten (een zelfstandig geheel, bestaande uit onzelfstandige wooneenheden). Zit de verzameling van zelfstandigheid dan niet op het Woonobject?

**Reactie digiGO:**
ja, klopt


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #3: [bouwcomponenten] - foutjes herstellen

**Beschrijving:**
**Indiener:** Ben Huijskes (JP van Eesteren)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6. figuur 15

**Commentaar:**
“De BouwComponenten worden in 14 klassen verdeeld. Daarbij wordt nauw aangesloten bij de ILS O&E en IFC." Dit lijkt een verwijziging te zijn naar IfcSharedBldgElements, wat in werkelijkheid maar een fractie van het totale IFC-schema is. Let op: je moet ook de TypeEnumerations accepteren wil jij volledige toegang hebben tot de eigenschappen per Entiteit. IfcBearing is pas een Entiteit sinds IFC4.2, dus eerdere IFC-versies zijn niet toegestaan? Ondersteunen de softwarepaketten van de gebruikers überhaupt deze IFC-versie? BIM Basis ILS / ILS O&E schrijven (nog) geen specifieke IFC versie voor.

**Reactie digiGO:**
Het hele IMWO is gericht op een conceptueel model over de gehele breedte van de gebouwde omgeving vwb wonen. De precisering komt bij de uitwerking in logische modellen. In de huidige versie zitten onvermijdelijk onvolkomenheden. Overigens is commentaar gevraagd aan de ILS-specialisten m.b.t. BIM Basis en O&E, maar we hebben geen reactie ontvangen.


**Acceptatiecriteria / To-do:**
- [ ] foutjes herstellen

**Labels:** `bug`
**Prioriteit:** `Medium`

---

## Ref #4: [installaties] - keuze nader toelichten

**Beschrijving:**
**Indiener:** Ben Huijskes (JP van Eesteren)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6. figuur 18

**Commentaar:**
"Het submodel voor Installaties sluit aan bij het Gebouwinstallatieregister (GIR) en de daarin toegepaste standaarden. Verder is het objecttype Nutsaansluiting opgenomen om een relatie te leggen met de NutsSystemen. De Installaties zijn verder geklassificeerd volgens de NL-SfB-standaard.". Geen verwijziging naar Systems (lees: IfcDistributionSystem)?. NL/SfB-coderingen zijn niet volledig sluitend op praktijk. Weet je zeker dat je hierop wilt classificeren?

**Reactie digiGO:**
Op advies van de vertegenwoordiger van Techniek NL is gekozen voor de NL-SfB-classificatie. Het is echter een voorzet, die nader uitgewerkt moet worden en waarover zo mogelijk de sector overeenstemming verkrijgt. Uiteraard dient er op IfcDistributionSystem gemapt te kunnen worden.


**Acceptatiecriteria / To-do:**
- [ ] keuze nader toelichten
- [ ] Uitwerking klassificatie installaties en mapping op de relevante standaarden

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #150: [Relatiesoort Relatienaam] - Review item omtrent relatiesoort relatienaam

**Beschrijving:**
**Indiener:** Wouter Lubbers, (NEN2660 beheercommissie Semmtech)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6.1

**Commentaar:**
Wat is de noodzaak voor de splitsing in relatiesoort en relatienaam? Dit zorgt ervoor dat de betekenis van de relatie soms in 'relatiesoort' gevonden moet worden en soms in 'relatienaam'.

**Reactie digiGO:**
Relatiesoort' verwijst naar een classificatie van relaties in een aantal hoofdgroepen. De relatienaam is de naam van de relatie waarom het gaat. Ik zal kijken hoe we dit duidelijker kunnen presenteren.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #104: [Topmodel] - aanpassing bekijken

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6.2

**Commentaar:**
In detailuitwerking 6.2 correspondeert fysieke ruimte niet met ruimtelijk object in het model 5.2 voor fysieke objecten (en in 6.2 zijn FysiekeRuimte en ReeelObject omgekeerd tov 5.2).

**Reactie digiGO:**
Inderdaad niet zo mooi dat in het ene model de plaatsing links-rechts verschilt van die in het andere model.


**Acceptatiecriteria / To-do:**
- [ ] aanpassing bekijken

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #105: [Woonobjecten] - aanpassen

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6.2

**Commentaar:**
Figuur 16 
Woonobjecten in figuur 16  en in figuur 10 globaal model woonobjecten: relaties woonobject-woongebouw verschillend. Figuur 10 lijkt beter te kloppen
Hier wordt beleid geïntroduceerd in de vorm van doelgroepen, dat lijkt niet meer relevant voor deze modellering
Bij meergezinswoning: = onderscheid langs ontsluitingswijze gebouw. Maisonnette zegt niets over de ontsluitingswijze. Criterium voor deze enumeratie specifiek maken. Dit lijstje heeft veel impact op registraties in de sector.

**Reactie digiGO:**
Klopt. Figuur 16 is leidend, figuur 10 een schematische weergave. Dat de figuren verschillen is inderdaad niet handig.
Aanduiding 'doelgroepen'is niet bedoeld als beleid, het is slechts een aanduiding.
De klassificatie eengezinswoning-meergezinswoning is voorlopig. Klassificaties dienen in een vervolgproject verder vormgegeven te worden, gebaseerd op een gedegen analyse.


**Acceptatiecriteria / To-do:**
- [ ] aanpassen

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #106: [Woonobjecten] - Review item omtrent woonobjecten

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6.2

**Commentaar:**
Functieruimte is een generalisatie van verblijfs-, verkeers- en technische ruimte. Als je verkeer en technisch ziet als ondersteunende functies, is in ieder geval verblijfsruimte een specialisatie van een functieruimte.

Zie ook de volgende dia.

**Reactie digiGO:**
De term 'Functieruimte'is overgenomen van Bbl en heeft een beperkte reikwijdte (berguirmte e.d.). De klassificatie van ruimten wordt een specifieke actie an sich.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #136: [Topmodel] - Review item omtrent topmodel

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 6.0, Paragraaf 6.2

**Commentaar:**
De "Top"-collectie van IMWO is in feite een lokale hertekening van NEN 2660. Dat is meteen de kern van het probleem: IMWO kopieert NEN 2660 tekstueel in plaats van het te importeren en te mappen. Dat is wellicht voor nu nog goed, maar de implementatie kan handiger waardoor het ook makkelijker wordt om de semantische correctheid te controleren

**Reactie digiGO:**
Zie boven: gaat gebeuren. Wel met dien verstande dat termen en definities uit standaarden niet klakkeloos overgenomen worden. Er moet ruimte blijven voor mappings tussen IMWO-objecttypen en objecttypen van standaarden zoals NEN 3610. Bijvoorbeeld IMWO werkt met de term Bouwwerk, terwijl NEN 3610 'Constructie' hanteert. Ander voorbeeld: een IMWO-Gebouw kan niet zomaar als een IMBAG-Pand gezien worden.Als IMWO straks naar attributen uitgebreid wordt, zal dat nog duidelijker worden. Om die reden is in veel gevallen een relatie met de naam heeftRelatieMet opgenomen tussen IMWO-objecttypen en externe standaard-objecttypen. Om later nader in te vullen dus. Verder: het zomaar overnemen van gehele standaarden is sowieso onmogelijk omdat standaarden onderling niet consistent zijn.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #80: [topmodel] - geen aanpssing; precisering relaties met NEN 2660 in vervolgtraject

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
In het topmodel is expliciet de keuze gemaakt om een eigen informatiemodel op te zetten waarin bestaande concepten uit de NEN 2660 en NEN 3610 niet worden hergebruikt, maar worden ‘gespecialiseerd’. Voorbeelden hiervan zijn: 
•	IMWO:Toestand is specialisatie van NEN2660:Toestand 
•	IMWO:FysiekObject is specialisatie van NEN2660:FysiekObject 
Wij adviseren echter om NEN 2660 en NEN 3610 zoveel mogelijk als stabiele bovenstructuur te gebruiken. Hergebruik de NEN 2660 en NEN 3610 en modelleer enkel domeinspecifieke concepten in de IMWO. Modelleer vervolgens deze domeinspecifieke concepten als specialisaties van de betreffende normen. Dit maakt het (her)gebruik en toepassing van abstracte topstructuren, vastgelegd in open standaarden als NEN 2660 en NEN 3610, nóg sterker in onze sector, en is in lijn met andere standaarden zoals de IMBOR. Bovendien voorkom je hiermee verwarring tussen concepten die op het eerste gezicht hetzelfde lijken, maar net een andere definitie hebben. Hiermee ligt de nadruk daarnaast op hergebruik en ‘het voortborduren op’, in plaats van gedeeltelijke duplicatie. Omdat abstracte topstructuren zoals de NEN 2660 en NEN 3610 niet snel wijzigen, zien wij hier geen wezenlijk risico in. Wij adviseren hierbij om te kijken naar de manier waarop IMBOR dit heeft toegepast. 
Wanneer IMWO er toch voor kiest om eigen concepten op te nemen die inhoudelijk overeenkomen met concepten uit de NEN-normen, leg dan een expliciete mapping vast via een owl:equivalentClass- of skos:exactMatch-relatie. Uitgangspunt hierbij is dat het IMWO-concept en het NEN-concept dezelfde definitie hanteren.

**Reactie digiGO:**
Uiteindelijk gaat het nog een stapje verder: vanuit IMWO is in het algemeen gekozen voor 'heeftRelatieMet'. Dit omdat als er sprake zou zijn van samenvallen/ equivalentie dit aangetoond moet worden. In principe zijn de begrippen verschillend in te vullen en moet er ruimte zijn om een mapping te maken. In de huidige situatie wordt er té gemakkelijk vanuit gegaan dat we over hetzelfde praten.
Hergebruik van zowel NEN2660 als NEN 3610  gaat ervanuit dat die twee standaarden coherent zijn. Dat is niet het geval: zie bijvoorbeeldd 'reëel object'en 'ruimtelijk gebied/ virtuele ruimte': andere definities.


**Acceptatiecriteria / To-do:**
- [ ] geen aanpssing; precisering relaties met NEN 2660 in vervolgtraject.
- [ ] kijken hoe IMBOR hergebruik van NEN 2660 en NEN 3610 heeft toegepast.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #81: [topmodel] - Detaillering relatie NEN 2660 - IMWO in vervolgprojecten

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Daarnaast zijn binnen IMWO zowel fysieke objecten als ruimtelijke objecten essentieel. Niet alleen afzonderlijk, maar vooral in hun onderlinge samenhang. Neem daarom expliciete NEN 2660-relaties op tussen ruimtelijke objecten of gebieden enerzijds en reële of fysieke objecten anderzijds. Relevante relaties zijn bijvoorbeeld heeft deel, is begrensd door en bevat. 
•	Voorbeeld: Ruimtelijk object “1e verdieping” heeft deel Ruimtelijk object “slaapkamer”. 
•	Voorbeeld: Ruimtelijk object “slaapkamer” is begrensd door Fysiek object “muur”. 
•	Voorbeeld: Ruimtelijk object “slaapkamer” bevat Reëel object “bed”.

**Reactie digiGO:**
De NEN-relaties zijn in het IMWO-topmodel benoemd en zullen gedetailleerd worden in uit te werken logische modellen. Opm': in NEN 2660 staan fysieke objecten niet tegenover ruimtelijke objecten, maar reële objecten tegenover ruimtelijke objecten.


**Acceptatiecriteria / To-do:**
- [ ] Detaillering relatie NEN 2660 - IMWO in vervolgprojecten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #82: [topmodel] - Review item omtrent topmodel

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Ook zien we binnen IMWO op verschillende plekken generieke relaties zoals heeft relatie met. Wij adviseren deze waar mogelijk te vervangen door semantisch scherpere relaties. Dit verbetert de leesbaarheid en duidelijkheid.

**Reactie digiGO:**
Dit gaat uiteraard gebeuren in het vervolgtraject


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #83: [Bouwwerk] - ad 2

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
De belangrijkste aanscherping op het onderdeel bouwwerken ligt in het verder aanscherpen van de relaties tussen concepten en de koppeling met standaarden, met name IFC en NEN 3610. In onderstaande lijst zijn onze opmerkingen en suggesties voor het onderdeel bouwwerken puntsgewijs opgenomen.
1 .	Maak de relatie tussen Bouwwerkcomponent, Geometrische ruimte en RuimteHoeveelheid explicieter. De betekenis van heeftRelatieMet is hiervoor te algemeen. 
2.	Verduidelijk het onderscheid tussen Product en Bouwcomponent. De huidige parallelle modellering suggereert twee naast elkaar bestaande soorten bouwwerkcomponenten, terwijl ook een bestaat-uit-relatie denkbaar is. 
3.	De klassen Terrein, Bouwwerk, en Gebouw zijn alle drie gekoppeld aan IfcSpace. Dit is inhoudelijk niet passend. Gebruik hier de IFC-klassen IfcSite, IfcBuiltFacility, en IfcBuilding.  
4.	Heroverweeg overbodige heeft-relaties tussen ruimtelijke bouwwerkcomponenten wanneer de isDeelVanrelatie de structuur al voldoende expliciet maakt. 
5.	Overweeg om bij concepten die inhoudelijk overeenkomen met NEN 2660 of NEN 3610 aan te sluiten op de concepten en definities uit deze normen, in plaats van eigen varianten te introduceren, zoals bijvoorbeeld Constructie (NEN 3610) en Bouwwerk (IMWO). 
6.	Overweeg ook Ruimte als specialisatie van RuimtelijkeBouwwerkComponent te modelleren. 
7.	Overweeg om de relatie tussen NEN 2580 en BepalingsMethode, en de relatie tussen Bepalingsmethode en Ruimtehoeveelheid expliciet te maken. 
8.	De klassen Bruto-/Netto-/TarraGeometrischeRuimte staan niet in Respec. Daarnaast is onduidelijk wat het verschil tussen deze concepten en BouwwerkComponentOppervlakte/-Inhoud is. Overweeg dit te verduidelijken.

**Reactie digiGO:**
ad 1. welke wordt bedoeld. Ik zie dit niet in het model Bouwwerken
ad 2. met Product wordt een buiten de bouwplaats geproduceerde bouwwerkcomponent bedoeld. Een product kan zowel een Bouwcomponent als een Installatiecomponent als een Inventsrisacomponent zijn. NB Er dient nog een productdecompositie toegevoegd te worden: een aangeleverd product kan groot zijn, tet en met een complete woning!
ad 3. hierop zouden we verduidelijking willen ontvangen
ad 4. ?
ad 5. als dat mogelijk is: OK. Maar de term Bouwwerk wordt buiten NEN 3610 veel gebruikt en met een Constructie wordt veelal iets anders bedoeld.
ad 6. Binnen de context van een Bouwwerk kunnen Ruimte en RuimtelijkeBouwwerkComponent als synoniemen gehanteerd worden.
ad 7. ?
ad 8. Dit zal aangevuld worden


**Acceptatiecriteria / To-do:**
- [ ] ad 2. Decompositiemogelijkheid producten expliciteren

**Labels:** `documentation`
**Prioriteit:** `Hoog`

---

## Ref #84: [Bouwcomponenten] - Uitwerking Bouwcomponenten in Logsch modelproject

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Onderdeel bouwcomponenten 
De belangrijkste aanscherping op het onderdeel bouwcomponenten ligt in het consistent omgaan met IFCmappingen en het verbeteren van onderlinge relaties tussen componenten. In onderstaande lijst zijn onze opmerkingen en suggesties voor het onderdeel bouwcomponenten puntsgewijs opgenomen. 
1	Zonwering is gemodelleerd als specialisatie van Bouwcomponent, overweeg om dit te modelleren als specialisatie van Installatiecomponent. 
2	Overweeg definities aan te scherpen waar IFC-begrippen inhoudelijk niet volledig samenvallen met IMWObegrippen. Dit is met name van toepassing bij Plaat/IfcPlate en Ondersteuningsconstructie/IfcMember. 
3	Maak een bewuste keuze tussen is specialisatie van en heeft relatie met bij de IFC-mapping. Dubbele relaties naar hetzelfde concept kunnen verwarrend zijn. 
4	Voeg waar relevant mappingen toe naar IFC voor hogere klassen in de taxonomie, zoals 3DRuimte en IfcSpace. 
5	In de definitie van de klassen Deur en Raam wordt gesteld dat deze onderdeel zijn van Wand of Dak. Overweeg om dit soort onderlinge relaties expliciet te modelleren. 
6	VirtueleComponent is een specialisatie van BouwComponent wat weer een specialisatie is van 
ReëleBouwComponent. Dit impliceert dat VirtueleComponent een reëel component is, maar dat klopt niet met de definitie van VirtueleComponent. Overweeg om VirtueleComponent op een andere manier te modelleren.

**Reactie digiGO:**
ad 1. zou kunnen; in dezen is wel IFC gevolgd
ad 2. in het algemeen: dit is een eerste voorzet; in discussie met álle betrokkenen dient er een goede classificatie tot stand te komen
ad 3. klopt; wordt nagelopen
ad 4. OK
ad 5. latere uitwerking
ad 6. we gaan onze best doen; nu is aangesloten bij IFC; een VirtueleComponent is een vreemde eend in de bijt


**Acceptatiecriteria / To-do:**
- [ ] Uitwerking Bouwcomponenten in Logsch modelproject

**Labels:** `bug`
**Prioriteit:** `Hoog`

---

## Ref #85: [Woonobjecten] - Uitwerking Woonobjecten in Logsch modelproject

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Onderdeel woonobjecten 
De belangrijkste verbetering op het onderdeel woonobjecten ligt in het verduidelijken van relaties en het herzien van een aantal specialisaties. In onderstaande lijst zijn onze opmerkingen en suggesties voor het onderdeel woonobjecten puntsgewijs opgenomen. 
1.	Overweeg Gebouw niet verder te specialiseren naar Woongebouw, maar een eigenschap functie te gebruiken met een enumeratielijst. Dit voorkomt verwarring bij multifunctionele gebouwen. 
2	De specialisaties onder EengezinsWoning en MeergezinsWoning zijn nu enkel gebaseerd op de manier van toegang. Overweeg om deze uit te breiden, bijvoorbeeld met studio's, lofts, woonwagens, of geschakelde woning. 
3.	Op dit moment hebben zowel WoonEenhedenObject als WoonEenheid een relatie met Doelgroep. Behoud bij voorkeur één van deze relaties zodat tegenstrijdige informatie wordt voorkomen. 
4.	De formele definitie van Functie is 'Activiteit met een doelgerichte output en een specifieke input.'. Dit strookt niet geheel met de manier waarop Functie wordt gebruikt in het onderdeel Woonobjecten. Overweeg om de definitie aan te passen of hier een andere klasse te gebruiken. 
5.	De relatie tussen twee WoonObjectRuimte is niet gedefinieerd. Definieer of verwijder deze relatie. 
6.	Er is geen relatie tussen WoonObjectRuimte en Fysieke Ruimte uit het topmodel. Overweeg deze toe te voegen. 
7.	Positioneer Bedruimte eenduidig als specialisatie van BinnenRuimte of VerblijfsRuimte, afhankelijk van de gekozen modelleerlogica.

**Reactie digiGO:**
ad 1. Goede suggestie. 'Woongebouw' is wel een echte entiteit, zeker in de Nederlandse juridische praktijk
ad 2. moet inderdaad gebeuren. In IMWO is een eerste voorzet gemaakt. Er dient in samenspraak met alle betrokkenen een volledige en consitatente classificatie tot stand te komen.
ad 3. gaan we bekijken
ad 4. Op zich een goede suggestie. De discrepantie tussen de functiebegrippen komt door de idiosyncratische taal van het Bbl.. Het zal moeilijk zijn van dit homoniem af te komen: enerzijds heb je het begrip nog voor alles wat een 'functie' heeft en anderzijds zit je in de Nederlandse praktijk aan het Bbl-begrip Functie vast. We kunnen wel het het Ministerie adviseren hun terminologie aan te passen.
ad 5. decompositie
ad 6. OK
ad 7. Bedruimte: weer zo'n Bbl-begrip


**Acceptatiecriteria / To-do:**
- [ ] Uitwerking Woonobjecten in Logsch modelproject. Naast uitwerking van een geharmoniseerde klassificatie uitwerking van de relatie met Bbl

**Labels:** `documentation`
**Prioriteit:** `Hoog`

---

## Ref #86: [Woonobjectruimte] - Uitwerking classificatie van Woonobjectruimten

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Onderdeel woonobjectruimten 
De ruimtetypologie van het onderdeel woonobjectruimten is grotendeels herkenbaar, maar enkele ruimten kunnen logischer worden gepositioneerd, zoals opgenomen in onderstaande lijst. 
1.	Overweeg Liftschacht en Galerij onder VerkeersRuimte te plaatsen. 
2.	Beoordeel of Trapgat en Vide daadwerkelijk ruimten zijn, of beter als opening, uitsparing of ruimtelijk element kunnen worden gemodelleerd. 
3.	Overweeg BergZolder toe te voegen als specialisatie onder FunctieRuimte.

**Reactie digiGO:**
ook hier weer: het gaat om een voorzet die samen met de betrokkenen tot een mooie consistente en volledige classificatie uitgewerkt zou moeten worden.. We nemen d suggesties zeker mee.


**Acceptatiecriteria / To-do:**
- [ ] Uitwerking classificatie van Woonobjectruimten

**Labels:** `bug`
**Prioriteit:** `Medium`

---

## Ref #87: [Installaties] - Uitwerking Installaties tot logisch model in een vervolgproject

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Onderdeel installaties 
Bij het onderdeel installaties is het van belang dat het onderscheid tussen een installatie als systeem en installatiecomponenten als onderdeel voldoende duidelijk wordt gemaakt. In onderstaande lijst zijn onze opmerkingen en suggesties voor het onderdeel installaties puntsgewijs opgenomen. 
1.	Overweeg om ook de complete Installatie onderdeel te laten zijn van het Bouwwerk, niet alleen de InstallatieComponenten via overerving. 
2.	Overweeg een relatie tussen InstallatieComponent en IfcDistributionElement toe te voegen. 
3.	Scherp de definitie van Installatie aan door te benadrukken dat het om een systeem van componenten gaat. Laat eventueel weg dat de installatie altijd noodzakelijk is voor het functioneren van het gebouw. 
4.	Heroverweeg AssetManagementInstallatie en GebouwManagementInstallatie; beide concepten lijken over hetzelfde te gaan. De term GebouwBeheerSysteem is onzes inziens gangbaarder. 
5.	Positioneer Brandveiligheidsinstallatie niet uitsluitend onder Werktuigbouwkundige installatie. Een brandmeldinstallatie, ontruimingsinstallatie en noodverlichting vallen onder Brandveiligheidsinstallatie maar zijn elektrotechnisch van aard. 
6.	Overweeg Sanitaire installatie en Elektradistributie-installatie (het geheel van groepen, kabels en stopcontacten) toe te voegen.

**Reactie digiGO:**
ad 1. OK. Is eigenlijk al zo: de installatie als geheel is ook een component.
ad 2. gaan we bekijken
ad 3. aanscherping definitie: goed idee; weglating noodzakelijkheid: dit staat wel in de brondefinitie
ad 4. OK. Dit was wel overgenomen uit de NL-SfB-classificatie
ad 5,OK. idem. Ook hier geldt weer: de classificatie is een voorzet. In dit geval is die van de NL-SfB overgenomen (op advies van de vertegenwoordiger van Techniek NL)
ad 6. gaan we bekijken


**Acceptatiecriteria / To-do:**
- [ ] Uitwerking Installaties tot logisch model in een vervolgproject. Hierbij streven naar een uniforme classificatie.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #88: [Onderdeel slimme woning] - Slimme woningproject

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Overweeg om de werking van slimme-woningconcepten explicieter te maken door vast te leggen hoe een sensorwaarde leidt tot een actie of aansturing door een actuator. Overweeg daarnaast om de relatie Beheerst te vervangen door Beïnvloed, omdat dit beter past bij indirecte aansturing.

**Reactie digiGO:**
latere uitwerking


**Acceptatiecriteria / To-do:**
- [ ] Slimme woningproject

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #89: [Juridische entiteiten] - Juridische objecten vervolgproject

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Onderdeel juridische objecten 
Overweeg om de aansluiting op bestaande juridische informatiemodellen te versterken door een expliciete relatie op te nemen tussen appartementsrecht uit IMKAD en Juridische ruimte uit IMWO. Daarmee kunnen eigendom, gebruik en ruimtelijke afbakening beter aan elkaar worden gekoppeld.

**Reactie digiGO:**
gaan we bekijken: wordt dan wel een relatie met appartementrechtsplitsing, aangezien een appartemantsrecht op zich niet gerelateerd is aan een ruimte


**Acceptatiecriteria / To-do:**
- [ ] Juridische objecten vervolgproject

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #90: [binnenruimtenetwerk] - Vervolgproject logisch model binnenruimtenetwerk

**Beschrijving:**
**Indiener:** Chiel van der Pas (BIM-Connected/ Quickscan)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Onderdeel binnenruimtenetwerk 
Omdat het binnenruimtenetwerk nog niet volledig is gemodelleerd, is dit onderdeel buiten de quickscan gehouden.


**Acceptatiecriteria / To-do:**
- [ ] Vervolgproject logisch model binnenruimtenetwerk.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #102: [Bouwwerk] - Nader onderzoeken

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Vragen, inhoudelijk
Waarom heeft pas een bouwwerk een reële component, en niet al een FysiekObject. Reële component lijkt al op FysiekObject toepasbaar. Voorstel: reële component naar abstractie fysiekobject, de onderliggende specialisaties op het niveau van bouwwerk intekenen

**Reactie digiGO:**
Goede suggestie.


**Acceptatiecriteria / To-do:**
- [ ] Nader onderzoeken

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #116: [Algemeen] - Uitwerking in vervolgproject, i

**Beschrijving:**
**Indiener:** Erwin Lazet (Syndetho BV)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Voor de doorontwikkeling van het GIR en de relatie met LVG lijken de juiste aansluitingen en entiteiten te zijn opgenomen. Verdere adoptie van het model irt GIR zal dit ook moeten gaan uitwijzen

**Reactie digiGO:**
Goed om te horen.


**Acceptatiecriteria / To-do:**
- [ ] Uitwerking in vervolgproject, i.c.m. LVG

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #121: [Algemeen] - Review item omtrent algemeen

**Beschrijving:**
**Indiener:** Erwin Lazet (Syndetho BV)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
"InstallatieComponent is een generalisatie van SlimmeWoning (Model) en Object Apparaat". Dit snap ik niet goed. Installatiecomponent is een soort(type) Product (ETIM class) en een instantie van een Product.

**Reactie digiGO:**
1. Een apparaat is een installatiecomponent. En tevens een product.
2. In het model gaat het alleen over typen (klassen). Zowel Installatiecomponent als Product kunnen geïnstantieerd worden.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #124: [Algemeen] - verbetering leesbaarheid

**Beschrijving:**
**Indiener:** Niek Pluijmert (VNG)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
1.  Figuur 11 Topmodel is ook na inzoomen niet (goed) leesbaar en er is geen legenda bij.
2.  In figuur 16 wordt een aantal objecten (studenten, arbeidsmigranten, bewonersinZorginstelling, asielzoekers en woongroepen) als meervoud gedefinieerd, normaal hanteren we voor objecten het enkelvoud.
3.  Objecttype observatie: in het CIM VTH Flo wordt het objecttype Bevinding gebruikt. Dit moet beter afgestemd, want definities zijn verschillend, IMWO gaat over dat wat sensoren meten en CIM VTH FLo gaat over wat mensen waarnemen. Gebruik het begrip Waarneming voor beiden (dus zowel wat mensen als wat sensoren waarnemen).
4. Het IMWO is mooi vanuit de theorie opgezet. Het voordeel is dat het compleet is en klopt, maar het is niet overal makkelijk toegankelijk of begrijpbaar. Daarom is een meer uitgebreide toelichting nodig hoe dit model praktisch moet worden toegepast.

**Reactie digiGO:**
ad 1. akkoord. 
ad 2. Het gaat hier om een type-aanduiding, niet om individuele studenten, arbeidsmigranten, etc.
ad 3. ?
ad 4. Mee eens, maar we hadden de prioriteit eerst het model compleet te hebben. In volgende versies zal de toelichting uitgebreid worden.


**Acceptatiecriteria / To-do:**
- [ ] verbetering leesbaarheid
- [ ] uitbreiding toelichting

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #13: [Installaties] - geen

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Wat doe je met installatiecomponent en inventariscomponent per woning of wooneenheid. Op het laagste niveau vastleggen moet het naar boven toe over erven in de reële componenten. De vraag alleen is of het realistisch is dat je hier een systematische vastlegging van kunt krijgen. In een BIM model obv vergunningverlening zit het wellicht al wel en wordt het voor bijv. de IBRO er weer weggefilterd.

**Reactie digiGO:**
Een woningbeheerder zoals een corporatie zal installatie- en inventariscomponenten zeker per woning/woonheid willen vastleggen en bijhouden, veelal zelfs per ruimte (zie ILS-woco). Overerving naar boven  geldt uiteraard voor meronomieën. Dit is algemeen geldig en hoeft niet in het conceptueel model vastgelegd te worden. Het is wel relevant als we modellen gaan vertalen, bijvoorbeeld IMWO ==> IMIBRO: dan moet die overerving naar behoefte geïmplementeerd worden,


**Acceptatiecriteria / To-do:**
- [ ] geen
- [ ] beproeven niveau van vastlegging installaties in user case

**Labels:** `enhancement`
**Prioriteit:** `Laag`

---

## Ref #14: [figuur 18] - in eerste instantie huisaansluiting koppelen aan het woonobject (VBO)

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Later in fig. 18 wringt het daar ook. Installaties op woonobject niveau of op bouwwerkniveau. Een Nutsaansluiting zit in mijn beleving altijd op woonobject niveau.

**Reactie digiGO:**
Er zullen idd aansluitingen zijn op meerdere niveaus. Dit moeten we nog eens goed bekijken.


**Acceptatiecriteria / To-do:**
- [ ] in eerste instantie huisaansluiting koppelen aan het woonobject (VBO). (Zoelas in het GIR).
- [ ] relatie installatiecomponent - bouwwerk in extenso analyseren en modelleren

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #15: [Bouwwerken] - zinsnede verwijderen of verduidelijken

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Par. 6.2 – Bouwwerken: Bijzonder zin in relatie tot definitie van bouwwerk, wat is de ratio hiervan? 
•	weggelaten: ’Of een ruimtelijk af te bakenen deel daarvan’; dit zou modellering van een deel van een groter bouwwerk (vleugel, segment, bouwdeel) als afzonderlijk bouwwerk mogelijk maken; een nieuwe term is dan toch te prefereren, bijvoorbeeld ‘deelbouwwerk’, en wel omdat de zelfstandigheid van het object een essentieel kenmerk van een bouwwerk is.

**Reactie digiGO:**
Waarschijnlijk is deze passage gebaseerd op de opvatting van MiniBIM over een bouwwerk, dat gedefinieerd wordt als 'de ruimtelijke demarcatie van een bouwkundig en constructief zelfstandige eenheid of een afsluitbaar deel van die eenheid.'. Deze demarcatie zou gehandhaafd kunnen worden, maar in IMWO zou dan een objecttype Deelbouwwerk geïntroduceerd moeten worden.


**Acceptatiecriteria / To-do:**
- [ ] zinsnede verwijderen of verduidelijken
- [ ] uitwerken in mapping IMWO-MiniBIM

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #16: [fig. 17] - Multifunctionele ruimte opnemen met subtypen

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Fig. 17 Woonobjectruimten: Binnenruimte – Verblijfsruimte – Woon/Keuken/Slaapruimte  Maak hier Mulitfunctionele ruimte van als het niet te duiden is.

**Reactie digiGO:**
Deze ruimtetypen komen uit ILS-Woco en zijn kennelijk in de praktijk nodig


**Acceptatiecriteria / To-do:**
- [ ] Multifunctionele ruimte opnemen met subtypen

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #17: [fig 21] - Nog eens goed bekijken en eventueel aanpassen

**Beschrijving:**
**Indiener:** Sandra Leijten / Theo de Smidt (Gemeente Rotterdam)
**Locatie:** Hoofdstuk 6.0

**Commentaar:**
Fig 21 Juridische objecten: Er worden relaties gelegd tussen IMWOZ – IMBAG – IMKAD objecten die nu losgekoppeld lijken te zijn.

**Reactie digiGO:**
Klopt. Dit is bedoeld als verduidelijking, maar is methodologisch niet juist. De relaties worden primair in de externe modellen gelegd.


**Acceptatiecriteria / To-do:**
- [ ] Nog eens goed bekijken en eventueel aanpassen.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #140: [FysiekObject] - Review item omtrent fysiekobject

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.1.10

**Commentaar:**
heeftTopologischeRelatieMet'
Mij is niet duidelijk waarom deze relatie zelf gedefinieerd wordt en niet isBoundBy of isConnectedTo gehanteerd wordt.

**Reactie digiGO:**
Er zijn heel veel topologische relaties tussen fysieke objecten, te herleiden tot een achttal hoofdgroepen. heeffTopologischeRelatieMet vat alle mogelijke relaties samen.


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #141: [GeografischeRuimte] - nagaan hoe het precies zit in NEN 2660 en actie dienaangaande

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.1.12

**Commentaar:**
GeografischeRuimte'
In NEN 2660 is GeometricEntity een Representation > InformationObject > Object > Entity > ConcreteConcept. Geometrie is daar dus een concreet informatieobject. Hetzelfde geldt voor TemporalEntity (ook onder Representation, dus concreet).
In IMWO wordt geometrie (AbstracteRuimte, GeometrischeRuimte) en tijd (Tijd) juist onder AbstractConcept gehangen als wiskundige ruimte. En via imwor:bronterm "Geometrische entiteit" claimt IMWO dat dit de NEN 2660-GeometricEntity is. Dat is volgens mij niet correct
Wat in de de NEN concreet/representationeel is, wordt in IMWO abstract/wiskundig.
IMWO's keuze is begrijpelijk (en misschien zelfs beter dan NEN 2660), maar het volgt dus niet de NEN2660 en dit zit een beetje verstopt

**Reactie digiGO:**
Ja, klopt. Ik ging uit van figuur 35 in NEN 2660-2, waarin een Geometrische entiteit, net zoals een Temporele entiteit, als een Abstract concept gezien wordt. Moeten we nader bekijken dus. Ik vind overigens 'representatie' geen adequate vlag voor de lading Geometrische entiteit. Een geometrische entiteit kan wel gebruikt worden om een object te representeren, maar is an sich een 'existentieel onafhankelijke entiteit' lijkt me.


**Acceptatiecriteria / To-do:**
- [ ] nagaan hoe het precies zit in NEN 2660 en actie dienaangaande

**Labels:** `enhancement`
**Prioriteit:** `Laag`

---

## Ref #142: [ReeelGeoObject] - vooralsnog geen

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.1.17

**Commentaar:**
In NEN 3610 staat dat het NEN 3610 reëel object overeenkomt met het NEN 2660 technisch reëel object. Dan wordt dus verondersteld dat een NEN 2660 een vaste plaats t.o.v. het aardoppervlak hebben; dat is maar de vraag. Verder blijkt uit de zin 'Een reëel of fysiek object is een tastbaar begrensd object dat gekenmerkt wordt door zijn materiele samenstelling en structuur.' dat reëel en fysiek als synoniemen gebruikt mogen worden. Dat isnin strijd met NEN 2660'
Dit is inderdaad een correcte bevinding en een best wel onhandig punt. Misschien kan Michel of Paul hier wat over zeggen?

**Reactie digiGO:**
afstemming NEN 2660 en NEN3610 lijkt geen luxe


**Acceptatiecriteria / To-do:**
- [ ] vooralsnog geen
- [ ] aankaarten afstemming NEN2660 - NEN3610 bij de respectieve commissies

**Labels:** `enhancement`
**Prioriteit:** `Laag`

---

## Ref #137: [Begrip Concept] - tekst aanpassen

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.1.4.

**Commentaar:**
Maar wat is 'existentieel onafhankelijk'.
In mijn beleving betekent dat het concept op zichzelf kan bestaan, in tegenstelling tot een eigenschap zoals 'kleur', die alleen kan bestaan aan een object

**Reactie digiGO:**
OK


**Acceptatiecriteria / To-do:**
- [ ] tekst aanpassen

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #138: [Begrip Concept] - nagaan betekenis 'Top'in 'TopComcept'

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.1.4.

**Commentaar:**
NEN2660Element'
Zou dit niet simpeler zijn als je gewoon nen2660:TopConcept direct gebruikt?

**Reactie digiGO:**
zou kunnen, ons is echter de prefix 'top'niet duidelijk


**Acceptatiecriteria / To-do:**
- [ ] nagaan betekenis 'Top'in 'TopComcept'

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #139: [FysiekeRuimte] - Nadere bepaling van terminologie rond 'FysiekeRuimte'

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.1.9

**Commentaar:**
FysiekeRuimte' sluit als term het beste aan bij het beeld van de meeste mensen'
Ik snap de redenering wel. Maar ik vind toch dat als je de NEN2660 volgt je dan ook wel binnen die terminologie moet blijven. Daar komt bij dat 'Ruimte' en 'Space' zoals de NEN2660 ze hanteert ook echt ontologisch anders zijn en dus FysiekeRuimte wellicht tot verwarring kan leiden.

**Reactie digiGO:**
Gaan we bekijken.


**Acceptatiecriteria / To-do:**
- [ ] Nadere bepaling van terminologie rond 'FysiekeRuimte'

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #153: [Pand] - herstellen

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.2.13

**Commentaar:**
Lijkt gelijke definitie te hebben met IBRO pand dus geen generalisatie maar hetzelfde..

**Reactie digiGO:**
Het is een foutje: de relatie is 'bevatPand'.


**Acceptatiecriteria / To-do:**
- [ ] herstellen

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #143: [Materiaal] - usecase/vervolgproject Paspoorten

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.2.16

**Commentaar:**
Materiaalheeft relatie metisSamengesteldUitNEN2660Materie'
Deze redentatie ontgaat me ook even. Waarom zou dit niet gewoon nen2660:Matter zijn?

**Reactie digiGO:**
begrippen 'materiaal' en 'materie' moeten we nog een keer goed uitzoeken. Bijvoorbeeld in het kader van een usecase 'materiaalpaspoorten'.


**Acceptatiecriteria / To-do:**
- [ ] usecase/vervolgproject Paspoorten. Daarin specifieke analyse van de termen Materie en Materiaal

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #154: [Trap] - nadere uitwerking in het kader van de klassificatie van Bouwcomponenten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.3.15

**Commentaar:**
Ik mis het verschil tussen trap en ladder en daartussen de vlizotrap. een belangrijk verschil.

**Reactie digiGO:**
Is een ladder een BouwComponent? Ja, als het een vaste ladder is. Anders lijkt het me meer een inventariscomponent. Een Vlizotrap is een specialisatie van Trap. Wellicht te gedetailleerd voor dit informatiemodel.


**Acceptatiecriteria / To-do:**
- [ ] nadere uitwerking in het kader van de klassificatie van Bouwcomponenten

**Labels:** `enhancement`
**Prioriteit:** `Hoog`

---

## Ref #144: [Wand] - verwijzing aanpassen

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.3.19

**Commentaar:**
IMWO00TechnischeEntiteit'
Deze komt een beetje uit de lucht vallen en wordt nergens anders gebruikt volgens mij. Wordt hier de nen2660:TechnicalEntity bedoeld? Dan moet deze nog vaker aangehaald worden volgens mij.

**Reactie digiGO:**
TechnischeEntiteit komt als zodanig niet voor in IMWO


**Acceptatiecriteria / To-do:**
- [ ] verwijzing aanpassen

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #155: [Functieruimte] - Definitief bepalen in het kader van uniformering van e klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.4.11

**Commentaar:**
In een functiegebied gelegen ruimte. Een functiegebied is een gebruiksgebied of een gedeelte daarvan, waar de voor die gebruiksfunctie kenmerkende activiteiten anders dan het verblijven van personen plaatsvinden;'
overige inpandige ruimten (WOZ). functieruimte is verwarrend. Bergruimte is beter. waarom Functieruimte? dat klinkt meer als een verzamelnaam.

**Reactie digiGO:**
De term 'Functieruimte' komt uit het Bbl en is inderdaad zeer ongelukkig. 'Bergruimte' kan, maar dekt niet alle 'activiteiten anders dan het verblijven vn personen'. Nader te bepalen.


**Acceptatiecriteria / To-do:**
- [ ] Definitief bepalen in het kader van uniformering van e klassificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #145: [Algemeen] - ontdubbelen

**Beschrijving:**
**Indiener:** Rik Opgenoort (Commissie NEN2660)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.4.11

**Commentaar:**
FunctieRuimte is gerelateerd aan heeftRelatieMet Woonobjecten FunctieRuimte'
Lijkt dubbel?

**Reactie digiGO:**
idd.


**Acceptatiecriteria / To-do:**
- [ ] ontdubbelen

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #148: [WoonGebouw] - Definitie 'Woongebouw'nader bepalen

**Beschrijving:**
**Indiener:** Leon van der Zanden (CorpoNet, Woonbedrijf)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.4.30

**Commentaar:**
WoonGebouw'
Rare naam. Er zijn dus veel gebouwen waar niet alleen in gewoond wordt maar waar ook winkels, zorg, kantoren in 1 en hetzelfde gebouw zijn ondergebracht. Hoe moet ik dit nu lezen?

**Reactie digiGO:**
Dit moet nader bepaald worden.Het Bbl definieert een woongebouw als'gebouw of gedeelte daarvan met alleen woonfuncties en nevengebruiksfuncties daarvan, waarin meer dan een woonfunctie ligt die is aangewezen op een gemeenschappelijke verkeersroute;' Een gebouw met woningen en één winkeltje erin is dan al geeen woongebouw meer. De definitie van IMIBRO is weer ruimer, maar waar precies de grens ligt?


**Acceptatiecriteria / To-do:**
- [ ] Definitie 'Woongebouw'nader bepalen

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #149: [Woonobjectruimten] - Aanvullingen verwerken in het kader van de classificatie van ruimten

**Beschrijving:**
**Indiener:** Leon van der Zanden (CorpoNet, Woonbedrijf)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5

**Commentaar:**
Woonobjectruimten
Ik mis de Entresol.
Verder wordt voorbij gegaan in mijn beleving aan de situatie waarbij er sprake is van gestapelde bouw die zowel voor wonen als voor commerciële en of zorg doeleinden wordt aangewend.

**Reactie digiGO:**
Goede aanvulling!
Reactie Mirjam Donders: 
voor de zekerheid wat voorbeeldjes. https://www.vtwonen.be/binnenkijken/unieke-villa-luxe-entresol~23e5d19. https://watismijnhuiswaard.com/entresol/, https://architectenweb.nl/projecten/project.aspx?id=38152
digiGO: Aan een goede klassificatie van woonobjectruimten dient nog veel aandaxcht besteed te worden.


**Acceptatiecriteria / To-do:**
- [ ] Aanvullingen verwerken in het kader van de classificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #156: [Woonobjectruimten] - Aanvullingen verwerken in het kader van de classificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5

**Commentaar:**
Ik mis de tuinkamer, een dichtgemaakte overkapping. Niet helemaal de logia en ook niet de serre. Hij is veelal aan een kant geplaatst tegen een bestaand bouwwerk, maar dat hoeft niet (kan ook vrijstaan), en is niet verwarmd, geïsoleerd en met veel glas omsloten. https://www.countrywood.nl/luxe-tuinkamer-royal-douglas-900x400-cm-buitenverblijf-excellent-hillhout, https://verandaglas.com/wp-content/uploads/2023/08/lp12.jpg

**Reactie digiGO:**
Tuinkamer zouden we inderdaad moeten toevoegen, lijkt me.


**Acceptatiecriteria / To-do:**
- [ ] Aanvullingen verwerken in het kader van de classificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #157: [Atrium] - Review item omtrent atrium

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.1

**Commentaar:**
'binnen-atrium toch gewoon een vide?'
ja

**Reactie digiGO:**
!


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #158: [ExterneBergRuimte] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.11

**Commentaar:**
'met ook andere functies.'
Waarom ook andere functies? een schuurtje in de tuin is een externe bergruimte zonder andere functies.

**Reactie digiGO:**
mee eens


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #159: [ExterneBergRuimte] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.11

**Commentaar:**
'I npandig'
Inpandig wordt gebruikt als het in het pand van de woning ligt. je moet geen onderscheid maken of als criterium benoemen dat hij binnendoor bereikbaar moet zijn, dat is beheertechnisch niet te doen. dat het buiten de schil van het gebouw ligt zegt al voldoende.

**Reactie digiGO:**
mee eens


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #160: [Gang] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.14

**Commentaar:**
'Een langwerpige doorgangsruimte'
Lijkt erg op de corridor. Is het maken van een verschil noodzakelijk? zo ja, dan dat verschil duidelijker beschrijven.

**Reactie digiGO:**
Een corridor is een gang in een gemeenschappelijke ruimte. Misschien moeten we een corridor als een specialisatie van een Gang definiëren.


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #161: [Garage] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.15

**Commentaar:**
"Meestal" geeft ook aan dat het niet zo zou kunnen zijn en daarmee is het een irrelevant gegeven. Binnen de BAG is een doorgang niet nodig, het is beheerstechnisch ook niet bij te houden.

**Reactie digiGO:**
mee eens


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #162: [Garage] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.15

**Commentaar:**
'uitpandige garage'
vrijstaande garage (want een garage zit wel in een gebouw/pand dus kan niet uitpandig zijn). de vrijstaande gerage staat niet tegen de woning aan, zit in een ander gebouw.
Een wat als de deur naar binnen opent? een roldeur bijvoorbeeld. deze detaillering weghouden.
Een garage is niet gebonden aan een woning maar dienstbaar aan de woning. gebonden kangelezen worden als "verbonden".

**Reactie digiGO:**
mee eens. NB deze definitie is die van de bron Aedes IM en hebben we niet overgenomen in IMWO!


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #163: [Loggia] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.29

**Commentaar:**
Een loggia ligt op een verdieping en niet "meestal". Aangegeven wordt dat het een Inpandig balkon is en een balkon ligt niet gelijkvloers… daarmee wordt neem ik aan een verdieping bedoeld. (zie definitie balkon)

**Reactie digiGO:**
betreft MiniBIM, niet IMWO


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #164: [Trapgat] - Verwerken in het kader van de klassificatie van ruimten

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)
**Locatie:** Hoofdstuk 7.0, Paragraaf 7.5.44

**Commentaar:**
Definitie lijkt niet te kloppen: “LegeRuimte tussen de ruimte voor een Trap en de Vide daarboven.” Hoezo “vide”? een vide is lucht, een gat. Dus een trapgat is de ruimte voor een trap en het gat erboven? Een trapgat en vide kunnen wel tegen elkaar aanliggen als niet de hele verdieping dicht is maar naast de trap een gat naar beneden heeft.

**Reactie digiGO:**
Tja, ik betrek het trapgat alleen op het gat in de vloer.


**Acceptatiecriteria / To-do:**
- [ ] Verwerken in het kader van de klassificatie van ruimten

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #101: [Beheer GEBORA] - meenemen in volgende versie

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 8.0, Paragraaf 8.

**Commentaar:**
Hoe gaat met model om met de levenscyclus van het vastgoed, zie de Gebora? Hierin is de functie van fysieke objecten een apart concept dat in de tijd kan veranderen. Hiervoor zou je functioneel mogelijk los willen modelleren van fysiek, of functionele instanties mogelijk maken.

**Reactie digiGO:**
Gebora wordt gevolgd. Het tijdsaspect dientt nog wel utgewerkt te worden, zodat bijvoorbeeld verandering in functie van objecten in het model geïncorporeerd kan worden. Wel is al opgenomen dat een object naast een inherente functie een feitelijke functie kan hebben (figuur 15).


**Acceptatiecriteria / To-do:**
- [ ] meenemen in volgende versie
- [ ] Tijdsaspect inbouwen in IMWO

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #102: [Beheer] - In de volgende versie de inhoudelijke relatie met Gebora expliciteren

**Beschrijving:**
**Indiener:** CORA/ Aedes Jan Fock, VIncent Breuking (CORA/ VERA Aedes)
**Locatie:** Hoofdstuk 8.0, Paragraaf 8.

**Commentaar:**
Dit is een werkgroep van de Gebora, worden de constateringen verwerkt in de Gebora en wat is het vervolg?

**Reactie digiGO:**
Ja, er wordt teruggekoppeld naar Gebora. Verder wordt er een beheerorganisatie opgezet , volgende versies voorbereid en uitwerkingsprojecten samen met de stekeholders opgezet.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie de inhoudelijke relatie met Gebora expliciteren

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #20: [bouwlaag] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0, Paragraaf Aedes Informatiemodel Vastgoed 0.9

**Commentaar:**
Zowel in de indeling, meting van Gebruiksoppervlakte als bij de bouwkundige opnamestaat wordt dit gebruikt.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #21: [buitenruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0, Paragraaf Aedes Informatiemodel Vastgoed 0.9

**Commentaar:**
Er kan sprake zijn van gebouwgebonden buitenruimte of een beschrijving van de buitenruimte zoals tuin, erf, oprit etc.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #22: [gebouw] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0, Paragraaf Aedes Informatiemodel Vastgoed 0.9

**Commentaar:**
Taxateurs taxeren een gebouw (of een gedeelte daarvan)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #24: [Bbl: gebruiksgebied] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt niet in het rapport opgenomen, maar de taxateur moet in zijn onderzoek naar omgevingsplannen hier wel rekening mee houden

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #25: [Bbl: woonfunctie] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Als de gebruiksfunctie wonen is of er is sprake van de activiteit wonen of de locatie is 'wonen' dan heeft de woning een woonfunctie.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #26: [ILS O&E: Dak] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
dit onderdeel wordt meegenomen in de bouwkundige opnamestaat

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #27: [ILS O&E: Fundering] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
dit onderdeel wordt meegenomen in de bouwkundige opnamestaat (tenzij bedoeld wordt wat voor soort type fundering onder de woning zit, want dat volgt uit het funderingsrisicorapport dat een bijlage is bij het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #28: [ILS O&E: Raam] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
dit onderdeel wordt meegenomen in de bouwkundige opnamestaat

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #29: [ILS O&E: Vloer] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
dit onderdeel wordt meegenomen in de bouwkundige opnamestaat

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #30: [ILS O&E: Wand] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
dit onderdeel wordt meegenomen in de bouwkundige opnamestaat

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #31: [ILS O&E: KadastraalPerceel] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Dit onderdeel is in hoofdstuk G van het taxatierapport opgenomen

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #32: [ILS Spaces: Tuin] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Dit onderdeel is in hoofdstuk H van het taxatierapport opgenomen (maar dan beschrijvend).

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #33: [IMBAG: Adresseerbaar object] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Het adres van het getaxeerde moet een BAG registratie hebben tenzij er sprake is van nieuwbouw die nog niet vergund is.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #34: [IMBAG: Pand] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Het pand dat wordt getaxeerd

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #35: [IMBAG: Verblijfsobject] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Andere term voor pand

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #36: [IMBAG: Woonplaats] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
de plaats waar het object is gelegen

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #37: [IMIBRO: AdresseerbaarObject] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
zie regel 209

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #38: [IMIBRO: Benedenwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #39: [IMIBRO: Bovenwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #40: [IMIBRO: Corridorflatwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport (corridorflat)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #41: [IMIBRO: Dakkapel] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt in de bouwkundige opnamestaat

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #42: [IMIBRO: Eindwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #43: [IMIBRO: Galerijflatwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #44: [IMIBRO: GeschakeldeTweeOnderEenKapWoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport (geschakelde 2-onder-1-kapwoning)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #45: [IMIBRO: GeschakeldeWoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport (geschakelde woning)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #46: [IMIBRO: Maisonnette] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #47: [IMIBRO: Object] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zo noemen wij in de volksmond het getaxeerde (object)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #48: [IMIBRO: Pand] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Vanuit de BAG komt er een pandid beschikbaar voor het hele pand waarbij 1 of meerdere objecten in zijn gelegen. NWWI gebruikt die intern

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #49: [IMIBRO: Portiekflatwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport (portiekflat)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #50: [IMIBRO: Portiekwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #51: [IMIBRO: Tussenwoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #52: [IMIBRO: TweeOnderEenKapWoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport (2-onder-1-kapwoning)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #53: [IMIBRO: VrijstaandeWoning] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Wordt gebruikt bij woningtype (fotowijzer woningen) in het taxatierapport (Vrijstaande woning)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #54: [IMIBRO: Woonfunctie] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zie eerdere opmerking over deze term in kader van omgevingswet (bestemming)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #55: [IMKAD: KadastraalObject] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
NWWI gebruikt brondata van het Kadaster (eigendomsinformatie) die de taxateur gebruikt bij het invullen van het taxatierapport. Regel 413-424 worden gedeeltelijk geautomatiseerd ingevuld in het taxatierapport.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #56: [IMKAD: LocatieKadastraalObject] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
locatie van het getaxeerde object (hoofdstuk C)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #57: [IMKAD: Perceel] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Gegevens van het perceel (als grondgebonden woning / hoofdstuk G.2.a.)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #58: [IMKAD: Appartementsrecht] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Gegevens van het appartementsrecht (als appartement / hoofdstuk G.2.b.)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #59: [IMKAD: ZakelijkRecht] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Welke eigendomssituatie wordt nu getaxeerd (hoofdstuk G van het rapport)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #60: [IMKAD: Mandeligheid] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Of er sprake is van een mandelig perceel (hoofdstuk G)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #61: [IMKAD: AppartementsrechtSplitsing] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Of er sprake is van een splitsing in appartementsrechten (hoofdstuk G.2.b)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #62: [IMKAD: PubliekrechtelijkeBeperking] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Of er sprake is van publiekrechtelijke beperkingen (hoofdstuk O)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #63: [IMKAD: OnroerendeZaakBeperking] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Of er sprake is van publiekrechtelijke beperkingen (hoofdstuk O) of eigendomsgebonden beperkingen (hoofdstuk G.2)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #64: [MiniBIM: WoningType] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zie fotowijzer woningen (hoofdstuk C)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #65: [MiniBIM: Perceel] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Dit is te vinden in hoofdstuk G.2.a.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #70: [ILS O&E: complex] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
De term voor 'complex' wordt bij taxateurs alleen gebruikt bij appartementen waarin een appartement gelegen is in een complex (van appartementen).

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #71: [ILS O&E: gebouw] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Een taxateur taxeert een gebouw of een gedeelte daarvan

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #72: [ILS O&E: bouwlaag] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
In de indeling en in de bouwkundige opnamestaat geeft de taxateur per bouwlaag aan welke voorzieningen aanwezig zijn.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Laag`

---

## Ref #73: [ILS O&E: ruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
In de indeling en in de bouwkundige opnamestaat geeft de taxateur per ruimte aan welke voorzieningen aanwezig zijn.

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #74: [ILS O&E: Adres] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Elke taxatie bevat een uniek adres (straat, huisnummer, huisnummertoevoeging, postcode en plaats)

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #75: [ILS O&E: Verdieping] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Het is mogelijk dat een object op een verdieping ligt of uit meerdere verdiepingen bestaat. Wordt dat hiermee bedoeld?

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #76: [ILS O&E: Gebouwgebonden buitenruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
In de Meetinstructie gebruiksoppervlakte woningen juli 2019 wordt dit element benoemd en in het taxatierapport opgenomen

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #77: [ILS O&E: Binnenruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Waarom wordt dit niet nader uitgewerkt?

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #78: [ILS O&E: Gebouwgebonden buitenruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
In de Meetinstructie gebruiksoppervlakte woningen juli 2019 wordt dit element benoemd en in het taxatierapport opgenomen

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #79: [ILS O&E: toiletruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Deze wordt, samen met de badkamer ook door de taxateurs opgenomen in de indeling en bouwkundige opnamestaat

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #23: [Bbl: gebruiksfunctie] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Sinds de omgevingswet zijn intrede heeft gedaan moet de taxateur onderzoeken welke gebruiksfunctie het object heeft (mag je er wonen zonder 'belemmeringen')

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #66: [gebruiksoppervlakte gebouwgebonden buitenruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zie Meetinstructie Gebruiksoppervlakte woningen BBMI en hoofdstuk H. van het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #67: [gebruiksoppervlakte wonen] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zie Meetinstructie Gebruiksoppervlakte woningen BBMI en hoofdstuk H. van het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #68: [gebruiksoppervlakte overige inpandige ruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zie Meetinstructie Gebruiksoppervlakte woningen BBMI en hoofdstuk H. van het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #69: [gebruiksoppervlakte externe bergruimte] - In de volgende versie van IMWO taxatierapportage expliciet verwerken

**Beschrijving:**
**Indiener:** Jan Pieter Redert (NWWI)
**Locatie:** Hoofdstuk 12.0

**Commentaar:**
Zie Meetinstructie Gebruiksoppervlakte woningen BBMI en hoofdstuk H. van het taxatierapport

**Reactie digiGO:**
In deze versie van IMWO zijn nog niet alle details verwerkt.


**Acceptatiecriteria / To-do:**
- [ ] In de volgende versie van IMWO taxatierapportage expliciet verwerken. Mogelijk een uitwerkingproject definiëren. De input vanuit taxatie meenemen in de relevante klassificaties.

**Labels:** `documentation`
**Prioriteit:** `Medium`

---

## Ref #118: [Algemeen] - Review item omtrent algemeen

**Beschrijving:**
**Indiener:** Mirjam Donders (Rotterdam Mercator / DATA-Kracht)

**Commentaar:**
Ja, heb ik als annotatie opgenomen.

**Reactie digiGO:**
?


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Medium`

---

## Ref #125: [Algemeen] - Review item omtrent algemeen

**Beschrijving:**
**Indiener:** Paul Oude Luttighuis (project Landelijke Voorziening Gebouwgegevens)

**Commentaar:**
Zie de suggestie/wens bij 6.

**Reactie digiGO:**
?


**Acceptatiecriteria / To-do:**
- [ ] Analyseer het commentaar en bepaal de benodigde aanpassing.

**Labels:** `enhancement`
**Prioriteit:** `Laag`
