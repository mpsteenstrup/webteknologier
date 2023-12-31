## Opbygning af hjemmeside

Her vil vi gennemgå det basale i forhold til at programmere en hjemmeside. De hjemmesider I skal lave bliver lavet i en tekst editor, vi bruger [Visual Studio Code](https://github.com/mpsteenstrup/InformatikRysensteen/blob/main/dokumenter/TekstEditorOgGithubTilmelding.md), og gemmes med endelsen ```.html```. Startsiden kaldes ofte index så filnavnet skal være ```index.html```.

Der er rigtigt mange ressourcer på nettet når man skal lave hjemmesider. Vi bruger guiden fra w3schools, [https://www.w3schools.com/html](https://www.w3schools.com/html/default.asp).

Her er den simpleste hjemmeside
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
</head>
<body>
Hello world.
</body>
</html>
 ```
Elementerne er
* ```<>``` åbnings-tag og ```</>``` lukke-tag.
* Header mellem ```<head>..</head>```. Her defineres opsætningen af siden, men det som står bliver ikke vist på siden.
* Body ```<body>...</body>``` eller kroppen. Her skal alt tekst, billeder osv. som skal vises på siden være.
* Det hele omsluttes i ```<html>...</html>```.
* Øverst angives dokumenttypern, ```<!DOCTYPE html>```.

## Øvelse
* lav en mappe kaldet ```hjemmeside``` og åben mappen i VS code.
* Lav et nyt dokument og kopier koden ind i VS code.
* Gem filen som ```index.html```.
* Tryk på ```Go Live``` nederst til højre og hjememsiden er levende!.
* Skriv noget andet i stedet for Hello World og gem det.
* I behøver ikke at lukke browserwinduet, men kan bare opdatere det.
* Slet linjen ```<meta charset="UTF-8">``` og undersøg hvad der sker.

## Overskrifter, paragraffer osv.
For at lave noget struktur på hjemmesiden bruges tags for overskrift, paragraf osv. Her er en liste med tags.
* ```<h1>,<h2>,<h3>,<p>,<ol>,<ul>,<br>```
## Øvelse.
* Undersøg hvad de forskellige tags gør, brug evt. nettet til at slå det op.

## Links og billeder.
Vi vil  gerne have billeder og links til andre sider. Links laves med ```<a href="url link"> navnet på linket </a>```. Billeder gemmes i undermappen ```billeder```og indsættes med ```<img src="billeder/filnavn" alt="navn på billed">```.

## Øvelse
* opret en undermappe kaldet ```billeder``` og find et billede på nettet og placer det i mappen.
* Indsæt et link til en ekstern side, I vælger selv hvilken.
* Indsæt et billed fra fra nettet ved at bruge url-addressen.

### Relative links og lokale filer, HVOR ER MIN FIL???
Computere har en mappestruktur og filer ligger i mapper - det kommer måske som en chok. Det er en vigtig del af at være et dannet menneske at vide hvor sine ting er og det gælder også på computeren. På min computer ligger denne fil i mappen ```webteknologier``` under ```undervisning```. Den fulde sti til mappen er ```/Users/madspetersteenstrup/Documents/programming/Undervisning/webteknologier```. Som I kan se er hver undermappe angivet ved ```/```, på mac ```option,shift,7```.

## Øvelse
* Lav den mappe kaledet ```hjememside``` som I ikke gad ovenfor og placer et billede i undermappen ```billeder```.

Dette hedder et relativt link da det peget på billedet i mappen ```billeder``` som ligger i den mappe hvor ```index.html``` filen ligger. Det kan godt betale sig at holde noget struktur med billeder i en mappe og html filer i overmappen.