# Laboration 2, Versionshantering och publicering
Detta är min webbplats som jag har skapat i första kursen på webbutvecklings programmet. Webbplatsen innehåller information om vem jag är.

## Tekniker som har använts:
* HTML

## Länkaar till det publicerade versionerna
* **Vercel:** https://dt224g-benjamin-bj-rkstr-m.vercel.app/
* **Netlify** https://moment12.netlify.app

## Frågor om git:

### Vad är skillnaden mellan git add och git commit?
Git add lägger till filer i staging area alltså dit filer är som ska sparas medan git commit sparar det permanent. 

### Varför använder man branches istället för att jobba direkt i main?
Branches används för att man inte ska riskera att förstöra något i den färdiga versionen. De underlättar också samarbetet i team om man är flera som jobbar i projektet med olika delar samtidigt.

### Vad händer rent praktiskt när man gör en merge?
När man gör en merge så slås en branch ihop med en annan (t.ex dev och main). Koderna jämförs sedan i brancherna som sedan kombinerar dom till en gemensam version. 

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
Github lagrar ens kod och är källan till den medan när man publicerar den på Netlify tillexempel så kan vem som helst besöka hemsidan via vilken webbläsare som helst. 

### Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
Genom att skapa en fil som heter.gitignore i projektet och sedan skriva i namnen på filerna man vill ta bort, så kommer git att ignorera dessa. 