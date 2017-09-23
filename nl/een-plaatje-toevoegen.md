1. Neocities heeft al een plaatje voor je op je website gezet. Kun je in `index.html` terug vinden waar ze dat gedaan hebben?
> Maar het is natuurlijk nog veel leuker als je zelf een plaatje kunt toevoegen. Zoek een plaatje op je computer die je op je website wilt laten zien. Als er niets op je computer staat, kun je natuurlijk ook een plaatje downloaden.

2. Een plaatje dat je wilt laten zien, moet ook op internet staan (bezoekers van je site kunnen gelukkig niet op je computer kijken). Daarom moet je je plaatje uploaden naar je site in Neocities.

3. Ga naar het dashboard van Neocities. Daar zie je knop met `Upload`. Klik daarop, zoek het plaatje voor je site en open het. Je ziet nu het plaatje in de lijst met bestanden staan. 

4. Onthoud of kopieer de naam van je plaatje, want die hebben we zo nodig.
![](/assets/plaatje_dashboard.png)

5. Ga nu weer naar `index.html` in de editor. Zoek daar de tekst:
```html
    <p>Here's how you can add an image:</p>
    <img src="/neocities.png">
```
Dit is waar Neocities het plaatje heeft neergezet en die gaan we vervangenen door jouw plaatje

6. Verander de tag met het plaatje (in plaatje van JOUW_PLAATJE type je de naam van jouw plaatje):
```html
     <img src="/JOUW_PLAATJE" alt="Mijn plaatje" width="300px">
```
Sla op en refresh je pagina.
> Merk op dat de `<img>` tag anders is dan de tags die we tot nu toe hadden gebruikt:
> * Er is geen sluitende `</img>` tag. Deze tag is **zelf-sluitend**: de openende tag eindigt met `/>`. Dit is omdat er geen 'begin' en 'einde' zijn, zoals wanneer je bijvoorbeeld een paragraaf typt.
> * De tag heeft extra delen informatie, die worden **attributen** genoemd:
    * `src` vertelt de browser welk bestand moet worden getoond (src staat voor source en betekent bron).
    * `alt` geeft een korte beschrijving dat de browser zal laten zien als het niet lukt om het plaatje te laten zien.
    
7. Waar denk je dat het attribuut `width` voor wordt gebruikt? (Hint: **px** is een afkorting voor **pixels**, de kleine puntjes waaruit je beeldscherm bestaat). Probeer eens verschillende getallen! Pas op, verwijder de letters `px` niet.

8. Verander ook de tekst in het `alt` attribuut, zodat het iets over je plaatje vertelt.
> Belangrijk: de attribuutwaarden zoals de bestandsnaam en de beschrijving moeten tussen aanhalingstekens staan.

