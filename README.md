# Opdrachtbeschrijving

## Inleiding

Je gaat de home-pagina van een bekend bedrijf ontwikkelen. De designers van dit bedrijf hebben alle schermontwerpen al
voor jou gemaakt, jij hoeft het alleen nog tot een werkende versie te vertalen!

Het resultaat kan behaalt worden met alleen CSS Flexbox, dus technieken als CSS Grid heb je niet nodig. Alle benodigde
afbeeldingen, iconen en andere SVG's zijn aangeleverd in de `assets`-map.

![screenshot](./assets/screenshots/screenshot-main.png)
_Let op:_ Dit voorbeeld bevat bonus-opdracht elementen

## Randvoorwaarden

* In plaats van te clonen, maak je voor dit project een **eigen** project aan, _from scratch_. Zorg dat je Git correct
  initialiseert en het project (met de basis-be standen die jij nodig hebt) minstens 1 keer naar jouw eigen repository
  hebt gepusht voor je begint.
* Je maakt de aangeleverde designs **zo gedetailleerd mogelijk na**, dus let ook op schaduwen onder elementen,
  afgevlakte hoeken en kleurgebruik. De lettergroottes en afstanden tussen elementen mag je op goed geluk inschatten.
  Spreek je innerlijke designer-oog aan! Er zijn designs aangeleverd voor zowel de desktop als mobiele versie. Jouw
  website is dus _responsive_.
* Bedenk van tevoren een plan voor je begint met programmeren. Welke titels worden een `h1`, welke een `h2`, etc.? En
  welke groottes en afstanden van verschillende elementen komen met elkaar overeen? Welke patronen zie je? Hoe ga je de
  CSS voor verschillende gedeeltes van de pagina uit elkaar houden?
* De gebruikte fonts zijn `Merriweather` voor titels en `Roboto` voor normale tekst. Deze fonts kun je gratis vinden op
  Google Fonts.
* Bekijk het [kleurenpalet hier](https://coolors.co/5722cd-4b49e8-f2f0ff-ed4385-0c0c0c). Het gaat om de volgende
  hex-codes:
    * Paars `#5722CD`;
    * Blauw `#4845E4`;
    * Roze `#ED4385`;
    * Zwart `#0C0C0C` (voor standaard tekst);
    * Lichtpaars `#F2F0FF` (voor de grote zwevende woorden, zoals "hello" en "services")
      _Uitzonderingen:_
    * Lichtgrijs `#F3F6F9` (voor de achtergrond van de projecten)
    * Grijs `#7A7A7A` (voor de service-tegel tekst);
* In de header en het contact-gedeelte is een _gradient_ gebruikt. _Tip:_ gebruik
  een [gradient-generator](https://cssgradient.io/) voor een mooi vloeiend verloop!
* De links in de navigatie linken naar hun bijbehorende _gebied_ op de homepagina. Dus als de gebruiker op "Contact Us"
  klikt, krijgt hij het contact-gedeelte (onderste deel) van de pagina te zien.
* De project-links linken naar een lege pagina waar alleen: _"The page you were looking for does not exist. Unless you
  were looking for an empty page, because then you've definitely found it."_ op staat.

## Screenshots eindresultaat basisopdracht

De screenshots zijn groot, dus je kunt ze het best downloaden en lokaal ingezoomed bekijken:

* [Desktop design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/basic/basic-desktop.png)
* [Mobiel design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/basic/basic-mobiel.png)

## Tips

* Om de achtergrond-kleur over de volledige breedte te laten lopen (maar de content niet) zul je gebruik moeten maken
  van het principe waarbij je een outer- en inner-container gebruikt.
* Je kunt de SVG's gebruiken als afbeeldingen in een `<img>`-tag, óf door ze als background-image in te stellen via CSS.

## Bonusopdrachten

1. Sla de kleur-codes op als CSS variabelen en gebruik deze in jouw CSS-bestand in plaats van de kleuren uit te
   schrijven.
2. Voeg de zwevende woorden toe achter de content. Dit doe je door een **pseudo-element** te gebruiken _(EdHub Hfst.
   9.2)_.
3. Zorg ervoor dat de lijnen tussen de verschillende secties schuin lopen ("sqewed") in plaats van horizontaal.
4. Ook de squiggle lijntjes wil je invoegen als een pseudo-element, waarbij de svg een `background-image` van het
   pseudo-element is. Op deze manier vervuil je de HTML niet met "nutteloze" elementen.
5. De gradients zijn voorzien van een doorzichtige textuur, om ze visueel wat meer interessant te maken. Ook deze kun je
   als pseudo-element via een background-image invoegen. Let hierbij wel goed op dat de textuur op de achtergrond,
   maar **onder** de content moet komen te staan. Hiervoor zul je gebruik moeten maken van de `z-index`.
6. Zorg ervoor dat er een transitie ontstaat wanneer de gebruiker over de project-links hovert:

![screenshot](./assets/screenshots/bonus/bonus-moving-link.gif)

## Screenshots eindresultaat inclusief bonusopdrachten

De screenshots zijn groot, dus je kunt ze het best downloaden en lokaal ingezoomed bekijken:

* [Desktop design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/bonus/bonus-desktop.png)
* [Mobiel design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/bonus/bonus-mobiel.png)

## Dummy tekst

#### Your website is an investment in the success of your business.

We are here to help you succeed. Let's work together

#### Hello

Rekupe is a digital agency in Los Angeles. We use strategic UX, SEO optimization and beautiful visual designs to help
your business grow. We see every project as a fresh opportunity, pushing ourselves to create new digital experiences.
Have a question? Click here to contact us!

#### Work

**Rolling Stone**
You know Rolling Stone. It’s the definitive voice in music, politics and culture. It’s a global
icon.

**Variety**
Variety is an industry leader for breaking entertainment news, reviews and box office results
with archive of content dating back to 1905.

**Worth**
A global media platform connecting a community that embraces worth beyond wealth.

#### Services

**Web Design**
Good web design is how companies stand out from their competitors. High quality web design leads
to increased user conversion and engagement. Through a proven web design process, we help clients launch websites and products that improve on their bottom line.

**Web Development**
Modern websites need to be responsive and fully functional at all sizes. We develop all of our
sites with a mobile first approach and ensure that our code quality is clean, organized and
performant. Already have a design but need it developed? We’re here to help!

**User Experience**
In order to build successful products you have to understand the user. We create user personas,
wireframes and prototypes to test with users. This allows us to gather feedback which helps to
shape the product and can quickly eliminate potential risks – saving you time and money.

**Logo Design + Branding**
Nike, Apple, Coca-Cola, Starbucks. What do all of these brands have in common? Easily
recognizable logos and brand identity. The best brands stand out from the crowd by having a clear and unique point of view. We will work with you to understand your vision and help create a unique brand identity and style guide for your company.

**SEO**
Do you want your site to rank higher in search results? Google is constantly changing their
algorithms for how they rank pages. Don’t worry about constantly playing catch-up. We will make
sure your website it optimized, providing you the best opportunities for organic search exposure.

**Copy Writing**
Brand messaging needs to be clear, direct and easy to understand to be effective. A unique tone
of voice will help you stand out from the crowd and build brand loyalty. We work with you to
establish your brand bible and ensure your messaging is focused and targeted.

#### Form
Let's work together
Have a question? Need a quote? Let us know!

#### Footer
Business website opdracht &copy; NOVI Hogeschool 2022