> _Fork_ deze leertaak en ga aan de slag. 
Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. 
De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# mijn OBA: Uitleningen & Verlengen
<!-- Geef je project een titel en schrijf in één zin wat het is -->
Voor de opdrachgever OBA heb ik een website gebouwd voor de uitleningen binnen het mijn OBA platform. Ik heb hierbij gewerkt vanuit de feedback van een versie van de vorige sprint. 

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

Userstory: "Toon in een overzicht alle abonnementen van een familie met een verwijzing naar een individueel profiel van elk familielid, met de functie:  in te leveren boeken om boete te voorkomen."

Mijn website bestaat uit een header, menu-bar en de main-content: de in te leveren boeken. In de header vindt je een search-bar (algemene zoekfunctie) en verder vindt je informatie over de ingelogde gebruiker. In de navigatiebar vindt je linkjes naar andere pagina's binnen het mijn-OBA platform. Ook vindt je onderaan een darkmodus en een betere contrast mdous. Op de uitleningen pagina zelf, vindt je alle producten die geleend zijn en binnenkort ingeleverd moeten worden. Elke product heeft een verlengen button, indien de gebruiker het product nog wil verlengen. De gebruiker kan ook via 2 manieren door de lijst van producten heen, namelijk mbv de buttons of dmv van scrollen.

<img width="700" alt="Scherm­afbeelding 2023-11-30 om 20 30 44" src="https://github.com/wingsvn/look-and-feel-corporate-identity/assets/144009709/c8de7f25-d737-48af-be28-35ad591f4383">

<img width="300" alt="Scherm­afbeelding 2023-11-30 om 20 31 43" src="https://github.com/wingsvn/look-and-feel-corporate-identity/assets/144009709/666b2c93-4e8e-4cb1-80f9-e57c79cf0fd7">

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

De website in HTML bestaat uit 3 delen, de header, de navigatie en de main. De navigatiebar heb ik in HTML opgezet met list items binnen een unordered list.
De gegevens van de boeken, DVD's en CD's bevinden zich elk in een article element. Alle articles van de  zit weer in een div element. Om per categorie de producten naast elkaar te zetten heb ik CSS flex gebruikt. Verder heb ik voor de uitbeeld vallende producten CSS overflow: scroll gebruikt om deze producten zichtbaar te krijgen. 'disabled' is op sommige buttons toegepast indien boeken niet verlengd kunnen worden.

Werken aan deze website? Installeer door deze repository te forken en te clonen.

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
