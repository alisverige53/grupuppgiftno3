# Teamets webbsida

En enkel webbsida som vi bygger tillsammans i gruppen. Sidan presenterar vårt team,
våra gruppmedlemmar och vad vi vill lära oss under kursen.

Projektet är byggt med ren HTML och CSS – inga ramverk och inga externa bibliotek.

## Innehåll

| Fil | Beskrivning |
| --- | --- |
| `index.html` | Sidans struktur och allt innehåll |
| `style.css` | All formatering: färger, typsnitt och layout |
| `.gitignore` | Filer som Git ska ignorera |
| `README.md` | Den här filen |

## Kom igång

### 1. Hämta projektet

```bash
git clone https://github.com/alisverige53/grupuppgiftno3.git
cd grupuppgiftno3
```

### 2. Öppna sidan

Dubbelklicka på `index.html` så öppnas sidan i din webbläsare.

Tips: I VS Code kan du installera tillägget **Live Server**. Högerklicka sedan på
`index.html` och välj *Open with Live Server* – då uppdateras sidan automatiskt
varje gång du sparar.

## Så här arbetar vi tillsammans

För att vi inte ska skriva över varandras kod arbetar alla i en **egen gren**
(branch) och skickar in ändringarna via en *Pull Request*.

### Steg för steg

**1. Hämta det senaste innan du börjar**

```bash
git checkout main
git pull
```

**2. Skapa din egen gren**

```bash
git checkout -b fornamn-min-del
```

Exempel: `git checkout -b ali-presentation`

**3. Skriv din kod, spara och committa**

```bash
git add .
git commit -m "Lade till min presentation"
```

**4. Skicka upp din gren**

```bash
git push -u origin fornamn-min-del
```

**5. Öppna en Pull Request**

Gå till projektet på GitHub. Där dyker en gul ruta upp med knappen
*Compare & pull request*. Klicka på den, skriv kort vad du har gjort
och tryck på *Create pull request*.

En annan i gruppen tittar igenom koden och klickar på *Merge*.

### Regler vi kommer överens om

- Arbeta aldrig direkt i `main` – skapa alltid en egen gren.
- Kör `git pull` innan du börjar för dagen, så slipper du krockar.
- Skriv commit-meddelanden på svenska och beskriv vad du gjorde,
  till exempel `Lade till bild i sidfoten` – inte `ändringar`.
- Fråga i gruppchatten om något krånglar. Det är helt normalt att det
  strular med Git i början.

## Att arbeta samtidigt (live coding)

Om ni vill sitta och koda i samma fil samtidigt kan ni använda tillägget
**Live Share** i VS Code:

1. En person installerar Live Share och startar en session.
2. Den personen får en länk och delar den i gruppchatten.
3. De andra öppnar länken och kan skriva i samma filer direkt.

Kom ihåg att den som är värd måste committa och pusha koden efteråt –
annars försvinner arbetet när sessionen avslutas.

## Kvar att göra

- [ ] Skriva rubriken i `<h1>` i sidhuvudet
- [ ] Skriva en presentation av teamet
- [ ] Fylla i namn och presentation för varje gruppmedlem
- [ ] Skriva texten i sidfoten
- [ ] Göra sidan responsiv med media queries
- [ ] Kontrollera att sidan fungerar på mobil

## Vad vi lär oss i projektet

- Att skriva en tydlig HTML-struktur med semantiska element
- Att använda CSS-variabler för färger
- Att placera innehåll med Flexbox
- Att skapa en webbsida som fungerar på olika skärmstorlekar
- Att samarbeta i ett gemensamt kodprojekt med Git och GitHub

## Länkar

- [MDN Web Docs på svenska](https://developer.mozilla.org/sv-SE/) – uppslagsverk för HTML och CSS
- [Flexbox-guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) – bra genomgång av Flexbox
- [Git-handbok](https://docs.github.com/sv) – GitHubs egen dokumentation på svenska

## Gruppmedlemmar

| Namn | GitHub |
| --- | --- |
| Ali Asgari | [@alisverige53](https://github.com/alisverige53) |
| | |
| | |
| | |
