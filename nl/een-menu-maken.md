1. Je kunt je navigatie menu eruit laten zien als een cool menu door **CSS** regels toe te voegen in het stylesheet.

2. Weet je nog in welk bestand je stylesheet staat? Open `style.css` in de editor. Ga naar het einde van het bestand en voeg de volgende code toe:
```css
nav ul {
     background-color: tomato;
}
```
> Is het je opgevallen dat de ***twee selectors** gebruikt hebt in plaats van maar één? Als je alleen `ul` zou gebruiken, zou de regel voor *alle* willekeurige lijsten op je website gelden. Door de `nav` selector toe te voegen, wordt deze regel alleen gebruikt voor de lijsten tussen de `nav` tags.

3. Sla op, herlaad je pagina en kijk hoe het eruit ziet.
 
4. De bolletjes voor elk item in je lijst zijn niet zo mooi in een menu. Die gaan we laten verdwijnen. Open weer `style.css` en voeg het volgende toe onderaan het bestand. Doe dit weer een op een nieuwe regel, zodat het niet per ongeluk in een andere verzameling regels terecht komt.
```css
nav ul li {
    list-style-type: none;
}
```
> Merk op dat deze verzameling regels **drie** selectors heeft. Deze regels gelden voor alle `li` elementen in een `ul` lijst binnen een `nav` sectie. Pffff!
