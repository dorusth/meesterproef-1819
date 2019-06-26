# Reflectie



## Inhoud
- [Leerdoelen](#Leerdoelen)
	- [Web design](#WebDesign)
		- Exclusive design
		- Testen voor een beter ontwerp
	- [RTW](#RTW)
		- Data management
		- Client-server interactie
		- Multi user support
	- [WAFS](#WAFS)
		- App structuur
		- Routes
		- Data manipulatie
- [Reflectie samenwerking](#Reflectiesamenwerking)


## Leerdoelen

### Web Design
- Exclusive design:
	- Het Jiskefet project is specifiek voor de shifters die bij cern werken aan het alice project, Dit is een kleine groep mensen met veel kennis over natuurkunde en de deeltjesversneller.
	- Hierdoor kan je ontwerpen voor Exclusieve groep die veel kennis heeft van het project door oa. een 3-daagse cursus over het platform en het bijhouden van de data.
	Door deze bevinding hebben wij delen van het platform complexer kunnen maken aangezien er rekening gehouden kan worden met voorkennis van de gebruikers.
	- Ook is er rekening gehouden met de setting waarin de gebruikers zullen werken en het platform gebruiken om functionaliteiten voor die use case in te zetten.
	- Door veel te onderzoeken/interviewen met (oud)medewerkers van cern hebben we veel informatie kunnen verzamelen over de manier waarop zij het product zullen gebruiken en daar het platform aan te passen


- Testen beter ontwerp
	- Voor het project zijn we bezig geweest om zoveel mogelijk informatie te verzamelen over hoe de gebruikers het platform gebruiken om daar in de usability rekening mee te houden.
	- Ook zijn we bezig geweest met het testen met "gebruikers" waaronder 2 testers die ook natuurkunde studeren en kennis hebben over het onderwerp.
	- Door oa. met eye-tracking te testen hebben we het ontwerp kunnen verfijnen voor de gebruikers.


### RTW
- Data management
	- In het platform wordt veel (meta)data verwerkt over de runs en bijbehorende logs van het platform.
	- Hiervoor ben ik bezig geweest met het uitzoeken hoe in React de flow van data gaat tussen components om hier interactie en tijdige updates door te voeren.
	- De dataset die gebruikt werd voor het project bleek niet heel betrouwbaar te zijn en hierdoor hebben wij besloten een eigen "API" te bouwen om consistent met data te kunnen werken


- Client-server interactie
	- Hiervoor ben ik bezig geweest met interacties toevoegen tussen verschillende componenten binnen het platform data weer te geven.
	- Dit is vooral te zien bij de "Log overview" pagina van het platform waar een overview is van de runs, maar ook een previewer waar op basis van interactie de juiste informatie weergegeven wordt van de logs.
	- Dit is vooral een leerdoel geweest van de manier waarop React met states, props en het doorgeven van interactie om gaat.


### WAFS
- App structuur
	- Na het Vooral werken met het native in elkaar zetten van apps gedurende de minor hebben wij bij dit project gekozen om met NEXT(node+react) te werken als framework.
	- Voor structuur geeft dit een andere manier van kijken hoe je omgaat met componenten, maar na het opzetten geeft dit een efficiënte workflow.
	- Het voornamelijkste wat ik hiervan heb geleerd is de flow van data tussen verschillende componenten in de app en hoe dat invloed heeft.
	- Een van de problemen die ik tegenkwam is dat wanneer je afhankelijk bent van data voor het renderen van van pagina's er hele delen of hele pagina's weg kunnen vallen wanneer er problemen zijn met de data.
	- Door duidelijk af te stemmen wie aan welk deel van de app zou werken hebben wij wel problemen met merge conflicts etc. kunnen vermijden.


- Routes
	- Binnen Next wordt routing automatisch afgehandeld op basis van de page files die jij aanmaakt.
	- Doordat dit automatisch gaat was het wel moeilijker om dynamische routing toe te voegen aan de app, uiteindelijk was dat voor ons proof of concept geen probleem en kon er dus met simpele routing gewerkt worden.


- Data manipulatie
	- Data manipulatie toepassen is een deel wat heel soepel ging bij het weergeven van de data aangezien het veel data is dat direct vanuit sensoren etc. komt.
	- met gebruik van packages zoals Moment.js was het formatteren van data zoals timestamps makkelijk op te lossen voor de overviews.



## Reflectie samenwerking
Aan het begin van het project wist ik niet goed wat ik moest verwachten van het samenwerken in een team met 2 UX-designers en een andere developer.
Het team hadden wij gelukkig al vooraf samengesteld en we waren al bekend met elkaar wat hielp bij de verwachtingen en samenwerking.
Als team waren wij het er redelijk snel over eens dat het wegwerken van de backlog van Jiskefet niet de richting was waar wij in wilde gaan.
Wij hebben vervolgens de keuze gemaakt om bezig te gaan met het redesign en samen bezig te gaan met het nieuwe ontwerp.
Door de grote van het project is er voor ons veel tijd in het onderzoek naar ALICE en de shifters gaan zitten om insights te verzamelen.
Door deze keuze zijn Marcel en ik ook veel in het design proces gebleven vanuit het technisch oogpunt met als technisch doen een proof of concept prototype.
Doordat wij de focus snel hadden konden wij het werk ook goed verdelen waardoor iedereen een goed aandeel kon leveren en als er onenigheid was kon dit altijd redelijk snel besproken en uitgepraat worden en zijn er geen grote problemen ontstaan.
Al met al kan ik wel zeggen dat dit een van de beste samenwerkingen is geweest die ik op CMD heb gehad en ben ik heel tevreden over het resultaat.
