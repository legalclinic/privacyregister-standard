# Technische specificaties

Dit document bevat een uitwerking van de technische specificaties die voortvloeien uit het referentiedocument. In dit document is het volgende opgenomen:

1. Specificaties van de structuur van het register
2. Specificaties van de (gebruikers)interface
3. User stories



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
