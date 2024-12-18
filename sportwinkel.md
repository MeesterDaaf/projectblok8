# Inventarissysteem voor een Sportwinkel

## Functionaliteiten

De eigenaar van de sportwinkel wil de volgende functionaliteiten in het inventarissysteem:

1. **Productbeheer**
   - Producten toevoegen en beheren
   - Voorraad bijhouden

2. **Categoriebeheer**
   - Hoofdcategorieën en subcategorieën beheren

3. **Leveranciersbeheer**
   - Leveranciersinformatie beheren

4. **Rapportage**
   - Basisrapportage van producten onder de minimumvoorraad

## Specifieke Eisen

### Producten

Elk product moet minimaal de volgende eigenschappen hebben:
- Naam
- Artikelnummer
- Verkoopprijs
- Inkoopprijs
- Huidige voorraad
- Minimum voorraad
- Maat/afmeting
- Kleur

Daarnaast:
- Hoort bij één hoofdcategorie (bijv. 'Schoenen')
- Kan in meerdere subcategorieën vallen (bijv. 'Hardlopen', 'Indoor')
- Wordt geleverd door één leverancier

### Leveranciers

Van leveranciers moet de volgende informatie worden bijgehouden:
- Naam
- Contactpersoon
- Email
- Telefoonnummer
- Levertijd in dagen

## Technische Eisen

- Frontend moet gebruik maken van Tailwind CSS of Bootstrap
- Backend moet gebruik maken van Laravel 11
- Backend moet gebruik maken van Laravel Breeze voor authenticatie
- Middleware moet zijn toegepast op alle routes die afgeschermt moeten zijn
- Alle CRUD functionaliteiten moeten zijn geïmplementeerd
- Alle relaties moeten zijn geïmplementeerd

## Opdracht voor de Student

1. **ERD (Entity-Relationship Diagram)**
   - Toon alle entiteiten
   - Toon attributen per entiteit
   - Toon relaties tussen entiteiten
   - Toon de cardinaliteit van de relaties

2. **Database Ontwerp**
   - Specificeer tabelnamen
   - Specificeer kolomnamen en datatypes
   - Definieer primary en foreign keys
   - Voeg eventuele constraints toe

3. **Beoordeling**
   - Het databaseontwerp (DBO) moet eerst worden beoordeeld door een docent voordat het wordt geïmplementeerd.

4. **Userstories**
   - Userstories moeten eerst worden geschreven en goedgekeurd door een docent voordat het wordt geïmplementeerd.
