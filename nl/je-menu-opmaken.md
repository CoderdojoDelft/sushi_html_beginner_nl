Met CSS zijn de mogelijkheden om je menu er fantastisch uit te laten zien eindeloos. Open `style.css` weer in de editor (dit is de plek waar het gebeurt!). Sla het bestand elke keer als je iets verandert, op en herlaad je website.

1. Zoek je `nav ul` selector op en voeg nog een aantal regels toe, zodat het er zo uit ziet:
```css
  nav ul {
     list-style-type: none;
     display: inline;
     margin-right: 10px;
     margin-left: 10px;
     background-color: tomato;
     border-style: solid;
     border-color: MediumVioletRed;
     border-width: 2px;
     padding: 10px;   }
 ```
 > De eigenschap `padding` voegt wat extra ruimte toe. Kun je bedenken wat de andere eigenschappen doen ('border' betekent lijst, zoals om een schilderij).
2. Experimenteer met verschillende kleuren en verschillende hoeveelheden pixels.

3. Dat de links onderstreept zijn, is eigenlijk ook niet zo mooi. Deze kun je laten verdwijnen door de volgende regels toe te voegen na de regels voor `nav ul li`.
```css
 nav ul li a {
    text-decoration: none;
 }
```
> Je kunt de regel overal neerzetten, maar het handig om regels die met elkaar te maken bij elkaar in de buurt te zetten, zodat je ze gemakkelijk terug kunt vinden.

