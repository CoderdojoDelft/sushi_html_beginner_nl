1. In het dashboard van Neocities, zie je de bestanden die samen je website vormen. Daarbij staat ook het bestand **style.css**. Open dit bestand door op `Edit` te klikken \(achter het bestand of al je eroverheen zweeft me je muis\).

   > CSS is de taal die beschrijft hoe een website eruit ziet. CSS betekent Cascading Style Sheets.

2. In het bestand staat het volgende:

   ```css
   body {
    background-color: white;
    color: black;
    font-family: Verdana;
   }
   ```

   > De kringelhaakjes `{ }` en de tekst daartussen is een verzameling **CSS regels**. Het woord `body` betekent dat deze regels gelden voor alle `<body>` elementen in je website. Het deel wat buiten de haakjes staat noemen we een **selector**. In dit geval is het dus een **selector** voor de **body** elementen.

3. Verander de kleur in `LightBlue`, klik `Save` en herlaad de pagina. Wat is er gebeurd met je site?

4. Hoe werkt dit? Open weer het bestand `index.html` in je editor. Daarin zie je de regel

   ```html
   <link href="/style.css" rel="stylesheet" type="text/css" media="all">
   ```

   > Deze regel vertelt aan de browser om op zoek te gaan naar een bestand met de naam `styles.css`. Een stylesheet kun je herkennen als een bestand dat eindigt met `.css`. Dit stylesheet bevat regels over hoe je pagina eruit moet zien.  
   > Elke regel bestaat uit een **eigenschap** met een `:` symbool \(dubbele punt\) erachter en daarna een **waarde** voor deze eigenschap, gevolgd door een `;` symbool \(puntkomma\).

5. Open het `style.css` bestand weer in je editor en verander de tekst in de `body` selector:

   ```css
   body {
    background-color: LightBlue;
    color: purple;
    font-family:  "Helvetica", sans-serif;
   }
   ```

6. Save en herlaad de pagina. Kijk wat er met je website is gebeurd.

   > De eigenschap `color` geldt altijd voor de tekst.

7. Je kunt ook regels toevoegen om je koppen er anders uit te laten zien dan je paragrafen! Hiervoor gebruik je de `h1` selector. Voeg de volgende code toe aan `style.css`, onder de gekrulde haakjes.

   ```css
   h1 {
    color: orange;
    font-family: "Times New Roman", serif;
   }
   ```

8. Save en herlaad de pagina. Ziet jouw site er nu ook zo uit?  
   ![](../assets/saved_styling.png)

   > Is het je ook opgevallen dat de letters er anders uitzien \(niet alleen een andere kleur\)? Dit is omdat je ook de **font family** hebt veranderd. Je kunt meer lettertypen \(fonts\) zien op [https://www.w3schools.com/cssref/css\_websafe\_fonts.asp](https://www.w3schools.com/cssref/css_websafe_fonts.asp)

9. Probeer ook een verzameling regels toe te voegen voor `<h2>` koppen door gebruik te maken van de `h2` selector.

10. Speel een beetje met verschillende kleurcombinaties voor de tekst en de achtergrond. Er zijn ontzettend veel kleuren die je kunt gebruiken. Een lijst me kleuren kun je hier vinden: [https://www.w3schools.com/cssref/css\_colors.asp](https://www.w3schools.com/cssref/css_colors.asp)



![](../assets/badges/thumbs/01_live.png) 
![](../assets/badges/thumbs/06_style.png)

