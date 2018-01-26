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
- De naam van de verwerkingsactiviteit
	- Voorvraag: Wanneer is sprake van een nieuwe verwerkingsactivteit?
- Het doeleinde van de verwerkingsactiviteit
	- 
- De categorieën betrokkenen
- De categorieën persoonsgegevens
	- Algemeen <--> Bijzonder
- De grondslag van de verwerking
	- 

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


#### Hoe moet de gebruiker om kunnen gaan met de gegevens in het register?


## 3. User stories
- Als gebruiker wil ik:
	- Verwerkingsactiviteiten kunnen groeperen en sorteren
	- Een export kunnen maken van het register
	- Een versie van het register kunnen importeren 

## 4. To be discussed
- Wie host het register?
