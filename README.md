![Screenshot 2026-09-23 at 12.56.19.png](https://fantastic-newt-291.eu-west-1.convex.site/api/editor-files/kg20jnvg5qmp86qpw64xx6e6618ey42z/Screenshot%202026-09-23%20at%2012.56.19.png "Screenshot 2026-09-23 at 12.56.19.png")

# Gruppuppgift: bygg en webbplats för en kaffebar

:::github-repository {url="https://github.com/BiggerPixel/fai26-course-1/tree/workshop-07-group-exercise"} :::

## Syfte

Vi arbetar i grupper om två och bygger en liten webbplats för en kaffebar. Vi använder HTML för sidans innehåll och Tailwind för utseende och layout.

Vi tränar särskilt på två layoutsätt:

- **Flexbox** ordnar innehåll i en riktning, till exempel logotyp och länkar på samma rad.
- **CSS Grid** ordnar innehåll i rader och kolumner, till exempel flera kaffedrycker i ett rutnät.

Målet är att vi ska kunna välja rätt layoutsätt för olika delar av samma sida och förklara några av våra val.

## Start

1. Vi öppnar mappen `starter` i VS Code.
2. Vi startar `index.html` med Live Server.
3. Vi kontrollerar att rubriken **Kaffebar** visas i webbläsaren.
4. Vi bygger vidare i den befintliga filen. Tailwind är redan länkad på sidan så den ska redan fungera.

## Så arbetar vi tillsammans

Vi arbetar på samma lösning, så välj ut en av er som börjar skriva koden på sin dator och sedan turas vi om. Målet här är att verkligen få prova på och använda Tailwind fullt ut för att hantera all styling.

Tänk på att spara ofta, då blir det mycket lättare att snabbt upptäcka om något blir tokigt och vad det beror på.

## Uppgift

### 1. Bygg sidans meny

Vi skapar en meny högst upp på sidan.

Menyn ska innehålla:

- en logotyp eller kaffebarens namn till vänster;
- en lista med minst tre länkar till höger;
- en kantlinje under hela menyn.

Vi använder Flexbox för att placera logotypen och länklistan på samma rad. Tailwind-klasserna `flex`, `items-center` och `justify-between` kan vara en bra start.  
Precis som tidigare övningar är det inte viktigt vart länkarna pekar utan ni kan välja tex.  
`&lt;a href="/"&gt;Länk&lt;/a&gt;`

### 2. Presentera kaffebaren

I sidans huvudinnehåll skapar vi en sektion som berättar om kaffebaren. Sektionen ska innehålla en rubrik och en kort text.

Vi väljer ett namn och skriver två eller tre meningar som beskriver platsen. Texten kan till exempel berätta om kaffet, bakverken eller känslan i lokalen.  
**OBS!** _Det är helt okej att använda sig av lorem ipsum här, hitta på något eget eller be AI att skriva en kort text._

### 3. Bygg en kaffemeny med CSS Grid

Vi skapar en ny sektion med rubriken **Kaffemeny**. Under rubriken lägger vi minst 6st kaffedrycker. Varje dryck ska visas i ett eget kort med:

- dryckens namn;
- en kort beskrivning;
- ett pris.

Behållaren runt korten ska använda CSS Grid. Vi börjar med en kolumn och lägger sedan till fler kolumner på bredare skärmar. Exempel på användbara Tailwind-klasser är `grid`, `grid-cols-1`, `gap-6`, `md:grid-cols-2` och `lg:grid-cols-3`.

Prefixen `md:` och `lg:` betyder att klassen börjar gälla när webbläsaren når en viss bredd. Det gör layouten responsiv, alltså anpassad efter tillgängligt utrymme.

### 4. Bygg sidans sidfot

Längst ned skapar vi en sidfot (`footer`) med:

- samma logotyp eller namn som i menyn;
- copyrightinformation, till exempel `© 2026 Kaffebarens namn`.

## Kontrollera resultatet

Vi är klara med grunduppgiften när vi kan kontrollera allt detta:

- Menyn har logotyp till vänster och länkar till höger.
- Menyn har en synlig kantlinje längst ned.
- Huvudinnehållet presenterar kaffebaren.
- Kaffemenyn innehåller minst sex drycker med namn, beskrivning och pris.
- Kaffekorten ligger i en Grid-layout.
- Sidan visar en kolumn på smal skärm och fler kolumner på bredare skärm.
- Sidfoten innehåller logotyp och copyrightinformation.
- Alla delar går att läsa och sidan har tydliga färgkontraster.

Vi testar responsiviteten genom att göra webbläsarfönstret smalare och bredare. Vi pekar sedan ut för varandra vilka klasser som skapar Flexbox-layouten och vilka som skapar Grid-layouten.

## Om vi fastnar

Vi börjar med sidans HTML-struktur och lägger till några få Tailwind-klasser i taget. Efter varje förändring uppdaterar vi webbläsaren och kontrollerar vad tailwind-klassen gjorde.

Jag går runt och hjälper till med felsökning eller råd, hitta lämpliga klasser och kontrollera layouten. Ställ frågor om ni undrar något kring lösningen.

## Frivilliga utökningar

När grunduppgiften fungerar kan vi välja en eller flera utökningar:

- Lägg till en tydlig hover-effekt på meny-länkarna.
- Ge kaffekorten olika symboler eller bilder.
- Lägg till öppettider i presentationen.
- Gör menyn lättare att använda på en smal skärm.
- Lägg till ett framhävt kort för veckans kaffe.
