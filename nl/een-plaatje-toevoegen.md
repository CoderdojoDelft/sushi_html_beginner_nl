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
     <img src="/JOUW_PLAATJE">
```
> Merk op dat de `<img>` tag anders is dan de tags die we tot nu toe hadden gebruikt:
> * Er is geen sluitende `</img>` tag. Deze tag is **zelf-sluitend**: de openende tag eindigt met `/>`. Dit is omdat er geen 'begin' en 'einde' zijn, zoals wanneer je bijvoorbeeld een paragraaf typt.
> * De tag 