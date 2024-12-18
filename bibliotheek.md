# Inventarissysteem voor een Bibliotheek

## Functionaliteiten

De bibliotheekbeheerder wil de volgende functionaliteiten in het inventarissysteem:

1. **Boekbeheer**
   - Boeken toevoegen en beheren
   - Voorraad bijhouden

2. **Genrebeheer**
   - Hoofdgenres en subgenres beheren

3. **Leveranciersbeheer**
   - Leveranciersinformatie beheren

4. **Rapportage**
   - Basisrapportage van boeken onder de minimumvoorraad

## Specifieke Eisen

### Boeken

Elk boek moet minimaal de volgende eigenschappen hebben:
- Titel
- Auteur
- ISBN
- Genre
- Aantal exemplaren
- Minimum voorraad
- Uitgever

Daarnaast:
- Hoort bij één hoofdgenre (bijv. 'Fictie')
- Kan in meerdere subgenres vallen (bijv. 'Science Fiction', 'Mysterie')
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

- 

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



