1. Soms is het handig om informatie te laten zien in een tabel. Dat kan bijvoorbeeld zo zijn als je informatie van leden wilt laten zien van een sportclub of een school. In dit voorbeeld gaan we informatie over muziek in een tabel zetten.
> Een tabel is een raster dat bestaat uit **rijen** en **kolommen**. De meeste tabellen hebben ook titels bovenaan elke kolomen, een **kop** (in het Engels een header) genoemd.

2. Maak een tabel aan met de tags `<table>` en  `</table>`.
> Elke tabel bestaat uit een aan rijen. Elke rij staat tussen `<tr> </tr>` tags. Dat betekent dat alles tussen deze tags op één lijn staat. 

3. De eerste rij is de kop. In de kop staat elke kolom tussen `<th> </th>` tags. Onze tabel heeft drie kolommen: Artiest, Titel en Jaar. Je code ziet dan zo uit.
```html
<table>
    <tr>
      <th>Artiest</th>
      <th>Titel</th>
      <th>Jaar</th>
    </tr>
</table>
```

4. Nu gaan we een rij toevoegen. In een rij staat elke kolom tussen `<td> </td>` tags. Een rij ziet er dan zo uit:
```html
<tr>
     <td>Justin Timberlake</td>
     <td>Can't stop the feeling</td>
     <td>2016</td>
</tr>
``` 
![](/assets/tabel.png)

5. Je kunt nu je eigen favoriete hits toevoegen! Een nieuwe rij voeg je toe door een nieuwe set `<tr> </tr>  tags te gebruiken. Tussen deze tags zet je je **data** tussen `<td> </td>` tags.

6. Een extra kolom kun je toevoegen door een extra **data** item toe te voegen met de tags `<td> </td>` in elke rij. Je kunt ook een extra kop toevoegen door de `<th> </th>` tags te gebruiken. 

7. De tabel ziet er nu nog niet uit als een echte tabel. Dat kunnen we oplossen. Heb je al een idee waar. Juist! In `style.css`.

8. Type de volgende tekst onderaan je stylesheet. Het geeft niet als je het niet helemaal begrijpt. Probeer met de code te experimenteren en kijk wat er veranderd. Dan kun je een stijl maken die je zelf mooi vindt.
```css
table, th, td {
      border: 1px solid HoneyDew;
      border-collapse: collapse;
}
tr {
      background-color: PaleTurquoise;
}
th, td {
      vertical-align: top;
      padding: 5px;
      text-align: left;
}
th {
      color: purple;
}
td {
      color: purple;
}
```

Onze tabel ziet er nu zo uit:
![](/assets/tabel2.png)





