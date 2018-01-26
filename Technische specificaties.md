# Technische specificaties

Dit document bevat een uitwerking van de technische specificaties die voortvloeien uit het referentiedocument. In dit document is het volgende opgenomen:

1. Specificaties van de structuur van het register
2. Specificaties van de (gebruikers)interface
3. User stories
4. To be discussed

## 1. Specificaties van de structuur van het register

#### Welke gegevens moet het register kunnen bevatten?

1. Gegevens over de organisatie


2. Gegevens over de verwerking

| Naam verwerkingsactiviteit |  |
| ------------- | ------------- |
| Voorvraag: | Wanneer is sprake van een nieuwe verwerkingsactivteit? |
| Soort: | Open veld |

| Doeleinde verwerkingsactiviteit |  |
| ------------- | ------------- |
| Omschrijving ||
| Soort: | Open veld, meerdere entries mogelijk |

| Categorieën betrokkenen |  |
| ------------- | ------------- |
| Omschrijving ||
| Soort: | Open veld, meerdere entries mogelijk |

| Categorieën persoonsgegevens |  |
| ------------- | ------------- |
| Omschrijving ||
| Voorvraag: | Bijzonder en/of Algemeen |
| Soort: | Open veld |

| Verwerkingsgrondslag (algemeen) |  |
| ------------- | ------------- |
| Omschrijving ||
| Soort: | Dropdown, afhankelijk |
| Optie 1: | Toestemming betrokkene (art. 6.1 (a) AVG) |
| Optie 2: | Noodzakelijk voor de uitvoering van een overeenkomst (art. 6.1 (b) AVG) |
| Optie 3: | Wettelijke verplichting (art. 6.1 (c) AVG) |
| Optie 4: | Bescherming vitale belangen betrokkene of andere natuurlijke personen (art. 6.1 (d) AVG) |
| Optie 5: | Taak van algemeen belang of uitoefening van het openbaar gezag (art. 6.1 (e) AVG) |
| Optie 6: | Gerechtvaardigde belangen van de verwerkingsverantwoordelijke of van een derde (art. 6.1 (f) AVG) |

| Verwerkingsgrondslag (bijzonder) |  |
| ------------- | ------------- |
| Omschrijving ||
| Soort: | Dropdown, afhankelijk |
| Uitdrukkelijke toestemming | art. 9.2(a) AVG |

| Categorieën ontvangers |  |
| ------------- | ------------- |
| Omschrijving ||
| Soort: | Open veld, meerdere entries mogelijk |
| Uitdrukkelijke toestemming | art. 9.2(a) AVG |


#### Voorbeeldstructuur

```JavaScript

Organisatie = {
	Naam: <naam organisatie>,
	Adresgegevens: <adres organisatie>,
	KVK-nummer: <KVK-nummer organisatie>,
	E-mailadres: <e-mailadres organisatie>,
	Telefoon: <Telefoonnummer organisatie>,
	verwerkingsverantwoordelijken = [{verantwoordelijke1}, {verantwoordelijke2}, etc..]
	// Vertegenwoordiger?
	// Functionaris Gegevensbescherming?
}

{
	Verwerkingsverantwoordelijke : {
		Naam: 
		Contactgegevens :
	},
	verwerkingsactiviteit = [{activiteit1}, {activiteit2}, etc..]
}

verwerkingsactiviteitDoorVerwerkingsverantwoordelijke = {
	doeleinde : [optie1, optie2, etc..],
	categorieeën van betrokkene : [optie1, optie2, etc..],
	categorieeën van persoonsgegevens : [optie1, optie2, etc..],
	categorieeën van ontvangers : [optie1, optie2, etc..],
}

// Organisatie
			// Verwerkingsverantwoordelijken
						// Verwerkingsactiviteiten
```


## 2. Specificaties van de (gebruikers)interface

#### Welke informatie moet de website bevatten?
- Informatie over privacy register
- Voorbeelden


#### Hoe moet de gebruiker om kunnen gaan met de gegevens in het register?


## 3. User stories
- Als gebruiker wil ik:
	- Verwerkingsactiviteiten kunnen groeperen en sorteren
	- Een export kunnen maken van het register
	- Een versie van het register kunnen importeren 

## 4. To be discussed
- Wie host het register?
