# Design rationale

![dashboard](./img/dashboard.png)

## Inhoud
- [Case](#Case)
- [Probleem](#Probleem)
- [Oplossing](#Oplossing)
- [Techstack](#Techstack)
- [Uitwerking](#Uitwerking)

## Case
Bij het ALICE (A Large Ion Collider Experiment) project van CERN is een nieuw platform nodig om meta data te verwerken die van de sensoren in de deeltjesversneller af komt.
Hiervoor worden verschillende platformen gebruikt, maar er is een platform nodig voor het bijhouden van logs over deze data.


## Probleem
Voor het platform was al een team van software engineering begonnen met de technische uitwerking, maar hierbij miste nog een vertaalslag naar een visual front-end.
Hierbij zagen wij de kans om een passende oplossing te vinden om ene goede gebruikerservaring te creeren voor de shifters die bij CERN aan het ALICE project zitten.

## Oplossing


## Techstack
De techstack die wij hebben gebruikt voor het project bestaat uit:
#### Server
- Next.js
	- Voor de server maken wij gebruik van Next.js, dit is een framework om serverside pagina's voor react apps te genereren.
	- Met Next is het mogelijk om voor pagina's een gedeelte van data vooraf al klaar te zetten zoals data van api's en databases en hiervan een versie naar de client te sturen die daar als een normale react app wordt afgehandeld.
	- Next maakt routing ook makkelijker door dit te baseren op de files in de pages map
- Storybook
	- Voor het bijhouden van components binnen het platform hebben wij gekeken naar Storybook om voor volgende teams die hiermee werken een inzicht te geven in de components die gebruikt en beschikbaar zijn.


#### Client
- React
	- Wij hebben gekozen om voor dit project React te gebruiken als front-end framework, dit omdat:
		- Wij hier beiden al ervaring mee hadden
		- De manier waarop React met states en components updaten omgaat voor deze app handig leek met de hoeveelheid data die er binnen komt en wordt verwerkt.
	- React maakt gebruik van een javascript subset(JSX) om pagina's te genereren met daarin functionaliteiten ingebouwd zoals delen modulair maken waardoor er meer/minder toegevoegd worden op basis van de data.
	- Door de manier waarop React met data omgaat worden alleen de delen die beinvloed worden door de data aangepast/geüpdate waardoor de pagina's minder zwaar zijn om te laden.
- D3
	- D3 gebruiken wij om data te visualiseren over runs die binnen komt.
	- Wij hebben gekozen voor D3 omdat dit een uitgebreide library is om te gebruiken en Marcel hier al kennis van had.
- Moment
	- Moment gebruiken wij om de timestams etc. uit de dataset te formateren naar begrijpelijke tijdsnoteringen
- Material design als design system
	- Na overleg met onze UX-designers hebben wij besloten Material design te gebruiken als design system binnen het platform. Deze keuze is tot stand gekomen door de aard van het project. Het jiskefet project is een project dat een wisselende samenstelling heeft van teams die er aan werken, voornamelijk bestaand uit ICT studenten.
	- Door de wisselende opstelling binnen het project is het wel belangrijk dat er consistentie en houvast is met een duidelijke documentatie voor de volgende teams.
	Het zelf bouwen van een design system viel niet binnen onze scope van het project en daardoor hebben wij gekeken naar een bestaand design system met goede documentatie dat herkenbaar is voor gebruikers.
	- Ook is visuele identiteit niet heel belangrijk binnen dit platform, maar usabillity en herkenbaarheid is wel een belangrijke factor.

## Uitwerking
