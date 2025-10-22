# 💼 Power Apps – OnkostenDeclaratie-app Basis (Canvas App)

Deze basisapp helpt gebruikers om **zakelijke onkosten** te declareren, te beheren en op te volgen. 
De gegevens worden veilig opgeslagen in **Dataverse-tabellen**, wat zorgt voor schaalbaarheid en integratie met andere Microsoft-oplossingen.
Dit is een **basisversie** van een declaratie-app. Het **doel** is dat je deze **basisversie** verder kunt verfijnen en uitbreiden met andere functionaliteiten en schermen, naargelang je behoeften en wensen.

---

## 🚀 Overzicht

De app biedt functionaliteit voor:
 - Indienen van nieuwe uitgaven
 - Toevoegen van commentaar per uitgave
 - Koppelen van uitgaven aan een werknemer en een goedkeurder
 - Automatisch creëren van een uniek recordnummer bij registratie van een uitgave
 - Veilige opslag in **Microsoft Dataverse**

Ideaal voor interne teams die een gestructureerde en een eenvoudige **basisversie** low-code oplossing zoeken voor **onkostendeclaratie**.

---

## 🧭 Hoe werkt de app?

### 🖥️ Gebruikersinterface
De app is opgebouwd uit twee hoofdsecties:
- **Galerij**: laat toe nieuwe registraties uit te voeren en toont tevens een lijst van records (uniek recordnummer, status en indiener).
- **Formulier**: laat toe om geselecteerde records te bewerken of te verwijderen. Alle wijzigingen worden weggeschreven naar **Dataverse-tabellen**.

Deze indeling maakt het eenvoudig om gegevens te bekijken en te beheren.

---

### 📊 Tabellen
Je dient eerst de tabellen te creëren of op te laden in de **Dataverse**-omgeving. Creëer je nieuwe tabellen, vergeet dan niet de objecten en variabelen aan te passen.
Er zijn twee facultatieve tabellen toegevoegd die je kunt gebruiken voor verdere verfijning: **Status** en **Goedkeurder**. 
Via dropdowns kun je deze dan laten zien en de output koppelen aan het record voor het wegschrijven naar de hoofdtafel.

---
