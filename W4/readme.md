# Week 4

Maak een folder 'week4' waar al je oefeningen voor deze les in terecht komen.

## Deployment

Plaats je portfolio opdracht in de homedirectory (de map public_html). De handleiding voor VPN toegang en toegang tot je homedirectory kan je terugvinden op het studentenintranet Canvas>Intranet>Modules>ICT>Handleiding Homedirectory.<br>

Paden om te verbinden:
* Windows: \\dt-srv-file1.ehb.local\studentenhomes
* Mac: smb://dt-srv-file1.ehb.local/studentenhomes

Upload en Bekijk je portfolio via http://dtsl.ehb.be/~login.naam/.

## Screen

Vertrek met screen.html (en css) en maak screenshot screen.png na.<br>

### position

Je kan beginnen van onderstaande code. Alle nodige classes zijn reeds voorzien.
````
<figure>
  <img src="img/foldablescreen.jpg" alt="A chamber filled with flexible screens" width="100%">
  <div class="overlay"></div>
  <figcaption>Flexible Displays</figcaption>
</figure>
````
Je zal met CSS de text over de afbeelding plaatsen. Je zal hiervoor `position: absolute` & `position: relative` nodig hebben.<br>
Als je alle opdrachten hebt gemaakt mag je proberen om een overlay te maken met : `<div class="overlay"></div>`. <br>
De overlay moet over de volledige afbeelding komen en moet achter de text blijven.

### kolommen met float

Onder de afbeelding maak je 3 kolommen met een gelijke breedte die schalen met de breedte van het scherm.<br>
Geef de kolommen een maximum breedte van 1200px;


## Adventure time

Vertrek met adventure.html (en css) en maak screenshot adventure.png na.<br>
In adventure.txt vind je alle text terug die je nodig hebt.<br>

### Header
De header mag maximum 800px hoog zijn.<br>
Hierin komt een `img` & `h1`. Je geeft ze beide een position absolute.<br>
Een absolute element kan je centreren met de offset properties en margin auto:
````
  top: 0;
  bottom: 0;
  margin: auto;
````
De Afbeelding zal vanaf een bepaalde scherm breedte, te hoog worden (meer dan 800px). Ze zal dus buiten de `header` komen.
Je kan dit oplossing door een `overflow:hidden` aan de te geven `header`. Hierdoor wordt alles afgesneden dat buiten de `header` komt.<br>
De titel moet altijd onderaan de header blijven. Gebruik hiervoor de `bottom` property.

**Let op!** een absolute element positioneert zich tegen over het eerste parent element met een `position: relative`. Indien er geen parent is met een `position: relative`, wordt het body element als referentie gebruikt.

### main

Finn staat links en Jake staat rechts. We zullen hiervoor 2 technieken gebruiken:
* `text-align`
* `float`

### footer

Zet de links in een `ul`<br>
Zorg ervoor dat het functionele links zijn.

## Breaking Thrones

Werkt verder in king-frame.html &  king-frame.css<br>
Je gaat voor het eerst een custom font inladen. Bekijk king-frame.jpg.<br>
Gebruik het font "AvQest"

## Travel away

Vertrek met travel-away.html (en css) en maak screenshot travel-away.png na.<br>
Gebruik landscape.jpg als achtergrond.

### Google font

Je gebruikt 2 verschillende google fonts:
* Open Sans
* Pacifico
Bekijk de [instructie pagina](https://fonts.google.com/specimen/Pacifico?selection.family=Open+Sans|Pacifico) voor meer uitleg.

### Icon font

We maken ook gebruik van een iconfont dat gegenereerd is door [Iconmoon](https://icomoon.io/app/#/select).<br>
Het gebruik van een iconfont:
* Importeer het font met `@font-face`
* Wijs het font toe met de `font-family` property
* Maak een unieke class/id aan voor elk icoontje
* Gebruik de `:before` pseudo selector en geef de correcte unicode waarde mee aan de `content` property

voorbeeld:
````
.icon-shoppingcart:before {
  font-family: "iconfont";
  content: "\e350";
}
````

De unicode waardes:
* compass: `\e900`
* bed: `\e901`
* bus: `\e902`
* globe: `\e903`



## angrybird

Vertrek met angrybirds.html (en css) en maak screenshot angrybirds.gif na.<br>
Gebruik voor de titel het font `angry_birds_movie-webfont`.<br>
Maak 4 hyperlinks die als `background-image` angrybird.png hebben<br>
Je zal met `width`, `height` & `background-position` moeten werken om enkel 1 vogeltje te tonen per hyperlink.<br>
Werk met een `:hover` om de `background-position` aan te passen.

## extra: sprite-navigation

Als je met alle oefeningen klaar bent probeer je sprite-navigation.gif na te bouwen.<br>
Deze oefening is vrij gelijkend met de angrybird oefening.<br>
Gebruik [attribuut selectors](https://www.w3schools.com/css/css_attribute_selectors.asp) voor het instellen van de `background-position`.
