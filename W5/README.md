# Week 5

Maak een folder 'week5' waar al je oefeningen voor deze les in terecht komen.

## Portfolio

Vertrek met travel-away.html (en css)<br>
zoals je ziet zijn er 3 screenshot van het eindresultaat dat je moet namaken.<br>
Begin met gallery.png<br>

### Header

Begin met de header
Gebruik logo dat je zelf hebt gemaakt of het logo van de website squarespace.<br>
In het midden zet je jouw naam & een motivatie<br>
Rechtsbovenaan komt een navigatie. Je kiest zelf de namen van de links maar je zet er minstens 3 <br>
Voor CSS de navigatie ga nodig hebben: een specifieke border & child selector.<br>
Geef de header een achtergrond afbeelding met als url `https://source.unsplash.com/1600x900/?tech` in combinatie met een gradient.

### sidenav

De side navigatie bestaan uit 3 links: Gallery, Events, News.
Het is anchor navigatie waar bij het aanklikken, de toebehoorde content zichtbaar wordt. Hiervoor ga is in CSS de `:target` pseudo selector nodig hebben.<br>
De content ernaast dat je niet wil tonen geet je een `display:none`<br>
De lijst elementen krijgen een driehoekje ipv een bolltje. `list-style: none` zorgt ervoor dat de bolletjes verdwijnen. Met CSS geef je de lijst elementen het pseudo element `:before`. De `content` hiervan krijgt de unicode : `"\25B6"`.

### Gallery / Events / News 
Er is altijd maar 1 van de 3 zichtbaar. Afhankelijk van welke link je hebt aangeklikt in de side navigatie.

#### Gallery

Zet 3 afbeeldingen naast elkaar. als source kan gebruik maken van `https://source.unsplash.com/800x800/?uidesign`. De laatste parameter van de url kan je zelf kiezen. In het voorbeeld is uidesgn, technology & vr gebruikt als thema.<br>
Laat ook de cursor veranderen als je over een afbeelding beweegt.

#### Events

Voor een event gebruik je een `<article>`. Dit is omdat alle informatie hierin "self contained content" is. Dit wil zeggen dat los van de website het article op zichzelf iets betekent. <br>
Geef het `<article>` een `<header>` en een `<footer>`. In de `<header>` komt de titel en de tijd en in de `<footer>` komt de plaats en de prijs.

Volgende elementen zijn eventueel een optie:
* `<time datetime="2018-07-07">July 7</time>`: hiermee kan je datum meegeven in machine-readable format. Goed voor SEO.
* `<address>`: bevat contact informatie over de auteur/eigenaar van het article. (dus niet enkel een post adres)

###### CSS Moeilijkheid:

De afbeelding mag niet van grootte veranderen. Maar het volledige article en de text hiernaast moet wel schalen met de breedte van het scherm.<br>
Je afbeelding zal dus een `position: absolute` nodig hebben. Het article geef je een `padding-left` die even breed is als de afbeelding.

#### News

In deze sectie ga je aan het werk met verschillende manieren om een font te stijlen.<br>
Je zal hiervoor volgende properties nodig hebben:
* `line-height`
* `text-indent`
* `word-spacing`
* `font-style`
* `font-weight`

Pas de stijl en maak gebruik van volgende pseudo-selectors:
* `first-line`
* `first-letter`


## Responsive

Vertrek met responsive.html (en css)<br>
zoals je ziet zijn er 3 screenshot van het eindresultaat dat je moet namaken.<br>
Dit zijn de 3 verschillende resultaten van : mobile - tablet - desktop<br>
Vergeet niet je [viewport meta](https://www.w3schools.com/css/css_rwd_viewport.asp) toe te voegen of de [media-queries](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) zullen niet werken.
````
<meta name="viewport" content="width=device-width, initial-scale=1.0">
````
Werk mobile eerst uit en voeg dan media-queries toe voor tablet en desktop.<br>
De gebruikte mediaqueries zetten een breekpunt op 768px en 1025 pixels.

### Portfolio 2.0

We hebben van de portfolio opdracht de desktop versie eerst uitgewerkt. We gaan de website nu ook mobiel toegankelijk maken. Hiervoor zal dus knip en plak werk moeten uitvoeren aangezien de zaken die we niet op mobile nodig hebben verplaatsen we naar een media-querie.

We maken de portfolio website dus voor 2 formaten. Mobiel & desktop. <br>
Bekijk de 3 porfolio afbeelding en bouw deze na.

Op desktop gaan we een transitions & transforms toevoegen aan de side navigatie. Bekijk hiervoor portfolio-side-nav.gif.<br>
Je zal zien dat er 1 item is bijgekomen. Dit item is niet gelink met content die tevoorschijn moet komen.<br>
De bedoeling is dat als je op deze link klikt, de hover-kleur aanwezig  blijft. gebruik hiervoor de `:focus` pesudo selector.


## vragen

Moeten hyperlinks in een zijbalk altijd in een nav element staan of niet?

