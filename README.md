# Kalenderverktyg i Javascript.

## Installation

Projektet är förinställt med skript i `package.json` filen för att du enkelt ska kunna köra starta och testa projektet, det görs med `npm run <script-name>`.

Nedan har du en lista på de olika skripten som kan köras i terminalen:

- `npm install` - Installerar alla NodeJS moduler (körs en gång).
- `npm run update` - Uppdaterar testerna, behöver köras om läraren har ändrat dem.
- `npm run dev` - Startar utvecklingsservern och öppnar projektet i Chrome.
- `npm test` - Startar utvecklingsservern och Cypress så du kan jobba med kravlistan.
- `npm test -- --run` - Kör alla testerna en gång i terminalen.

Det räcker att bara köra `npm test` om du vill jobba med kravlistan eftersom skriptet också startar utvecklingsservern.

> Om du får felet `Cypress verification timed out` kan du förlänga tiden för verifieringen - [läs mer här](https://stackoverflow.com/questions/63667880/cypress-verification-timed-out-after-30000-milliseconds).

## Uppgiftsbeskrivning

I den här uppgiften skall ni bygga ett verktyg där användaren kan skapa och schemalägga todos. Verktyget skall visa en lista med todos och en kalender för översikt. Utöver det tekniska som skall skapas så ämnar den här uppgiften att träna på att arbeta med git och GitHub i projektform.

Para ihop er i grupp om 3 - ni väljer själva vem ni jobbar med. Läs noga igenom hela uppgiftsbeskrivningen tillsammans och börja sedan med att planera och dela upp arbetet.

## Projektet

När ni har läst hela uppgiftsbeskrivningen är det dags att strukturera ert arbete. Börja med att skapa ett repo på någons GitHub och bjud in de andra från gruppen. Lägg även upp alla ärenden (se lista nedan) som issues på GitHub och planera tillsammans vem som ska göra vad. För att få en bra och gemensam struktur kan det vara bra att göra skisser och/eller flödesdiagram över systemet så ni får en gemensam bild över vad som skall skapas. Allt förarbete ni gör med skisser eller annan diskussion bör läggas till i berörande ärende på GitHub. När det är dags att för er att börja bygga verktyget skall ni använda GitHub flow principen: 1 issue - 1 branch - 1 pull request.

Det är rekommenderat att ni gör det första ärendet tillsammans för att undvika merge konflikter. Innan ni påbörjar arbetet och tar egna ärende bör ni fundera på hur ni ska strukturera ert projekt och vilka filer som skall finnas. Exempelvis kan det vara bra att skapa en javascript fil för verktygets olika delar (todos.js, calendar.js och today.js). För att få till ett tydligare flöde i koden bör ni även skapa en huvudfil (main.js) där programmet börjar.


