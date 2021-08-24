# SSIS.nu CSS-teman

Här finns ett antal CSS-stilar som kan användas med ett tillägg som exempelvis [Stylebot](https://stylebot.dev/) för att ändra utseendet på startsidan.

Ett galleri samt källkoden för att teman finns i mappen "css" ([här](https://git.ssis.nu/20alse/ssis.nu-css-teman/-/tree/master/CSS))

# Installera teman

För att kunna ändra utseendet på ett enkelt sätt och enkelt kunna stänga av ändringarna så rekommenderar jag webbläsartillägget [Stylebot](https://stylebot.dev/) eller [Stylish](https://userstyles.org). De ser dessutom automatiskt till att temats ändringar prioriteras. (`!important` läggs automatiskt till överallt i CSS-koden).

**Nedan följer en guide för tillägget Stylebot (som jag tycker är bättre än Stylish) och hur du lägger till mina teman.**


### Steg 1. Installera Stylebot

Gå in på hemsidan för [Stylebot](https://stylebot.dev/) och klicka dig rätt till den webbläsare som du använder.


### Steg 2: Kopiera innehållet i valfri fil

Hitta ett tema du gillar, och hitta sedan dess fil i mappen "CSS" (klicka [här](https://git.ssis.nu/20alse/ssis.nu-css-teman/-/tree/master/CSS) för att komma direkt dit). Kopiera innehållet i filen till ditt urklipp.

### Steg 3: Skapa en ny stil för https://ssis.nu

Nu är det dags att klistra in stilkoden i Stylebot. Först måste vi skapa en ny stil för SSIS.nu. Detta gör du genom att navigera [hit](chrome-extension://oiaejidbmkiecgbjeifoejpgmdaleoha/options/index.html) och klicka på **Styles>Add a new style**. Funkar inte länken? Du ska till inställningssidan för pluginet. Testa att högerklicka på vilken sida som helst och välja "Stylebot>Options...".

Nu kan du kopiera in koden som du kopierade till urklipp nyss i den stora vackra textrutan som tar upp större delen av sidan.

I URL skriver du bara `https://ssis.nu`. Sedan klickar du på **Save** och voilá!

*Notera: Du behöver troligtvis ladda om sidan för att de visuella ändringarna som temat gör ska visas.*

Du repeterar bara denna process om du vill lägga till fler teman. På samma sida där du lägger till teman kan du även aktivera och avaktivera befintliga teman.

