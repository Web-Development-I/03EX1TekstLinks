# Starter oefeningen Les 3<br>Hoofdstuk 03 & 04 - Tekst markeren & Koppelingen maken
## Oefening 1
Maak in de map oefStarters een nieuw bestand oefening01.html. Zorg dat de pagina er als volgt uit ziet. In de body maak je hiervoor gebruik van de volgende elementen: **h1, h2, h3 en p**. Let op de details, dit is een Nederlandstalige pagina (stel de taal in bij het **html** element) en de titel is _oefening01_ (stel dit in via het **title** element).

![oefening01.PNG](docs/images/oefening01.PNG 'oefening01')
<br><br>

## Oefening 2
Maak in de map oefStarters een nieuw bestand oefening02.html. Volg onderstaande stappen om tot het getoonde resultaat te komen
- maak gebruik van **Emmet** om het skelet van de pagina te creëren
- pas in het **head**-element de titel en taal aan
- pas de **body** aan
  - zorg dat de titel en ondertitel (zie: België & Een onvolledig overzicht) in een **header** element zitten en maak daarbinnen gebruik van een **h1** en **p** element. 
  - de provincies zet je telkens in een **section** element waarbinnen je gebruik maakt van **h2** en **p** elementen.
  - geef via **tekstmarkering** aan dat de hoofdstad van elke provincie **belangrijk** is.

  ![oefening02.PNG](docs/images/oefening02.PNG 'oefening02')
<br><br>

## Oefening 3
Open het bestand oefening03.html. Volg onderstaande stappen om tot het getoonde resultaat te komen
- zet het eerste h1 en p element in een **header**.
- vorm per kleur een **sectie**, de sectie bevat
  - een **h2**-element voor de naam van de kleur,
  - de bijhorende **lijst**

  ![oefening03.PNG](docs/images/oefening03.PNG 'oefening03')
<br><br>

## Oefening 4
Open het bestand oefening04.html en zorg dat je onderstaand resultaat bekomt.
- maak gebruik van een description list
- geef aan dat de termen HTML en CSS afkortingen zijn

  ![oefening04.PNG](docs/images/oefening04.PNG 'oefening04')
<br><br>

## Oefening 5
Open het bestand oefening05.html en volg de instructies. Zorg dat je onderstaand resultaat bekomt.
- vul de afkortingen voor de verschillende gassen aan
- gebruik **tekenreferenties** voor de **speciale tekens** Euro, Yen, Pound en Dollar
- zet elk gas in een **article**
- de drie articles vormen het main-gedeelte van de pagina, geef dit aan via een **main** element

  ![oefening05.PNG](docs/images/oefening05.PNG 'oefening05')
<br><br>

## Oefening 6
Open en vervolledig de pagina oefening06.html 
- voeg in de footer een **nav**-element toe
- voeg binnen het nav-element een hyperlink toe, maak hiervoor gebruik van de **\<a>-tag**
- geef dit element 
  - een **attribuut** genaamd **href** en stel de waarde in op **https://developer.mozilla.org/en-US/docs/Web/HTML<i></i>**
- het **aanklikbare gedeelte** voor dit element stel je in op **MDN Web Docs**
  - markeer MDN als afkorting, maak gebruik van het **abbr**-element en stel het **title**-attribuut in op "Mozilla Developer Network"

Open de pagina met LiveServer en kijk of de hyperlink werkt. 

- voeg een attribuut **target** toe aan de link en zorg ervoor dat de pagina opent in een nieuw tabblad
- voeg in de **nav**-sectie nog een hyperlink toe die in een nieuw tabblad de pagina **https://html.spec.whatwg.org/multipage/<i></i>** opent wanneer de gebruiker klikt op "HTML Living Standard"
- geef aan dat HTML een afkorting is en stel de titel voor de afkorting correct in
<br><br>

## Oefening 7
Open de pagina oefening07.html. Op de pagina vind je in de main enkele article elementen.
- voeg aan elk **article**-element een **attribuut id** toe en geef het id een waarde
  - tip: gebruik bv. een korte schrijfwijze van de opleiding
  - tip: maak gebruik van de mogelijkheid die VS Code biedt om blokken toe te klappen, zo kan je het overzicht goed bewaren
- voeg net voor de sluittag van het **header**-element een **nav**-element toe
- maak nu adhv **a**-elementen bladwijzers zodat je via een klik op de bladwijzer direct op de betreffende opleiding komt
- test of de bladwijzers werken
  - tip: maak je venster klein zodat je effectief het effect van de bladwijzers ziet
- voeg onder het main-element een alinea toe met de tekst "terug naar boven"
- pas de pagina aan zodat wanneer de gebruiker klikt op "terug naar boven" deze automatisch terug helemaal bovenaan de pagina komt
  - tip: voeg aan een gepast element het id attribuut toe en maak via een a-element een bladwijzer
  - test of de bladwijzer werkt
- extra
    - zorg dat de gebruiker eenvoudig kan bellen door op het telefoonnummer, dat in de footer staat, te klikken; maak hiervoor een hyperlink waarbij je in het href attribuut gebruik maakt van **tel:**
    - voeg onder het telefoonnummer nog een e-mail adres (info@hogent.be) toe; zorg dat bij een klik op het e-mail adres het e-mail programma van de gebruiker geopend wordt en een mail klaarstaat geaddresseerd aan info@hogent.be
<br><br>

## Oefening 8
Open pagina oefening08.html. 
- zorg dat bij een klik op "Agro- en biotechnologie" (het volledige article moet aanklikbaar zijn) de pagina agroEnBio.html wordt geopend; deze pagina bevindt zich reeds in de map opleidingen
- zorg dat in de pagina agroEnBio.html 'Terug naar overzicht' een hyperlink wordt, bij een klik op de link komt de gebruiker terug terecht op oefening08.html
- maak het HoGent-logo aanklikbaar; bij het aanklikken wordt de website van hogent.be geopend in een nieuw venster
- pas de pagina's aan zodat als je op de hyperlink 'Terug naar overzicht' klikt je in de pagina oefening08.html automatisch terug op de opleiding 'Agro- en Biotechnologie' komt; maak gebruik van een bladwijzer

Je merkt dat de titel en de tekst van het article van uiterlijk veranderen nu ze als hyperlink fungeren. De opmaak van een pagina zullen we later verzorgen adhv **css**. In de map css zit een bestand genaamd site.css. _(je hoeft nu nog niet te snappen wat in dit bestand staat)_
- voeg in de **head** van de pagina een **link** element toe dat refereert naar de **stylesheet site.css**
- indien je de pagina nu bekijkt heeft het article niet meer de typische opmaak van een hyperlink
