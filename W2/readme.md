# Week 2


## Colorpicker Chrome

Enkele handige plugins die je kan installeren als developer:<br>
* [ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp)
* [Web Developer Plugin](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm)

Een Colorpicker is een must voor developers.


## Oefening 1: Structuurelementen

Bekijk de screenshot 'webpage.png' .

Teken op papier de basisstructuur van deze site uit en geef aan welke html structuur elementen je waar zou gebruiken. (header, footer, section, article, …)

 

## Oefening 2: Hyperlinks

Maak binnen de map SWD die vorige week werd aangemaakt een nieuwe map: "week2" (geen spaties)  aan.

Je moet 3 pagina's maken. index.html, work.html en contact.html.
In feite werk je in deze oefening een zeer eenvoudige website uit.
Maak hyperlink.css aan en link deze met alle html files

Vertrek van het bestand hyperlinks.txt. Je vindt daarin de teksten voor  de 3 pagina's.
Begin met de Homepage, maak daarna de contact pagina en als laatse begin je aan anker navigatie pagina.

Maak van de navigatie een ongeordende lijst. Zorg dat je hiermee de 3 pagina's naar elkaar laat linken.

#### home.html
* gebruik de juiste lijsten
* `<small>` maakt je text kleiner

#### contact.html
* Functionele hyperlinks

#### work.html
 * Anker navigatie

  
## Oefening 3: Hyperlinks-advanced
> Je werkt hierbij verder op oefening 2. <br>

Breng meer kleur aan de website. Kies zelf een kleurschema via [Adobe color](https://color.adobe.com/nl/create) of [coolers](https://coolors.co/app)

Voeg extra css toe zodat de link die naar de huidige pagina verwijst (bv. de home-link op de homepage) een andere kleur krijgt.
Tip: gebruik een class bij de betreffende link in elke pagina. Geeft de class bijvoorbeeld de waarde 'current'. Je kan dan css schrijven voor deze class.

#### home.html
* Extra kleuren
* Current link

#### contact.html
* Extra kleuren
* Current link

#### work.html
* Extra kleuren
* Current link
* <b>4 verschillende css selectors</b>


## De images folder

Maak een nieuwe map: les3 (geen spaties!)  aan.  Maak een nieuwe map ‘img’ aan. Alle afbeeldingen die je zal gebruiken plaats je in deze folder.

## Chrome Developer tools - property inspector

Analyseer de website van [Multec van EHB ](https://www.erasmushogeschool.be/nl/opleidingen/multimedia-communicatietechnologie) met de property inspector.<br>
Open de property inspector door op de **rechtermuisknop** te drukken en kies dan **"inspect"**.<br>
**windows** shortcut: f12 of Ctrl + shift + C<br>
**mac** shortcut: Cmd + shift + C<br>
Probeer volgende zaken met de inspector tool: <br>
* Navigeer direct naar een gewenst element (2 methodes)
* Terugvinden van de volledige selector van een element
* Probeer css regels uit/aan te schakelen en kijk wat er gebeurt.
* Voeg CSS toe aan een element
* pas een `margin` aan door de pijltjes toetsen te gebruiken

**Gebruik deze tool altijd als de code die geschreven hebt, niet het gewenste resultaat geeft.**


## Birds: Afbeeldingen in HTML
>Maak de HTML voor Birds.png

Maak een nieuw HTML-bestand birds.html aan. De tekst vind je in birds.txt. Voeg de afbeeldingen toe. Het figure-element komt hier van pas. Vergeet niet om passende waardes te geven aan het alt-attribuut.

## Birds: Achtergronden in CSS
>Voeg CSS toe aan voorgaande oefening.

Geeft de body een `text-align: center` en voeg pattern.jpg toe als `background-image` <br>
Pas de kleuren aan en voeg semi-transparante achtergronden toe.<br>
Probeer ook eens met bg.jpg (ook in de images folder). Hier komt background-size van pas.<br>
Een figcaption is een block element. Dit kan je centreren door het een `width: 400px` te geven en een `margin: auto`

## Gradients

Bekijk de schermafbeelding "gradients.png". Maak minimum 2 van deze gradients na.<br>
In de html heb je telkens een div met een class. Elke div is 300 pixels hoog.<br>
Dit doe jet met volgende css:<br>

`div { height : 300px; }`

Bij 2de gradient combineer je een achtergrond afbeelding met een gradient. De url van de achtergrond afbeelding geef is:
`https://picsum.photos/1200/700`
 

## Multiple backgrounds & Gradients

Maak verder alle gradient oefening af.
Probeer zeker de "Outer space" oefening na te maken door het combineren van verschillende background-images.
