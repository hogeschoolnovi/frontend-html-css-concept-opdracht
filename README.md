# Opdrachtbeschrijving

**Inhoudsopgave**

1. [Inleiding](#inleiding)
2. [Opdracht 1: opzet](#opdracht-1-opzet)
3. [Opdracht 2: header en introductie](#opdracht-2-header-en-introductie)
4. [Opdracht 3: projecten](#opdracht-3-projecten)
5. [Opdracht 4: services](#opdracht-4-services)
7. [Opdracht 5: contactformulier en footer](#opdracht-5-contactformulier-en-footer)
8. [Bonusopdracht](#bonusopdracht)
9. [Schermontwerpen](#schermontwerpen)
    1. [Basisontwerp](#basisontwerp)
    2. [Bonusontwerp](#bonusontwerp)
10. [Bijlage](#bijlage)
     1. [CSS structuur](#voorbeeld-css-structuur)
     2. [Dummy tekst](#dummy-tekst)

## Inleiding

Het is tijd om jouw CSS-skills in de praktijk te brengen: je gaat de home-pagina van een bekend bedrijf ontwikkelen. De
designers van dit bedrijf hebben, naar aanleiding van hun huisstijl, alle schermontwerpen al helemaal uitgedacht. Het
enige wat jij als aanstormende web developer hoeft te doen, is daar een werkende versie van te maken! Je kunt de
desktop- en mobiele designs [hier](#schermontwerpen) bekijken.

Om je rustig kennis te laten maken met alle verschillende technieken, raden we je aan om bij het basis-ontwerp te
beginnen. Voor het basisontwerp heb je kennis nodig van CSS Flexbox, positionering doormiddel van de `position` property
en semantische HTML-elementen.

Heb je tijd over? Dan kun je ervoor kiezen alle "toeters en bellen" van het bonusontwerp toe te voegen.
Hiervoor heb je onder andere kennis nodig van pseudo-elementen, transities, het gebruik van vormen in CSS en gebruik
van `z-index` om elementen boven elkaar te stapelen. Al deze technieken worden besproken in het bonushoofdstuk op
EdHub (Hfst. 9).

![browser-screenshot](./assets/screenshots/browser-screenshot.png)

*Let op:* bovenstaand voorbeeld bevat bonus-opdracht elementen!

## Opdracht 1: opzet

Je gaat het ontwerp van deze webpagina zo gedetailleerd mogelijk namaken. Alle afbeeldingen en icoontjes die
worden gebruikt in de designs, zijn aangeleverd in de `assets`-map van deze repository.

In plaats van deze opdracht te clonen, maak je voor dit project een **eigen** project aan, _from scratch_! 
Wanneer je aan een nieuw project gaat beginnen, maak je eerst een goede basis. Anders wordt jouw code al snel een
rommeltje. Zorg daarom dat je onderstaande checklist afwerkt.

### 1.1 Projectopzet

- [ ] Maak een eigen project aan. Maak in het project alle benodigde bestanden aan, zoals een `index.html`, `styles.css`
  , `.gitignore`, een `README.md`.
- [ ] Download de afbeeldingen uit deze repository. Maak een map `assets` aan en zet alle afbeeldingen hierin. 
- [ ] Zet alvast een structuur klaar in commentaar in jouw CSS-bestand. Je kunt [deze structuur](#voorbeeld-css-structuur)
  gebruiken, maar voel je vrij om een eigen structuur te bedenken.
- [ ] Maak een repository aan op www.GitHub.com voor jouw project.
- [ ] Initialiseer Git in jouw project. Maak een commit en koppel daarna jouw repository aan dit project volgens de
  instructies op GitHub. Tip: weet je niet meer hoe dit moet? Volg dan de stappen uit de video (Hfst 4.2 van de cursus Git) één voor één op.
- [ ] Wanner dit is gelukt, maak je een feature-branch aan (`git checkout -b uitwerkingen`).  Op deze branch schrijf je jouw uitwerkingen, zodat deze later gemakkelijk kunnen worden nagekeken in een Pull Request.

### 1.2 Stylingopzet

- [ ] Declareer alvast een CSS-reset in jouw CSS-bestand. *Pssst*: vergeet jouw stylesheet niet te koppelen aan
  jouw `index.html`.

- [ ] De gebruikte fonts in de designs zijn `Merriweather` voor de headings en `Roboto` voor normale tekst. Deze fonts kun
  je gratis vinden op Google Fonts, zorg er alvast voor dat je deze importeert in jouw CSS-bestand en instelt
  als `font-family`.

- [ ] De ontwerper heeft de gebruikte kleuren voor ons
  aangeleverd: [bekijk het kleurenpalet hier](https://coolors.co/5722cd-4b49e8-f2f0ff-ed4385-0c0c0c). Het is handig om
  deze kleuren bovenaan jouw CSS-bestand te plakken, zodat je ze gemakkelijk kunt kopiëren wanneer je ze nodig
  hebt. *Tip*: je kunt ook gebruik maken van
  CSS-variabelen ([EdHub Hfst. 9.3](https://edhub.novi.nl/study/courses/514/content/12701)). Het gaat om de volgende
  HEX-codes:
    - Paars `#5722CD`;
    - Blauw `#4845E4`;
    - Roze `#ED4385`;
    - Zwart `#0C0C0C` (voor standaard tekst);
    - Lichtpaars `#F2F0FF` (voor de grote zwevende woorden, zoals "hello" en "services")
      *Uitzonderingen:*
    - Lichtgrijs `#F3F6F9` (voor de achtergrond van de projecten)
    - Grijs `#7A7A7A` (voor de service-tegel tekst);

## Opdracht 2: header en introductie

Je begint met het maken van de header en het introductieblok. Hiervoor heb je op voorhand bedacht welke
semantische elementen je nodig zult hebben. Voel je je zelfverzekerd? Kijk dan alleen naar de aandachtspunten en volg
jouw eigen plan! Als je meer houvast wil, bekijk dan eerst de aandachtspunten en werk daarna de volgende stappen af:

1. Zet eerst, *zonder* styling, alle benodigde HTML-elementen voor deze twee blokken in jouw `index.html`. Omdat je hier
   niet bent om je typediploma te halen, raden we je aan de [dummy tekst](#dummy-tekst) te kopiëren!
2. **Navigatiebalk**: zorg ervoor dat jouw menu-items netjes, naast elkaar, aan de rechterkant komen te staan. Maak het
   makkelijker voor jezelf door tijdelijk zwarte borders om jouw elementen te plaatsen, zodat je goed ziet wat je
   doet. *Pssst*: je hebt dit al gemaakt in de eerdere Flexbox opdracht!
3. **Content positionering**:
    1. **Header**: zorg ervoor dat de content van de header in het midden komt te staan. *Tip*: gebruik padding om de
       header wat meer hoogte te geven en blijf weg van letterlijke `height: 500px` properties.
    2. **Introductie blok**: doe nu hetzelfde voor de positionering van de introductie-tekst, om dit netjes in
       het midden te krijgen!
4. **Tekst en button**: nu kun je aan de slag met de details: pas de tekstkleur op beide blokken aan en maak de button
   zo gedetailleerd mogelijk na. Let hierbij bijvoorbeeld op de schaduw onder de button en het kleurverloop op de
   header!
5. **Witte icoontje:** voeg ten slotte het witte icoon aan de onderkant van de header toe. Dit kun je doen doormiddel
   van een `<img>`-tag, of door een `<div>`-tag met CSS een `background-image` te geven. Om hem vervolgens op de juiste
   plek te krijgen, zul je moeten spelen met positionering. Vergeet niet dat wanneer je iets absoluut positioneert, je
   het parent-element altijd een `position: relative;` moet geven!

### Aandachtspunten

* In de header is een *gradient* gebruikt met de aangeleverde kleuren blauw en paars. *Tip:* gebruik
  een [gradient-generator](https://cssgradient.io/) voor een mooi vloeiend verloop!

* De links in de navigatiebalk linken naar hun bijbehorende *gebied* op de homepagina: dit noem je een **jumplink**. Dus
  als de gebruiker op "Contact Us" klikt, krijgt hij het contact-formulier-gedeelte van de homepagina te zien. Hoe je
  dit implementeert, kun je nalezen op EdHub ([Hfst. 5.3](https://edhub.novi.nl/study/courses/514/content/12673)) onder
  het kopje "ID selectors".
* Zorg ervoor dat je de tekst op de button niet in letterlijke hoofdletters in de HTML zet. Dit is niet handig, want
  jouw klant (het bedrijf) zou ineens van gedachten kunnen veranderen! Gebruik altijd CSS om de tekst te transformeren
  naar hoofdletters.

## Opdracht 3: projecten

Je kunt nu aan de slag met het project-blok. Bekijk het ontwerp nog eens goed, lees de aandachtspunten goed door en maak
een duidelijk plan voor jezelf over hoe je dit gaat aanpakken.

### Aandachtspunten

* Om ervoor te zorgen dat afbeeldingen netjes mee schalen wanneer het scherm breder of smaller wordt, hebben we een
  andere aanpak nodig dan bij "normale" HTML-elementen. Dit doen we door onze afbeelding in een wrapper-element te
  wikkelen, zoals bijvoorbeeld een `<span>`:

```html
<span class="image-wrapper">
    <img src="..." alt="..."/>
</span>
```

![image-screenshot](./assets/screenshots/image-screenshot.gif)

Vervolgens geven we de afbeelding altijd een `width: 100%`, zodat ze altijd 100% van de *beschikbare ruimte* zullen
innemen. Het wrapper-element krijgt vervolgens een maximale breedte mee (doormiddel van `max-width` of `flex-basis`),
waardoor de afbeelding zich telkens zal aanpassen aan het omwikkelende element:

```css
img {
    width: 100%;
}

.image-wrapper {
    flex-basis: 800px;
    flex-grow: 0;
    flex-shrink: 1;
}
```

* Het is je waarschijnlijk opgevallen dat de volgorde van de tekst en de afbeelding zijn omgedraaid bij het 2e project.
  Dit zou je hardcoded in de HTML kunnen aanpassen, maar het is netter om dit met CSS te doen! Wanneer je één afbeelding
  en tekstblok samen in een container zet, ben je in staat om de volgorde van de content en afbeelding aan te passen met
  de `flex-direction` property. Je kunt de richting namelijk *reversen*! Daar lees
  je [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flex-direction) meer over.
* ... en als je alvast wil inspelen op het feit dat er in de toekomst waarschijnlijk meer projecten bij komen, waarbij
  je ieder 2e, 4e en 6e project omgedraaid moet zijn, kun je
  daar [deze speciale selector](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child) voor gebruiken.
  Door `:nth-child(even)` te gebruiken op de containers, wordt alleen ieder 2e, 4e, 6e, ..., 24e element aangesproken:
  dus alle *even* getallen. Super handig wanneer er nog meer projecten bij komen!

## Opdracht 4: services

Je kunt nu aan de slag met het services-blok. Bekijk het ontwerp nog eens goed, lees de aandachtspunten goed door en
maak een duidelijk plan voor jezelf over hoe je dit gaat aanpakken.

### Aandachtspunten

* Alle iconen op de service-tegels vind je terug in de meegeleverde `assets`-map. Dit zijn SVG's die je
  simpelweg kunt invoegen met een `<img>`-element.
* Vergeet de schaduw achter de service-tegels niet!
* Het services-blok is een mooi voorbeeld van een flexbox-container, waarin je de tegels een basis-breedte kunt geven
  met de `flex-basis`-property. Denk er aan of de tegels mogen meegroeien of mee krimpen wanneer de schermgrootte
  zich aanpast.

## Opdracht 5: contactformulier en footer

Je kunt nu aan de slag met het contact-formulier en de kleine zwarte footer. Bekijk het ontwerp nog eens goed, lees de
aandachtspunten goed door en maak een duidelijk plan voor jezelf over hoe je dit gaat aanpakken.

### Aandachtspunten

* Bouw eerst de basis van het formulier op in HTML. Maak correct gebruik van de submit-button, inputs,
  labels en `name`-attributen. Doe dit vóór je begint met styling;
* Het contact-blok heeft eenzelfde vloeiende kleurverloop als de header;
* Blijf weg van absolute breedtes wanneer je invoervelden gaat stylen. Gebruik altijd een `width: 100%` en laat het
  formulier (of een ander omwikkelend element) bepalen hoe breed de velden moeten zijn.
* *Tip*: je kunt placeholders stylen doormiddel van de `::placeholder`-selector!

## Bonusopdracht

1. Gebruik CSS-variabelen om de kleurcodes in op te slaan zodat je deze in jouw stylesheet kunt gebruiken.
2. Zorg ervoor dat de lijnen tussen de verschillende secties schuin aflopen door een uitgerekte CSS driehoek toe te
   voegen!
3. Voeg de zwevende woorden "hello", "work" en "services" toe achter de content. Dit kun je doen door de tekst
   letterlijk in de HTML te zetten, maar het is beter om dit te doen door een **pseudo-element** te gebruiken *(EdHub
   Hfst. 9.2)*.
4. De lijnen onder de project-titels wil je invoegen als een pseudo-element. Dit doe je door de
   afbeeldingen door middel van de `background-image`-property op een pseudo-element te plaatsen. Op deze manier vervuil
   je de HTML niet met "nutteloze" elementen.
5. De gradients zijn in het bonusontwerp voorzien van een doorzichtige textuur. Deze kun je als pseudo-element via een background-image invoegen.
   Let op dat de textuur **onder** de content moet komen te staan.
   Lees [hier](https://css-tricks.com/perfect-full-page-background-image/) meer over de `background-image` property.
6. Zorg ervoor dat er een transitie ontstaat wanneer de gebruiker over de project-links hovert *(EdHub Hfst. 9.5)*:

![bonus-moving-link](./assets/screenshots/bonus/bonus-moving-link.gif)

## Schermontwerpen

### Basisontwerp

De screenshots zijn erg groot. Download de screenshots om ze te bekijken:

- [Desktop design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/basic/basic-desktop.png)
- [Mobiel design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/basic/basic-mobiel.png)

### Bonusontwerp

De screenshots zijn groot. Download de screenshots om ze te bekijken:

- [Desktop design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/bonus/bonus-desktop.png)
- [Mobiel design](https://github.com/hogeschoolnovi/frontend-html-css-concept-opdracht/blob/master/assets/screenshots/bonus/bonus-mobiel.png)

## Bijlage

### Voorbeeld CSS structuur

```css
/*////////////////////////
    Table of Contents
    1. Global Styles
    2. Typography
    3. Layout
        3.1 Reusables
        3.2 Other
    4. Areas
        4.1 Header
        4.2 Introduction
        etc.
    5. Media Queries
////////////////////////*/

/* ------------------------------- 1. Global Styles -------------------------------- */

/* ------------------------------- 2. Typography ----------------------------------- */

/* ------------------------------- 3. Layout --------------------------------------- */

/* --------------- 3.1 Reusables ----------------------- */

/* --------------- 3.2 Other --------------------------- */

/* ------------------------------- 4. Areas ---------------------------------------- */

/* --------------- 4.1 Header ------------------------- */

/* --------------- 4.2 Introduction ------------------- */

/* ------------------------------- 5. Media Queries -------------------------------- */
```

### Dummy tekst

#### Your website is an investment in the success of your business.

We are here to help you succeed.

Let's work together

#### Hello

Rekupe is a digital agency in Los Angeles. We use strategic UX, SEO optimization and beautiful visual designs to help
your business grow. We see every project as a fresh opportunity, pushing ourselves to create new digital experiences.
Have a question? Click here to contact us!

#### Work

**Rolling Stone**

You know Rolling Stone. It’s the definitive voice in music, politics and culture. It’s a global icon.

**Variety**

Variety is an industry leader for breaking entertainment news, reviews and box office results with archive of content
dating back to 1905.

**Worth**

A global media platform connecting a community that embraces worth beyond wealth.

#### Services

**Web Design** Good web design is how companies stand out from their competitors. High quality web design leads to
increased user conversion and engagement. Through a proven web design process, we help clients launch websites and
products that improve on their bottom line.

**Web Development** Modern websites need to be responsive and fully functional at all sizes. We develop all of our sites
with a mobile first approach and ensure that our code quality is clean, organized and performant. Already have a design
but need it developed? We’re here to help!

**User Experience** In order to build successful products you have to understand the user. We create user personas,
wireframes and prototypes to test with users. This allows us to gather feedback which helps to shape the product and can
quickly eliminate potential risks – saving you time and money.

**Logo Design + Branding** Nike, Apple, Coca-Cola, Starbucks. What do all of these brands have in common? Easily
recognizable logos and brand identity. The best brands stand out from the crowd by having a clear and unique point of
view. We will work with you to understand your vision and help create a unique brand identity and style guide for your
company.

**SEO** Do you want your site to rank higher in search results? Google is constantly changing their algorithms for how
they rank pages. Don’t worry about constantly playing catch-up. We will make sure your website it optimized, providing
you the best opportunities for organic search exposure.

**Copy Writing** Brand messaging needs to be clear, direct and easy to understand to be effective. A unique tone of
voice will help you stand out from the crowd and build brand loyalty. We work with you to establish your brand bible and
ensure your messaging is focused and targeted.

#### Form

Let's work together

Have a question? Need a quote? Let us know!

#### Footer

Business website opdracht © NOVI Hogeschool 2022
