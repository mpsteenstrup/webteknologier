# Webteknologier

## Indholdsfortegnelse
* [Internettet](##Internettet)
* [Læringsmål for undervisningen](laeringsmaal.md)
* [Opbygning af website](OpbydningAfHjemmeside.MD)
* [CSS styling](/CSS)
* [Layout](#css-og-webside-layout)
* [Farver](farver.md)
* [Gestaltlovene](gestaltlovene.md)
* [Interaktionsdesign](interaktionsdesign.md)
* [Dokumentation af kode](dokumentatioAfKode.md)
* [Template til portfolie](portfolieTemplate)
* [Github til hosting af websider](#github-til-hosting-af-websider)


## Internettet

* [Webteknologier 1, hvad er internettet](https://docs.google.com/presentation/d/1TTR3N7ilYQZZ0FdJGCxPvAx-VwPzGvcPsZ7QnUfQMxY/edit?usp=sharing)
* [Historien om internettet](filer/Historien_om_internettet_politiken2014.pdf)



<!---  
* [Webteknologier 2, projekt og HTML introduktion](/filer/Webteknologier2.pdf)
* [Webteknologier 3, CSS](/filer/Webteknologier3.pdf)
* [Webteknologier 4, design](/filer/Webteknologier4.pdf)
--->

## Introduktion
Internettet er den altdominerende teknologi til deling af information. I dette forløb vil vi se på internettets opbygning og hvilke teknologier der ligger bag. Som projekt skal I lave en hjemmeside og offentliggøre den på Github.


## Projektbeskrivelse, Hjemmeside til præsentation af informatik-emne.
I informatik skal I redegøre for jeres projektarbejde i en portfolie. Portfolien skal være tilgængelig online og i dette projekt skal I lave strukturen til portfolien. Det er ok at linke til andre sider, evt. den I har arbejdet med de to første moduler.

Hjemmesiden skal indeholde
* En hoveside med en kort introduktion.
* Links til kommende undersider.
* Overskrift og afsnit.
* Billeder eller videoer.
* Konsistent styling.

Fokus er på at lære at programmere en hjemmeside og ikke i lige så høj grad indholdet.

### I portfolien skal I dokumentere
* Beskrive de designprincipper I har brugt.

# HTML programmering
Det er mange ressourcer når man skal lære at programmere hjemmesider. W3schools har tutorials til mange forskellige programmeringssprog. Det I skal bruge er, [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp).



# Github til hosting af websider

Github er et online sted hvor udviklere lægger programmer, data og meget mere. Det er et versionsstyringsværktøj lavet til at arbejde på forskellige versione af samme software. Vi kommer ikke til at bruge denne feature men kun bruge
det til at have vores websider liggenden.
Det anbefales generelt ikke at bruge specialtegn, æøå og mellemrum i filnavne.


I kan bruge Github til at hoste jeres webside. Startsiden hedder ```index.html``` og skal placeres i roden af jeres github repository. I kan linke til undersider ved relative referencer, eks ```<a href="side2.html"> Link til side 2 </a>```.

I skal lave et nyt ```repository``` og uploade alt materialet til den.

Når det hele er uploadet skal I ind i settings, hjulet, og ned til ```Github Pages```.


Addressen på websiden er ```brugernavn.github.io/repository/```. Reklamesiden for Informatik ligger for eksempel på ```mpsteenstrup.github.io/webteknologier/InformatikRysensteen/```.


Her er en side til at promovering af informatik.
[https://mpsteenstrup.github.io/webteknologier/InformatikRysensteen/index.html](https://mpsteenstrup.github.io/webteknologier/InformatikRysensteen/index.html)

Det kan godt kræve lidt tålmodighed at arbejde direkte i editoren på Github, da siden ikke altid opdatere så hurtigt. Man kan evt. prøve ```shift command R``` for hard reload af den side I vil se.


### Layout med topbar
Her er en template til et layout med en menu i toppen, [layoutTopbar.html](/introduktion/layoutTopbar.html)


## ```div``` og ```class```
```div``` står for **Content Division element** og er en ramme for indhold. Vi bruger den til at specificere forskelligt design og layout. ```class```giver elementer forskellige attributter, ud fra vores designvalg.

I eksemplet [class_capitals](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_capitals) fra w3schools.com, definere vi designet i ```<style>``` med ```.city { }``` og kalder designet med ```<div class="city">```.

## CSS og webside layout
W3schools har faktisk skrevet ret godt, så her er linket.
[https://www.w3schools.com/css/css_website_layout.asp](https://www.w3schools.com/css/css_website_layout.asp)

Filen [responsiveWebdesign](/introduktion/responsivWebdesign.html) er en kommenteret version som skalerer fint med forskellige skærmstørrelser. Den er ret fin.



<!--- * [index.html, et eksempel på basal html kodning som opfylder læringsmålene](https://mpsteenstrup.github.io/index.html)

* [Eksempler til introduktion til html, side1.htlm...](/introduktion)
--->
