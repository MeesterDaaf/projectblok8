# Inventarissysteem voor een Dierenasiel

## Functionaliteiten

De eigenaar van het dierenasiel wil de volgende functionaliteiten in het inventarissysteem:

1. **Dierenregistratie**
   - Dieren toevoegen en beheren
   - Basisinformatie en medische geschiedenis bijhouden

2. **Adoptieproces**
   - Adoptieaanvragen beheren
   - Adoptiegeschiedenis bijhouden

3. **Medische Geschiedenis**
   - Medische behandelingen en vaccinaties registreren

4. **Voederschema's**
   - Voedingsschema's per dier beheren

5. **Verblijven Beheer**
   - Verblijven toewijzen en beheren

## Specifieke Eisen

### Dieren

Elk dier moet minimaal de volgende eigenschappen hebben:
- Naam
- Soort
- Ras
- Leeftijd
- Geslacht
- Medische geschiedenis
- Huidige verblijfplaats

Daarnaast:
- Kan geadopteerd worden
- Heeft een voedingsschema

### Adoptie

Van adoptieaanvragen moet de volgende informatie worden bijgehouden:
- Aanvrager naam
- Contactinformatie
- Datum van aanvraag
- Status van de aanvraag

## Technische Eisen

- Frontend moet gebruik maken van Tailwind CSS of Bootstrap
- Backend moet gebruik maken van Laravel 11
- Backend moet gebruik maken van Laravel Breeze voor authenticatie
- Middleware moet zijn toegepast op alle routes die afgeschermd moeten zijn
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
