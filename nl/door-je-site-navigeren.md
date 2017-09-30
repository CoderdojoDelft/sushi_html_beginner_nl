1. Veel websites hebben een **navigatie** menu waarmee je gemakkelijk de verschillende pagina's kunt vinden. Je hebt nu een aantal pagina's, een homepage en links die ze met elkaar verbinden. Laten we de links verplaatsen naar een navigatie sectie bovenin.

2. Maak een header sectie bovenin je bestand, vlak nadat de body sectie begonnen is met de tags `<header>` en `</header>`. 

3. In deze header sectie maak je daarna een **navigatie** sectie met de tags `<nav>` en `</nav>`:
```html
  <body>
    <header>
      <nav>
      
      </nav>
    </header>
```
> 'nav' staat voor navigatie. De navigatie sectie is een verzameling tools waarmee je gemakkelijk naar de verschillende delen van je site gaat.

4. Ga nu naar je lijst me links en selecteer de tekst die begint met `</ul>` en eindigt met `</ul>`. Vergeet de driehoekige haakjes niet!
![](/assets/select_links.png)

5. In plaats van de tekst de **kopiëren**, ga je hem deze keer **uitknippen**. Dit doe je door de toetsen `Ctrl` en `X` tegelijk in te drukken. Schrik niet, de code verdwijnt nu.

6. Ga naar de `<nav>`en `</nav>` tags die je zojuist hebt gemaakt. Zet je cursor op de lege regel tussen deze tags. Zie je hem daar knipperen? **Plak** nu je code daar door de toetsen `Ctrl` en `V` tegelijk in te drukken. Je code moet er nu ongeveer zo uit zien.

```html
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="websites.html">Websites maken</a></li>
          <li><a href="badminton.html">Badminton</a></li>
          <li><a href="python">Spelletjes programmeren in Python</a></li>
        </ul>
      </nav>
    </header>
```
> Als een foutje maakt, kun je die **ongedaan** maken (undo in het Engels) door `Ctrl` en `Z` tegelijk in te drukken. Dit kun je in heel veel programma's gebruiken!

7. Sla het bestand op en herlaad je website. 

8. Je navigatiemenu wil je natuurlijk op alle pagina's van je website zien. Dit doe je door code in al je pagina's te plakken. Selecteer de hele header sectie en gebruik `Ctrl` + `C` om de tekst te **kopiëren**. Plak deze tekst in elke pagina in het begin van de body sectie (meteen na `<body>`.

 9. Als je al je pagina's hebt opgeslagen, kun je altijd naar één van je andere pagina's gaan! 