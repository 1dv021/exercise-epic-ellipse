# Episk ellips

- A-nivå
- [Gitbook](https://coursepress.gitbooks.io/1dv021/content/ovningsuppgifter/del2/episk-ellips/)

> __VIKTIGT!__ Innan du börjar arbeta med övningsuppgiften är det viktigt att du följer guiden [Att komma igång med en övningsuppgift](https://coursepress.gitbooks.io/1dv021/content/guider/att-komma-igang-med-en-ovningsuppgift/) för att lägga till övningsuppgiftens repo till ditt repo för övningsuppgifter.

Hämta hem övningsuppgiftens repo och lägg tillen .gitignore-fil och komplettera enligt nedan.

## Uppgift

Du ska skriva en konstruktorfunktion som skapar ett objekt av typen `Ellipse` där arean och omkretsen ska kunna beräknas. I samband med att objektet skapas ska det vara möjligt att ange halva storaxelns längd, som betecknas a, och halva lillaxelns längd, som betecknas b.

![Ellips](ellips.gif)

En ellips area kan bestämmas med `Math.PI * a * b`, och dess omkrets approximativt med `Math.PI * Math.sqrt(2 * a * a + 2 * b * b)`.

## Typen Ellipse

Du ska komplettera filen `Ellipse.js` med kod som gör det möjligt att instansiera objekt av typen `Ellipse`.

### Egenskaper

- `a`, halva storaxelns längd.
- `b`, halva lillaxelns längd.

### Metoder

Metoderna nedan ska vara gemensamma för samtliga objekt som instansieras av typen.

- `area`, ska returnera ellipsens area.
- `circumference`, ska returnera ellipsens omkrets.
- `toString`, ska returnera en sträng representerande aktuellt objekt, med halva storaxelns längd satt till 42.7 och halva lillaxelns längd satt till 13.8, enligt `a: 42.7, b: 13.8, area: 1851.2, circumference: 199.4` där arean respektive omkretsen ska avrundas till en decimal.

## Tips

__Se föreläsningen som fokusera på designmönstret "Constructor/Prototype".__

Genom att köra testerna som kommer med övningsuppgiften kan du undersöka om koden du skrivit löst uppgiften (i alla fall enligt testet...).

## Lösningsförslag

- [https://github.com/1dv021/exercise-solution-proposals/tree/master/part-2/epic-ellipse](https://github.com/1dv021/exercise-solution-proposals/tree/master/part-2/epic-ellipse)
